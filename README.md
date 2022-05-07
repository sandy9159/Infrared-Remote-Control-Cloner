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



![image](https://user-images.githubusercontent.com/19898602/167253257-65bc9f08-af81-447e-bba8-4be502df5e68.png)


If you seriously need quality PCB quickly in your hand then you must have to try JLCPCB PCB manufacturing service. They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly. If new user signup today from this link [JLCPCB.com](https://jlcpcb.com/IAT) you will get welcome coupons from JLCPCB.


![image](https://user-images.githubusercontent.com/19898602/159014034-3c9a50c3-61c3-40d2-836d-9cadc2317d33.png)
![image](https://user-images.githubusercontent.com/19898602/164385177-de123350-4a1f-4d0f-9f38-68ed7dbd5a9f.png)



SMT Assembly service of [JLCPCB.com](https://jlcpcb.com/IAT) is cherry on top now get your PCB fully assembled and save your time and money
Select components for your PCB from there Parts Library of 200k+ in-stock components
they are offering $30 valued New User coupons  & $24 SMT coupons every month
$8.00 setup fee, and $0.0017  per joint

Now no need to order components separately for you PCB and get free from stress of soldering them on PCB just try PCB SMT assembly service and get you PCB with components pre assembled and ready for the project


👉 Try PCBA service of [JLCPCB.com](https://jlcpcb.com/IAT) and save your time and money, get PCB ready for project, 200K+ components in library of [JLCPCB.com](https://jlcpcb.com/IAT) as well as 3rd party         parts to choose from. 
    Assembly will support 10M+ parts from Digikey, mouser
    
👉 $30 valued New User coupons 

👉 $24 SMT coupons every month


* Follow the simple step to get this PCB board.

1 - Download the circuit board Gerber file: https://github.com/dilshan/ir-clone

2 - Create an account using the link below: [JLCPCB.com](https://jlcpcb.com/IAT)

3 - visit [JLCPCB.com](https://jlcpcb.com/IAT) Add the Gerber file and place the order. 







