easeOmeter project
==================

 

November 20th, 2018
-------------------

### Enclosure update:

 

Working with CorelDraw x6, we were provided a default file to work with. My
current edited version is just tall enough for the user to reach down and remove
the sensor, while still providing protection during transport. The file can be
found here, and a preview for it can be found below.

![](https://i.imgur.com/vujfWZx.png)

As I write this, the prototype lab is in the process of cutting the acrylic
case. I will update this post as further progress is made.

 

November 13th, 2018
-------------------

### PCB Update and hardware demonstration:

![](https://i.imgur.com/ebCmzvj.jpg)

Successful, and corrected PCB soldered, and tested! Correctly detects the proper
address.

![](https://i.imgur.com/areagqn.png)

Moving on to the python libraries to being reading values, I noticed that trying
to connect to the school’s Wi-Fi network was greyed out in the GUI. Upon further
research I discovered that connecting to enterprise networks is disabled by
default. A work around to this was to enter information manually into the
/etc/wpa_supplicant/wpa_supplicant.conf file as shown below.

![](https://i.imgur.com/tvKcRtr.png)

After installing python and the libraries for the sensor, the example code to
get readings works!

![](https://i.imgur.com/p7cy2ry.png)

 

November 6th, 2018
------------------

### PCB soldering milestone update:

![](https://i.imgur.com/Ek2YiUi.jpg)

Unsuccessfully detects, and I am aware of the problem, and the solution.

![](https://i.imgur.com/yxMU3zz.png)

### Progress Report:

The current schedule as of today is slightly behind. I unfortunately had a set
back where I got ahead of myself and failed to double check my sensor and
corresponding fritzing file. As a result, there was an error where my SDA was
located in the wrong spot along where the 8-pin header sits. I will need to get
my PCB remade for my mistake. This will set me back a few days but I will be
able to make up time by coming to school on my day off and working in the
prototype lab. Below is an image of the fixed error, and appropriate files are
located
[here](https://github.com/rfmaynard/Accel-MagnetoMeter/tree/master/pcb%20files).

![](https://i.imgur.com/acJG0JM.jpg)

I had everything soldered in the lab, and upon realizing my error, needed to
de-solder (a very handy tool by the way). Unfortunately, I had not documented
any pictures of the completed soldering. On the bright side, I was able to
procure an 8 and full GPIO headers from the prototype lab without any extra
costs. Financial status is still on track and has not changed. Overall, a minor
set back, but having already had the experience to solder it all, test, and
de-solder. Performing it the second time around should be a little faster and
feel more comfortable. Will be on track for next week (Week 11).

 

October 30th, 2018
------------------

### Fritzing and PCB Update:

![](https://i.imgur.com/gYxyjnZ.jpg)

### Progress Report:

The schedule of the EaseOmeter is proceeding as expected, and as stated before,
I am fortunate to be not hitting any major road blocks as of yet. The fritzing
was completed on time with the help of my professor’s clarification on some
designing techniques. It was suggested to prevent any lines from crossing as
that would interfere with the PCB etching, as well as instructing us on the
proper use of via’s and differentiating the differences between the top and
bottom of the PCB. I should be able to hit the Week 10 milestone next week.

Financial status is still OK as of right now and I am currently refining and
double checking the PCB part on fritzing before send off to the lab for etching.
Ground needs to be sent around the pins still as it would conflict with the GPIO
pins in the Raspberry Pi.

 

October 23rd, 2018
------------------

### Build Update:

![](https://i.imgur.com/Uye91vq.png)

Successfully Detects!

![](https://i.imgur.com/ADmRp7r.png)

### Progress Report:

While on track for the most part, I fell behind in week 7 slightly as most
students had their sensors soldered. I made up the gap by mock bread-boarding my
sensor and Pi over the weekend leading toward week 8. One of the problems I
encountered was finding the correct GPIO labeling for this sensor as it is not
one of the more popular devices. Another neat solution to connecting to my Pi is
via a direct ethernet cable to my laptop along with VNC. This provides a simple
and quick connection.

As for any other extra amenities required, I needed an ethernet cable to connect
the Pi directly to my laptop, which happened to be lying around. Fritzing is
almost completed for the PCB etching in week 9. In all, this project is on track
and luckily, no major road bumps have occurred as of yet.

 

October 2nd, 2018
-----------------

### Proof of Purchase:

![](https://i.imgur.com/mXrPxaY.png)

![](https://i.imgur.com/jeV3cju.png)

![](https://i.imgur.com/x5FFRfP.png)

September 25th, 2018
--------------------

Budget Posted. Can be found
[here.](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/documentation/EaseOMeter_Budget.pdf)

 

September 18th, 2018
--------------------

Schedule Posted. Can be found
[here.](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/documentation/EaseOMeter_Schedule.PNG)

 

September 11th, 2018
--------------------

Proposal Posted. Can be found
[here.](https://github.com/rfmaynard/Accel-MagnetoMeter/blob/master/documentation/RyanMaynard_EaseOMeter_Proposal.pdf)
