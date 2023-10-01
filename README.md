# Home_Security_Alarm

**ABSTRACT**
The need for home security alarm systems nowadays is a serious demand. As
the number of crimes are increasing every day, there has to be something that
will keep us safe. We are all aware of the high end security systems present in
the market but they are not easily available to everyone. We therefore intend to
provide a solution by constructing a cost efficient electronic system that has
the capability of sensing the motion of the intruders and setting off the alarm.
The basic idea behind this project is that all the bodies generate some heat
energy in the form of infrared which is invisible to human eyes. But, it can be
detected by electronic motion sensor.

The project involves the use of Arduino, motion sensor, buzzer, LCD display
and a simple program. The sensor detect any motion in its permissible range
and triggers the alarm.

It will also send the signal to Arduino which processes the signal and set off
the alarm along with detection message on display. With this system we can
easily set up a security alarm in our home for unwanted intruders.


**CIRCUIT DIAGRAM**
![image](https://github.com/VikashiniPramanathan/Home_Security_Alarm/assets/95960472/1211a20d-7d77-462f-b09e-a77bd160a5c0)


**COMPONENTS REQUIRED**
• Arduino UNO
• PIR sensor
• Jumper wire
• USB cable
• Laptop
• SIM
• GSM module 900A


**WORKING OF THE CIRCUIT**
**COMMUNICATION BETWEEN ARDUINO AND SENSOR:**
• PIR sensor(Passive Infrared Radiation) observes motion by sensing the difference in
infrared or radiant heat levels emitted by surrounding objects.

• When the PIR sensor detects any motion, the output will be high. This is detected by
the Arduino UNO(initial release of Arduino software) which can be used to turn on an
alarm or it can be used to turn on any light as an indication that intruder is detected.


**COMMUNICATION BETWEEN ARDUINO AND GSM MODULE:**
• The Tx (Transmitting serial data with serial 0) pin of the Arduino board is connected to
the Rx(Receiving serial data with serial 1) pin of the GSM module and the Rx pin of the
Arduino is connected to the Tx pin of the GSM module .

• When the motion is detected by the Arduino then it communicates with the GSM
module via serial communication to make a call to the pre programmed mobile number.

