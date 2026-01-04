# MEH01-mod
Mods to MEH01 rotary encoder from https://github.com/EverydayErgo/MEH01

The changes made are listed below.
No changes interfere with interpoperatiliby with base MEH01 parts and are meant to be only slightly functional and primarily style-based changes from original.
I create these using FDM printing and not resin SLA so these changes may not be as valuable to folks in SLA scenarios.  My primary motivation for the changes started with assembly challenges in my setup mostly fitting the select button into the frame and clearance challenges and making several of these for folks thus wanting to make assembly easier.  This led to a rabbit hole of tweaks.  It must be mentioned that I overall see no problems with the original design in a purely functional sense and these mods are driven by my specific utilization of the design and my printer/workflow/etc..

Functional Modifications:

* The perimeter flare added to the model allows for positive seating in the socket beyond just the redention bumps.  I travel with my kbd and can't guarantee it won't be pressed inappropriately so added this.
+ The holes for the encoder wires were centered to align with the pins on the encoder (possibly a difference in how the model of encoder I used lines them up) reducing stress on wires inside the body.  It does lead to vertical motion on the wires with each click.  Not likely an issue but something to watch.
+ Added fillets to most corners and thickening of some wall sections that I had issues with fracturing in early pieces I printed, and overall increase in component strength.  
+ Moved the button cable holes from being paired on one side to each end of the button position as vertical holes offset from the 3 central ones.  Some of the strength changes I had made cable routing more challenging as there was less clearance and I also moved to using 28G wire rather than 30 making it even more challenging.  As such the cables can now almost all drop straight down.
+ The button retention design was changed including:
  + Sloped the internal edge retaining the switch to make it easier to insert while still having some physical retention. there is little forces inside the body and the wire retention keeps the switch in place with this just fine so far.
  + Tapered the cutout in the wall to allow for the solder tabs on the switch to fit and have the top narrower to keep the switch aligned.  Overall makes switch insertion easier.
  + Increased some clearances, likely to accomodate my FDM process or the specifics on the switch component I got from Ali.
+ Created a version of the encoder knob part that allows for insertion of a 1/16" piece of hex key shaft (bloody imperial units.....) in place of the printed plastic piece.  I didn't have any problems with the printed version but again, I travel with my kbd and the risk of forces perpendicular to the axis of the encover breaking it bothered me.  This change can be filed under individual paranoia if desired or used.  I got a set of 1/16" hex wrenches from Amazon/Ali and just cut them off and clean them up with either a file or a dremel cutoff wheel.  They were a good press fit into the knob.

Stylistic Modifications:  

I have a lot of curved surfaces in my Cosmos (https://ryanis.cool/cosmos) keyboard design and I wanted the encoders to fit more seamlessly into that design overall.  

* Removed majority of right angles at edge interfaces which also reduced stress concentration points, thickened the wall that holds the rotational pin as well as balanced the opposite wall a little and smoothed a bunch of edges in general.

Other:
Will be putting a fusion .f3d file up here eventually once I'm fully happy with the tweaks so people can further iterate.  I think this design is fantastic and I have chanced none of the functional dimensions so this will fit in any existing MEH01 socket.  If you have suggestions to further improve this direction please let me know!

The models.
Snaps from Fusion as the PCTG models I printed are dark and shiny as heck and make for terrible photos.
![Main Body](https://github.com/PedanticAvenger/MEH01-mod/blob/main/images/MEH01-Mod-1.png?raw=true "Modified Body - 1")
![Main Body](https://github.com/PedanticAvenger/MEH01-mod/blob/main/images/MEH01-Mod-4.png?raw=true "Modified Body - 2")
![Modified Roller](https://github.com/PedanticAvenger/MEH01-mod/blob/main/images/MEH01-Mod-2.png?raw=true "Modified Roller - 1")
![Modified Roller](https://github.com/PedanticAvenger/MEH01-mod/blob/main/images/MEH01-Mod-3.png?raw=true "Modified Roller - 2")
