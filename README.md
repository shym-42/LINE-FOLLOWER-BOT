This is my line follower robot project — a small but fast bot that can follow a black track on a white surface all by itself.
It uses Arduino Nano for the brain, QTR-8A sensors for “eyes,” and a PID control system to keep it smooth and steady.

I built it to learn more about robotics, sensors, and control systems, and also because… well… watching it zoom around the track is just plain fun.

COMPONENTS REQUIRED:

 1.  Arduino Nano – the bot's microcontroller

 2.QTR-8A reflectance sensor array – detects the track

 3. TB6612 motor driver – tells the motors how fast to spin

 4.N20 12V 600 RPM motors – moves the robot forward

 5.44mm wheels + caster wheel – lets it roll freely

 6.12V LiPo battery – Supplies the power to the bot(both to motor and arduino).

 7.A simple chassis (perforated board) to hold it all together

 #WORKING:
 The qtr 8 array sensor detects the black line using its low 
 
 reflectance value.The arduino takes these sensor input value and analyses whether its a black line or white line,our code
 
 tells that if its a black line make the bot move .This is the basic working principle of the bot.The coding is done in such a way
 
 that the bot analyzes the black line and moves the bot acccordingly even in sharp bends and acute turns in the path by controlling the motor by a PWM
 
 signal from the nano microcontroller to the motor driver based on the sensor input.A 12 V Lipo battery is used to supply the power to arduino via a DC-DC

 buck converter and to supply 12v to the motor.To control the bot effectively we have used PID algorithm which works on moving the bot in the right direction by 

 calculating the present,past and future errors.


 
 

 

