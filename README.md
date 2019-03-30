# QMRD3
Qualification Model Rover Demonstrator for Deep Drilling

Thanks to Roger-random, who created the amazing Sawppy rover on which this design is based.

Please view my blog post to see images of this project. Two Fusion 360 screenshots are provided in the repository.
      
This project is intended to be a testbed for future work on developing Mars ice drilling technologies. It would not be possible 
without the pioneering work by Github user Roger-random, who created the amazing Sawppy rover on which this rover is based. 
The Sawppy is a truly amazing and elegant design at an affordable price.

Unfortunately, this rover is not cheap. The wheels are around $100 each to print. 

The Rover Chassis has reached Version 1.02 and all components have been prepared for the larger size. The drive motors are from makermotor
and are available at: https://makermotor.com/pn00113-6-6-rpm-gear-motor-12vdc-high-torque/ while the steering motors are from Amazon seller
STEPPERONLINE and can be found by searching for the following listing: STEPPERONLINE 47:1 Planetary Gearbox Nema 23 Stepper Motor 2.8A. 
The mounting bracket for the stepper motor is required and will match up to the bolt pattern on the steering corners. 

The electronics, etc. have not been designed yet. It would be nice to adapt the Ardupilot Rover but it may be difficult to run the steppers
in this configuration. One idea may be to have steering changes executed as macro code by the autopilot. As in, the rover moves to a way 
point, and when it is there it executes the macro at that way point to do a steering maneuver. 

You can find more about Roger's original Sawppy rover at https://hackaday.io/project/158208-sawppy-the-rover 
and https://github.com/Roger-random/Sawppy_Rover

You can find more about the Mars Drilling Project at http://www.quinnmorley.com/2018/09/the-mars-drilling-project.html

Note: This rover uses the following bearing in 28+ locations: https://www.thingiverse.com/thing:3116838
      The bearing is a remix and therefore is released under a separate license and is maintained on Thingiverse. Two sizes are provided,
      88mm fits nicely when the bearing housings and printed with the diameter parallel to the xy plane, and the 87mm version fits nicely
      when the bearing housings are printed with the diameter perpendicular to or at odd angles to the xy plane. 
      Thanks to Zh4x0r for creating the parametric model with an integral lip, and thanks to Emmett for inventing 
      the gear bearing and completely changing the game.
