# DIY-Rotary-tumbler-polishing-Machine

![tumbler](https://user-images.githubusercontent.com/19898602/141048286-8c61f946-ea0c-413c-9a6d-88d04a264b09.gif)


Hello friends in this video I have built a mini Rotary tumbler polishing machine,
This machine is powered by Arduino and custom PCB User can set the time for tumbler rotation.

This mini tumbler rotary polisher is used to polish small metal parts, 
Abrasive granules is placed in the tumbler and then we have to put metal parts in this tumbler

after that user have to set the time like how long we need to run this machine and what will be speed of the rotation
all this is done by using mini HMI, I have used nextion 2.8" HMI in this project.



# VIDEO
Here is the complete video of the project 


# COMPONENT USED

High Torque DC motor

L298N motor driver

Arduino Nano 

Wooden board of 12mm thick

20 x 20 aluminum profile

8mm pillow bearing

8mm SS rod

T8 lead screw and nut

Timing pulley

Timing belt




![image](https://user-images.githubusercontent.com/19898602/141048834-95fa2205-31fd-4398-8b7c-ad4614464d74.png)![image](https://user-images.githubusercontent.com/19898602/141048878-a23c2a07-cf42-4055-87de-3f1b3762aacb.png)

Here I have used 6mm Acrylic sheet for making the side panel of the machine, I design the 3d design in fusion 360 
and used same software to convert its g-code which is GRBL based.

then I used my home made CNC engraving machine to cut out the part, I have used 500W in this CNC machine and 2mm milling bit


![image](https://user-images.githubusercontent.com/19898602/141049188-6570581a-f294-4f31-91a8-b8011e5df353.png)![image](https://user-images.githubusercontent.com/19898602/141049239-88da6f02-5e2e-4f41-bdda-4ac19d85a05e.png)

Then I bring four 608Z bearing 8mm ID and 22mm OD I placed this bearing at ther position. 

![image](https://user-images.githubusercontent.com/19898602/141050556-62854910-083f-4826-9fa1-b47859dfeeb3.png)


Then I bring a high torque 12V DC motor, this motor

Nearly all types of DC motors have some internal mechanism, either electromechanical or electronic, to periodically change the direction of current 

in a part of the motor.DC motors were the first form of motor widely used, as they could be powered from existing direct-current lighting power distribution systems. 

A DC motor’s speed can be controlled over a wide range, using either a variable supply voltage or by changing the strength of the current in its field windings.

>> Base Motor RPM: 18000


>> Operating Voltage: 6-18 V

>> Rated Voltage: 12 V

>> Rated Torque: 34.2 N-cm

>> Stall Torque: 300 N-cm

>> Gearbox Dimensions: 25×37 (LxW) mm

![image](https://user-images.githubusercontent.com/19898602/141050768-92902c1f-f2fe-4d18-a287-edd6c2b4a2c4.png)![image](https://user-images.githubusercontent.com/19898602/141050795-2f0e16ef-c551-4496-80cb-07e5ee9fbe38.png)

Then I use 6mm threaded rod to connect the acrylic parts 

I have previously cut that 2 Acrylic parts using CNC machine I have also used dome nut to 

![image](https://user-images.githubusercontent.com/19898602/141051251-1eca3bde-a715-45c4-b61d-0107e66e8006.png)

Then I inserted 8mm SS smooth rod through the bearing and placed rubber roller on that so that bottle get grip
during rotaion

# CIRCUID DRAWING $ CUSTOM PCB

Making such projects without PCB is night mare yes trust me
you cannot get wanted result and professional touch in your project if you ignore PCB
So some days back I have developed my Multipurpose PCB.
This PCB is used to build wide range of arduino projects 

![Schematic_Multipurpose pcb_2021-09-15](https://user-images.githubusercontent.com/19898602/133383877-24044b9a-8d05-445a-808f-b6960dbe0e07.png)


followings are the some features of PCB

1. Wide range of power input 9V to 24V DC
2. Cross polarity protection
3. DC motor voltage selection 9V or 12 V DC
4. Servo motor voltage selection 5V or 9V DC
5. Manual microstepping setting for stepper motor
6. Power indication LED
7. L298N IC for heavier DC motor
8. ON board 5V and 9V regulator no need to arrange different power sources
9. Header pins and screw terminals for easy connections

List of the Components you can connect to the PCB

1. 2 DC motor ( 9V to 24V DC)
2. 2 Potentiometer
3. 2 Servo motors ( 5V to 9V DC)
4. 1 Serial device (BT module, HMI, Communication module, RX, TX)
5. 1 Encoder (2 interrupt pin & 1 PB pin)
6. 1 I2C device (SCL/SDA Device, display, MPU6050 etc)
7. 2 Stepper motors 


![MVI_0001 00_06_45_21 Still003](https://user-images.githubusercontent.com/19898602/133377296-ba24f45e-dcf4-4f97-9aa5-77aaed90175a.jpg)
![MVI_0001 00_07_21_22 Still004](https://user-images.githubusercontent.com/19898602/133377355-12dca9e1-068f-4cf5-ae58-84663ff57dde.jpg)

I have ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )

This is the link of [PCB editabl file](https://oshwlab.com/sharmaz747/multipurpose-pcb)

If you seriously need quality PCB quickly in your hand then you must have to try [JLCPCB](https://jlcpcb.com/IAT ) PCB manufacturing service.
They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly.
If new user signup today from this link [JLCPCB](https://jlcpcb.com/IAT ) you will get 30$ coupon from [JLCPCB](https://jlcpcb.com/IAT ).

![image](https://user-images.githubusercontent.com/19898602/138686998-33a08efe-93af-44e7-991a-c77a59e2c089.png)


![image](https://user-images.githubusercontent.com/19898602/138687262-b17b4deb-fd48-4701-91f0-2416cc24f77d.png)

This is 2.8" nextion HMI which have onboard stm 32 micro controller, this is best for user interface no need to hardwire any push button or other hardware to arduino for 

user interface, its GUI developmet is also very easy. 

This way we completed the assembly of the machine for more details you can watch the video on my youtube channel.

![MVI_0004_1](https://user-images.githubusercontent.com/19898602/141059771-19c9bd8f-6524-496a-98b0-8627b7cbee94.gif)



