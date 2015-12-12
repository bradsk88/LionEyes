LionEyes
========

### I have discontinued development on this project

A simple android application / arduino device used together to determine the current location of the elevators at my apartment building.
  
The Plan:  
-------
  
Using a pressure based elevation sensor strapped to a battery-powered arduino with WiFi, I will post the current elevation of the
elevator at any given time (intervals + intelligence) to a database.  
  
Complementing this Arduino system, I will develop a simple Android app with the following functions.  
  
1) Show which floor each elevator is on **now**  
2) Extra - Display a history graph showing where each elevator has been.  
3) Extra - Allow the user to request an alarm that will go off when an elevator will be on their floor "soon"  
---- This will require some artificial intelligence and will be largely a "ball park" estimate.  
  
Why am I making this?
-------

This system is **extremely** specific to one purpose.  This system will be installed at my apartment where the elevators,
despite recent upgrades, are quite slow.  Sometimes, when you are running late (as I am, often) it might make more sense to
take the stairs than to wait for an elevator.  
  
Unfortunately, there is no "current floor" display by the elevator doors on each floor.  So when a person presses the button
to request an elevator car, they have no way of knowing how long it will be until the car arrives.  Based on my experience,
the wait can be anywhere between 0 seconds (it's already there) to 20 minutes (when only one elevator is in service, and
someone is moving in or out of the building).

I'm also just making this system for experience.  I have written a few Arduino programs, but never anything especially useful.
I'm also going to make the server which supplies the REST interface for the Android app using Node.js, which I have only just
starting learning how to use.  
  
In Summary
-------
  
Provide a convenience for the tenants of my apartment who have Android phones (myself included)  
Make a very small profit (have to break even on parts).  
Learn Node.js  
Improve arduino knowledge
