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

3.  Insert your SD card into the SD card reader, logo facing out, and plug it
    into your computer.

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

8.  Power down with `sudo powerdown` from the terminal by pressing `ctrl+alt+t`
    and set the Pi aside. We will not be using it until sensor testing.

**Step 2: Breadboarding and prototyping**

Here I will cover basic sensor connectivity to the Raspberry Pi by using a
breadboard for creating a mock layout/design that will be used in the PCB
creation stage.

1.  Gather the following items: Breadboard, LSM303 Sensor, and 4 Female-to-Male
    GPIO cables.

2.  Identify the labels on the sensor. For basic usage, we will be using: 3.3v,
    GND, SDA, and SCL.

![](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/images/LSM303zoom.png)

1.  Identify the corresponding pinouts on the Raspberry Pi. [This website is a
    great tool to use if your are unsure.](https://pinout.xyz/#)

2.  Plug in the female part of the GPIO cables into the Raspberry Pi’s 1,3,5,
    and 6 pins, based on the chart from pinout.xyz. These are the pins we are
    going to be using for this project.

3.  Using the 8-pin connector that came with the LSM303 sensor, plug it into the
    breadboard and rest the LSM303 onto it as a placeholder.

4.  Connect the corresponding cables from the Raspberry Pi into the matched
    holes for the sensor.

5.  Voila! You have your mock up sensor connection!

It should look something like this:

![](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/images/breadBoardprototype.png)

Now we can proceed to the PCB and soldering!

### PCB/Soldering

This is the part of the project that needs to be proceeded with care and
caution. I have made mistakes with my PCB design and case, however, I am
fortunate enough to have the resources at Humber to create 2nd or 3rd revisions
within a day or two. For those without access to such resources, it is advised
to double check your designs before purchasing etching and cutting services.

**Step 1: Fritzing**

[Fritzing](http://fritzing.org/download/) is an open-source application that
easily allows the user to create PCB schematics for different development
platforms. It is highly customizable and easy to use.

1.  [Download](http://fritzing.org/download/) and extract Fritzing. Installation
    notes are on the linked page for various operating systems.

2.  (Optional) Download the [AdaFruit Fritzing
    Library.](https://github.com/adafruit/Fritzing-Library) Handy if you want to
    take the extra step and create a mock connection in Fritzing.

3.  Download my Fritzing file
    [here](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/pcb%20files/LSM303pi2.fzz)
    and open it. From the PCB tab, you can make changes at your leisure and pick
    it apart to see how it was made.

4.  Export as gerber. File \> Export for Production \> Extended Gerber and
    select an appropriate folder. These files will be required to create and
    etch your PCB.

### Power Up

 

### Unit Testing

 

### Production Testing

###  

 
