Accel/Magnetometer project build instructions
=============================================

Table of Contents
-----------------

1.  [Introduction](https://github.com/rfmaynard/Accel-MagnetoMeter#introduction)

2.  [Bill of
    Materials/Budget](https://github.com/rfmaynard/Accel-MagnetoMeter#bill-of-materialsbudget)

3.  [Time](https://github.com/rfmaynard/Accel-MagnetoMeter#time)

4.  [Assembly](https://github.com/rfmaynard/Accel-MagnetoMeter#assembly)

5.  [PCB/Soldering](https://github.com/rfmaynard/Accel-MagnetoMeter#pcbsoldering)

6.  [Power Up](https://github.com/rfmaynard/Accel-MagnetoMeter#power-up)

7.  [Unit Testing](https://github.com/rfmaynard/Accel-MagnetoMeter#unit-testing)

8.  [Production
    Testing](/github.com/rfmaynard/Accel-MagnetoMeter#production-testing)

### Introduction

Hello and welcome to the (unofficial) build instructions and guide to using the
LSM303 Accelerometer and Magnetometer. The scope of this little project is to
learn and integrate a piece of hardware and broadcomm development platform
together. In our case, we will be using a Raspberry Pi B as our platform. All of
which can then be used for real world applications.

//system diagram to go here.

Now let’s get into it!

### Bill of Materials/Budget

Budget with part links
[HERE](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/documentation/BeginnerBudget.xlsx)

![](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/images/budgetcut.png)

Firstly, you will need to acquire certain parts in order to complete this
project. Shown above is the price break down for each component used. You may
not need all of them listed items, but it is everything I was required to use to
get the project to completion.

### Time

![](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/images/scheduleCut.png)

This project ran its course over an entire school semester (4 months, \~15
weeks), and the amount of time spent on it per week, on average I’d say was
about 1 to 2 hours. Assuming that those reading this are at the average skill
level in using a computer and hardware, a user would be able to complete this
potentially over a weekend. The one time constraint that isn’t always certain is
how long the parts will take to arrive. When ordering your parts, ensure that
the seller/supplier provides appropriate delivery time estimates. This will
ensure smooth assembly of your project!

### Assembly

**Step 1: Preparing your Raspberry Pi**

In this step we will cover basic Raspberry Pi imaging so you are able to login
and access your device to test and drive your sensor later on!

1.  Download the latest [Raspberry Pi
    image](https://www.raspberrypi.org/downloads/). My recommendation is NOOBS.
    This will ensure that starting off, you will have almost everything you need
    if you decide to re-purpose the device later on.

2.  Download [etcher](https://www.balena.io/etcher/). This program will allow
    you to burn the Raspberry Pi image to your SD card.

3.  Insert your SD card into the SD card reader and plug it into your computer.

4.  Open etcher and follow the on screen instructions to burn your image. I
    found this program the easiest to use. [Extra documentation if
    needed](https://www.raspberrypi.org/documentation/installation/installing-images/README.md).

5.  Insert the SD card into your Raspberry Pi along the underside of the device.
    Plug all of the required cables in such as: ethernet, HDMI cable, mouse,
    keyboard, power, and turn the device on.

6.  Upon boot you will see an option for different operating systems. Select
    **Raspbian** and follow the on screen instructions to complete the OS
    install. If you want grab a coffee or snack as the install may take some
    time.

7.  At this point the Pi should boot to desktop. Follow the additional set up
    options on screen.

8.  Power down with `sudo powerdown` from the terminal and set the Pi aside as
    we will not be using it until sensor testing. Your Pi is ready to go!

**Step 2: Breadboarding and prototyping**

Here I will cover basic sensor connectivity to the Raspberry Pi by using a
breadboard for creating a mock layout/design that will be used in the PCB
creation stage.

1.   

 

### PCB/Soldering

 

### Power Up

 

### Unit Testing

 

### Production Testing

###  

 
