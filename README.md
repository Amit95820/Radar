# Radar

requirements:-

ultrasonic sensor.
arduino.
servo.
jumpers.
arduino IDE.
processing software.

here there are three files radar_processing, servo_processing and OCRAExtended-30.vlw
radar_processing is the processing file which can be opened through processing software.
link:-  https://processing.org/download

OCRAExtended-30.vlw is the file which is responsible for the animation of radar, without this file no output screen will be shown

servo_processing is an arduino file. which controls the servo. it will run in arduino ide.


1. now copy these three files to a folder of any name. 

2. and inside the above folder, create another folder naming "data" and paste the OCRAExtended-30.vlw file inside it.

3. now upload the servo_processing to your arduino.

4. open radar_processing in processing software and code contains comments which will easily guide you. 

5. make changes accordingly in the processing file and then run it. 

this is a radar which is used to detect the object within its range. here ultrasonic sensor is placed on the servo and the servo is rotated
between certain angles.

side by side processing software will genrate a radar image with green lines showing that there is no object and red lines showing that an
object is being detected.


