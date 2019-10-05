Linobot AGV parts list
Already Have
Lidar: Kinect
//which model? running on 12v 1a?

Microcontroller: Raspberry pi 3/B+ (download ARM based dev)
runs 5v 2a
Buy:
IMUs: MPU9250
https://www.robot-r-us.com/sensor-inertia/9-axis-mems-imu-breakout-mpu-9250.html $16.50 or
https://www.aliexpress.com/item/32216818498.html $2.90usd

Teensy (3.3v but 5v tolerant signal, runs from 5v)
https://www.robot-r-us.com/vmchk/arduino-stuff/teensy-3.2-32bit-arm-72mhz-cpu.html $30

2 Motors with encoder (minimize slip)
https://www.aliexpress.com/item/32872592243.html x2 = $29.40usd
// the 12V 110rpm one has high torque, just worried too slow. Comes with 11step encoder

Motor driver runs from 5v and 12v
https://www.aliexpress.com/item/32820492945.html x2 = $10.50usd
// the BTS7960 only can drive 1 motor, so we need 2

optional: Teensy Shield

Power
LiPo Batteries
https://www.robot-r-us.com/battery-charger/polymer-lithium-ion-battery-2200mah-3s-20c-lipo-pack.html $35
 //3S pack should be fine
Voltage converters
12V
https://www.aliexpress.com/item/32967443167.html $5.80usd //preferred so we can put the motors on the 12v as well (since high current)... then maybe need capacitors to filter high inductance load
5V : LM2596S
https://www.aliexpress.com/item/32964690227.html $0.90usd

cheap ass housing wire terminal block to distribute the power -$2 from hardware shop
Acrylic sheet to mount everything 

without batteries, total cost around $105sgd

https://github.com/linorobot/linorobot/wiki/1.-Getting-Started
