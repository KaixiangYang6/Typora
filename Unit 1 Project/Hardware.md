# Anatomy of a Turntable: A Beginner’s Guide

https://www.recordplayerpro.com/anatomy-of-a-turntable-a-beginners-guide/#anatomy



127-47=77



https://youtu.be/MwdANEcTiPY

https://dronebotworkshop.com/arduino-color-sense/

![image-20211123024621044](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211123024621044.png)

Photodiode sensitivity changes with color.

Output for each color is not linear.

Output is not RGB vaule

Sensor calibration required to get RGB.

  Some sensor can sense infrared light.

TCS230/TCS3200

![image-20211123025307872](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211123025307872.png)

![image-20211123105254281](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211123105254281.png)

![image-20211123111946785](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211123111946785.png)

![image-20211125114356941](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211125114356941.png)

![image-20211125114417130](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211125114417130.png)

laser cut requirement

3D.ai

3D printing.stl



GitHub.cin.

![image-20211124005026873](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211124005026873.png)

parameters of motor:

motor diameter; 15MM      length; 11.4MM    screw length: 74MM   

slide length; 90.74MM  this length includes motor    slider stroke   55MM 

Slider size  25*15.5   this value will be biased, because each time is different,

The motor is a two phase four wire  18 degree  pitch 3MM  

The fastest moving speed of about 300MM/ minutes

![image-20211125113553871](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211125113553871.png)

![image-20211125114142768](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211125114142768.png)

![image-20211125114206029](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211125114206029.png)



Big Easy Driver Hookup Guide

https://learn.sparkfun.com/tutorials/big-easy-driver-hookup-guide?_ga=2.186204009.1917338984.1638317226-338482071.1638317226#hardware-overview

![image-20211201012858876](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211201012858876.png)

#### Board Top Pins

- **Coil A+**: DMOS Full Bridge 1 Output B. Half of connection point for bi-polar stepper motor coil A.
- **Coil A-**: DMOS Full Bridge 1 Output A. Other half of connection point for bi-polar stepper motor coil A.
- **Coil B+**: DMOS Full Bridge 2 Output B. Half of connection point for bi-polar stepper motor coil B.
- **Coil B-**: DMOS Full Bridge 2 Output A. Other half of connection point for bi-polar stepper motor coil B.
- **GND**: Ground.
- **M+**: Power supply. 8V - 35V.

**Check the coil serial number and wire colour to correctly match the coil serial number to the pins on the driver board**.

If don't know the wire pairs for each coil on the motor.

For a 4-wire motor, take one wire and check its resistance against each of the three remaining wires. Whichever wire shows the lowest resistance against the first wire is the pair mate. The remaining two wires should show similar resistance between the two of them.



The **potentiometer** on board is included to allow users the ability to select the current provided to the motor. It ranges from 0mA to 2000mA (2A). This will require you to be aware what current range your motor can handle - check the motor's data sheet for the current settings. 

I should adjust the current to 500mA.



Once the motor is connected, you can then connect a power supply to the Big Easy Driver. You can use any kind of power supply (desktop, wall adapter, battery power, etc.), but verify that whatever choice you go with is capable of providing up to 2A and falls in the range of 8V to 35V.

<img src="https://cdn.sparkfun.com/assets/learn_tutorials/2/3/9/Big_easy_driver_HookupFixed.jpg" alt="img" style="zoom: 33%;" />



Infrared radiation was accidentally discovered by an astronomer named William Herchel in 1800. While measuring the temperature of each color of light (separated by a prism), he noticed that the temperature just beyond the red light was highest. IR is invisible to the human eye, as its wavelength is longer than that of visible light (though it is still on the same electromagnetic spectrum). Anything that emits heat (everything that has a temperature [above around five degrees Kelvin](https://www.livescience.com/50260-infrared-radiation.html)) gives off infrared radiation.

![IMG_4637](/Users/yangkaixiang/Downloads/IMG_4637.JPG)





​	



![image-20211202015548178](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211202015548178.png)

差值

https://www.youtube.com/watch?v=A9F1ezGgaC4



https://www.youtube.com/watch?v=sqvsMHDMZ2o







https://www.youtube.com/watch?v=xre5y_jYn8c

![image-20211202024319259](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211202024319259.png) 



https://www.youtube.com/watch?v=g57r_4OQvqI

https://www.banggood.com/DANIU-HY-18-Handheld-Thermograph-Camera-Infrared-Temperature-Sensor-Digital-Infrared-Thermal-Imager-p-1465679.html?utm_campaign=10363491_1465679&utm_content=10534&p=AW300023511642201807&cur_warehouse=CN

MLX90640BAB Field of view angle 55*35 degrees (small angle, suitable for long distance measurement)



![image-20211202031723182](/Users/yangkaixiang/Library/Application Support/typora-user-images/image-20211202031723182.png)