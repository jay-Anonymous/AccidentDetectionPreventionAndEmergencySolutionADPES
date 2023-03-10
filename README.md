## Accident Detection Prevention and an Emergency Solution (ADPES)

Road accidents have become a significant concern in Kenya, with high-speed driving and unaware drivers being the primary factors in road accidents. Increasing vehicle use has resulted in increased traffic disorder, which has increased the number of road accidents. In the event of an accident, some people are unable to reach the hospital on time due to traffic jams, lack of ambulance, and lack of necessary information. Here is an automated Internet of Things (IoT) based accident prevention, detection, and emergency solution. The system is designed to send signals to the nearest hospital in case of an accident. It detects whether a driver has consumed alcohol or not. If the sensor detects alcohol, The car will automatically stop until the smell is gone. It also detects when the driver is asleep due to the ride and triggers the buzzer sound. When the car detects an object nearly 30 cm. away, it will stop moving. When an accident occurs, the system will send the accident location to the nearest hospital through SMS.









## Feature

:heavy_check_mark: Accident Detection
:heavy_check_mark: Accident Prevention
:heavy_check_mark: Emergency Solution

## How Does It Works

* Accident Prevention
    ```
    To Prevent accident we used four sensor
    * Ultrasonic:  When the sensor detects an object nearly 30 cm it will stop the car.
    * PIR: It is used to monitor the driver motion. If the driver moved out from its range the car will stop immediately.
    * MQ3: Checking whether the driver is alcoholic or not.
    * Bazzer: When the PIR sensor detects that the driver is in a sleep, It will make noise.
    ```
* Accident Detection
    ```
    To Detect an accident we used only one sensor
    * Vibrator sensor: If the car crash, it will produce a signal. Based on the signal we do an emergency solution.
    ```
* Emergency Solution
    ```
    In Emergency solution we used some modules and a server
    * GPS NEO 6M: Get car current location in Latitude and Longitude.
    * SIM 800L: Do a post request with Latitude and Longitude and then send an SMS into the responsed phone number.
    * Server: The server calculate the shortest path between hospitals and the accident occured location and return hospital details as response.
    ```
*


## Module & Sensor Used

| S/N | Name/Model | Quantity | Type | Price | Image | Description
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
1 | Arduino UNO | 1 | Microcontroller | | ![]| Arduino Uno is a microcontroller board based on the ATmega328P (datasheet).
2 | 4WD Car Set | 1 | Car Chassis Kit | = | !| Four-wheel drive (4WD) is a vehicle system that powers the front and rear wheel axles at the same speed to help gain traction, according to Car and Driver.
3 | L298N | 1 | Motor Driver |  |  | The L298N Motor Driver is a controller that uses an H-Bridge to easily control the direction and speed of up to 2 DC motors.
4 | SIM800L | 1 | Module | = | | SIM800L GSM/GPRS module is a miniature GSM modem, which can be integrated into a great number of IoT projects.
5 | GPS NEO 6M | 1 | Module |  |  | The NEO-6M module includes one configurable UART interface for serial communication, but the default UART (TTL) baud rate here is 9,600.
6 | MQ3 | 1 | Sensor | | | Alcohol Sensor Module - MQ3. 4753. This module is made using Alcohol Gas Sensor MQ3. 
7 | Ultrasonic| 1 | Sensor | | | An ultrasonic sensor is an instrument that measures the distance to an object using ultrasonic sound waves.
8 | PIR | 1 | Sensor |  |  | PIR sensors allow you to sense motion, almost always used to detect whether a human has moved in or out of the sensors range.
9 | HC-05 | 1 | Module | |  | The HC-05 is a popular module which can add two-way (full-duplex) wireless functionality to your projects.
10 | Bazzer | 1 | piezo | |  | A buzzer or beeper is an audio signaling device, which may be mechanical, electromechanical, or piezoelectric (piezo for short).
11 | Vibrator | 1 | Module |  | | A vibration sensor is a device that measures the amount and frequency of vibration in a given system, machine, or piece of equipment. 
12 | Antena | 1 | Module | || Antenna for SIM800L GSM Module.
13 | 3.7v Battery | 3 | Module |  |  | 18650 3.7 Volt lithium-ion rechargeable batteries are cylindrical batteries used in mainly for laptop battery packs, telephones, electronic cigarettes, flashlights and cordless power tools.
14 | 1x Battery Case | 1 | Module | |  | The primary function of a battery holder is to keep cells fixed in place safely and securely while conveying power from the batteries to the device in question.
15 | 2x Battery Case | 1 | Module | |  | The primary function of a battery holder is to keep cells fixed in place safely and securely while conveying power from the batteries to the device in question.
16 | 2x Battery Charger | 1 | Module | | | Proper charging of Li-ion batteries enables the best performance and longest operational life to be obtained.
17 | Soldering Iron | 1 | Module | |  | Spool of solder. 1.6mm. A soldering iron is a hand tool used in soldering.
18 | Soldering LID | 1 | Module | |  | Soldering Lid.
19 | Rojon | 1 | Module | | | Soldering Rojon.
20 | Jumper Wire | 3 | Cable |  |  | RF jumper cables - Jumper cables is a smaller and more bendable corrugated cable which is used to connect antennas and other components to network cabling.




# AccidentDetectionPreventionAndEmergencySolution-ADPES-
# -AccidentDetectionPreventionAndEmergencySolution-ADPES
