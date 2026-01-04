# MEH01-mod
Mods to MEH01 rotary encoder from https://github.com/EverydayErgo/MEH01

The changes made are listed below.
No changes interfere with interpoperatiliby with base MEH01 parts and are meant to be only slightly functional and primarily style-based changes from original.
I create these using FDM printing and not resin SLA so these changes may not be as valuable to folks in SLA scenarios.  My primary motivation for the changes started with assembly challenges in my setup mostly fitting the select button into the frame and clearance challenges.  This led to a rabbit hole of tweaks

Functional Modifications:

* The perimeter edge added to the model allows for positive seating in the socket beyond just the redention bumps.  I travel with my kbd and can't guarantee it won't be pressed inappropriately so added this.
+ The holes for the encoder wires were centered to align with the pins on the encoder (possibly a difference in how the model of encoder I used lines them up) to reduce stress on wires inside the body.
+ Added fillets and thickening of some wall sections that I had issues with fracturing in pieces I printed, and overall increase in component strength.  
+ Moved the button cable holes from the side to each end of the encoder as vertical holes offset from the 3 central.  Some of the strength changes I made cable routing more challenging and I also moved to using 28G wire rather than 30.  As such the cables can drop almost straight down.
+ The button retention design was changed including:
  + Removed the internal edge retaining the switch, there is little to no side to side forces inside the body and the wire retention keeps the switch in place.
  + Tapered the cutout in the wall to allow for the solder tabs on the switch to fit and have the top keep the switch aligned.
  + increased some clearances, likely to accomodate the FDM process or the specifics on the switch component I got from Ali.
+ Created a version of the encoder knob that allows for insertion of a 1/16" piece of hex key shaft in place of the printed plastic piece.  I didn't have any problems with the printed version but again, I travel with my kbd and the risk of forces perpendicular to the axis of the encover breaking it bothered me.

Stylistic Modifications:  

I have a lot of curved surfaces in my Cosmos (https://ryanis.cool/cosmos) keyboard design and I wanted the encoders to fit more seamlessly into that design overall.  

* Removed majority of right angles at edge interfaces which also reduced stress concentration points, thickened the wall that holds the rotational pin as well as balanced the opposite wall a little and smoothed a bunch of edges in general.

Other:
Will be putting a fusion .f3d file up here eventually once I'm fully happy with the tweaks so people can further iterate.  I think this design is fantastic and I have chanced none of the functional dimensions so this will fit in any existing MEH01 socket.
