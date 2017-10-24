# HW4
---
Eng.

Program was writen in LEGO® MINDSTORMS® EV3 Software is developed and distributed by the LEGO Group, DK-7190 Billund, Denmark. 

https://www.lego.com/ru-ru/mindstorms

Simple implementation of PID controller was created to improve the robot movement at a given distance from the wall. 
The coefficients were: P = 0.3, I = 0.003, D = 5. Increasing the proportional coefficient. Make robot too sensitive. 
Integral rate allows to ignore. This derivation prevents the excessive rotation during the trajectory correction. 
But it also can reduce robot performance.

The file 4.ev3 is the work itself.
the principle of work is the following:
- the corridor is permissible for driving straight (from 13 to 17 the wheels rotate at the same speed)
- If a deviation to the right turn left.
- If you turn left, turn to the right.
-When turning, reduce the speed of the driving wheel, for better control of the state of the object.

Problems:
when turning the sensor can begin to see that it moves away from the target although it makes the maneuver almost in place.
Decision:
   Reduce the speed of rotation so that the program can respond
   
 Results can be found here:   https://www.youtube.com/watch?v=EeTn4x6Xcu8&feature=youtu.be
   
---
