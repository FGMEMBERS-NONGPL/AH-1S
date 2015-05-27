Bell AH-1S Cobra

License:  Creative Commons CC-BY-NC-SA

David Culp
davidculp@cox.net


************************************************************************************

Credits:

Thomas Kreitler:  JSBSim rotor code, FDM, 3D model and texture
Jack Mermod:  Sound
Dave Culp:  FDM, 3D model and texture


************************************************************************************

I've put this model together to test the helicopter support for JSBSim.  Thomas
Kreitler did most of the work.  Originally I was using Jack Mermod's AH-1 model, 
but it was too advanced for my needs, so I borrowed the sound configuration, and
studied the way Jack integrated the model with FlightGear.

Note that some more work needs to be done with the propulsion models in JSBSim
in order to get this finished.  Until then the engines used here are electric,
so you won't see turboshaft engine parameters.

At sim start-up you'll be on the ground.  The throttle slider on your joystick is
your collective control.  The slider should be full forward for minimum collective.
You may have to jiggle the slider first to convince the simulator that is in fact 
full forward (since the start-up default assumes full aft slider).  Press the "u" 
key to engage the rotor governor.  Press "j" to close the rotor clutch.  The rotors 
will spin up to operating speed.

After landing, press "u" to disengage the rotor governor.  The rotors will spin down 
slowly.  You can brake them by pressing the "k" key to toggle the rotor brake.

