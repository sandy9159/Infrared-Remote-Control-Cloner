# Infrared-Remote-Control-Cloner

![image](https://user-images.githubusercontent.com/19898602/167252582-ad757130-7a80-4673-bb33-61000d700980.png)


IR Clone is an open-source IR remote control analyzer tool. This utility can analyze any IR remote control that modulates the IR signal with a 38kHz carrier signal. 

This utility has an option to store and retrieve up to 16 IR signals. 

In addition, it has PC software to analyze and edit captured IR signals.

The hardware component of this analyzer is built around the STM8S003F3 MCU. It has 24LC32 EEPROM installed to store the captured IR signals. 

This unit is designed to operate with a 5V to 9V DC power source or a 3V battery. 

![image](https://user-images.githubusercontent.com/19898602/167252622-a0dadfa3-5b56-43b9-8479-1f8c8a41c536.png)


Operating modes such as capture or replay can be changed using an onboard jumper on the PCB. These operating modes can change at any time without restarting the unit.

In addition to the IR clone PCB, the only external component needed to operate this system is a 4×4 matrix keypad. Most of the generally available 4×4 keypads can directly couple with this system.

The dimensions of the IR Clone PCB are 41.2mm × 32.1mm, and it has been designed using both SMD and through-hole type components. 

In this given design, the TSOP1838  IR decoder has been used to capture the incoming signals.

The output stage of this system consists of LD271, KCL5587S, or equivalent  880nm to 950nm (IR) LED. The 38kHz modulation signal required by the output stage is generated using built-in timers of the STM8S003 MCU.


![image](https://user-images.githubusercontent.com/19898602/167252634-1fd33240-3016-40cb-b499-c40254166d6f.png)

Captured waveforms stored in the EEPROM can be decoded directly using the IR Clone software provided in the repository. Using this application, the user can visualize and edit the captured signals. Both IR clone software and hardware supports up to 16 channels.

To transfer the EEPROM data to the PC, use any 24LC family compatible EEPROM reader or programmer. In our presentations, we used an inexpensive CH341A based programmer to read and write the 24LC32 EEPROM.

In addition to the IR Clone software, the repository also contains a sample Python script that exhibits decoding of EEPROM data.
