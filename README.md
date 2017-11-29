# sigrok_ipython_scope
An Ipython notebook that works as a sort of scope for a sigrok (tested
on Hantek 6022BE).
I have developed this on Windows 10 machine.  I started it because I
couldn't find a scope application that worked with the sigrok drivers
nor a way to make pulseview tirgger automatically like a scope.
An additional reason is that it can be the basis of building a complex
 triggering and logging system.  For instance I have a onewire
micropython controller that misreads about every hour.  I would like to
catch each of those traces and see if I can debug them.

# Status

This is now useful to me, it provides an interactive display and I can
see what is happening.  I am getting about 5000 points and it refreshes
about twice a second.

It is by no means perfect!

## Requirements
Assuming that you have already got sigrok-cli installed, and ipython.




