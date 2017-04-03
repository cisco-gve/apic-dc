The monitor file is using APIC test bed in RTP in order to login and pull the health score. This original Pi idea and design
was created by Kris Sekula. Our idea was to create this first Pi and then us a nicer Pi with a big display, rather than LED's in
order to display this (image 1). The original Pi was using the bars on an set of LED's, 8 lights high by 4 wide, to show
the health score based off how many rows of LED's were on. The use case for the Pi was to have this sit in an executives office
and have the CIO/CTO be able to see the health score. However we noticed that it would be hard to understand if you had to constantly
remember the ranges that were contained by each row. So we wanted to create a better way to display the health score and display
more information. The monitor.py code is used to create (image 2) and we created (image 3) which is a better way of displaying
the splash page as it contains more information. I will be uplaoding the code needed to get the LCD screen working with the 
Pi's Pixel OS and how to get it to autoload the splash page using the built in browser. 
