# Frequently asked questions

Questions about the previous (2018) CSUR release were collected from existing posts on social media and are addressed below. Some of the problems have already been fixed in new CSUR, while some others are inherent features or limitations of the CSUR system.

**Why can't I put bus stops on both sides of the road in a CSUR asset?**
- Problem fixed in new CSUR. Bus stops can be normally placed on all symmetric two-way CSUR roads. 

**When I remove pillars from some CSUR roads and reload my save, the road model is strangely twisted.**
- Problem fixed in new CSUR. In some old CSUR assets, a road option only intended for power lines is mistakenly turned on. As a result, the game treats the road segment without pillars as a power line missing the pylon, which causes the problem. 

**A shift module can't be bent into a curve. There is usually an empty space between a shift module and a connecting road, making it difficult to tweak the angles.
- The shift modules in the old CSUR was designed not to be bent. This allows for tuning the traffic path without significantly changing how the model looks, which prevents cars from glitching out of the model. New CSUR removed this design and shift modules are smooth curves.

**Cars does not move along the road on shift modules. Sometimes they even fly out of the road.**
- The game mechanics limits that the vehicle paths have to be parallel to the road segment. Since the model of shift modules is not parallel to the segment, cars cannot move exactly according to the road markings. New CSUR resolves the flying-car glitch by removing one effective lane in the vehicle path from shift modules with 2 or more lanes. The old CSUR resolves it as described in the previous item.

**Does CSUR require DLCs to play?**
- No, new CSUR does't require any DLC.

**Is there an interface module between two roads (e.g., 4DR and 6DR)?**
- The interface modules in new CSUR are calculated by the program, so there is an interface module between any two connectable roads. Particularly, most two-way interfaces in the old CSUR have been replaced by pairs opposing one-way interfaces.

**Is there a module with BRT (bus rapid transit) lanes?**
- Modules with BRT lanes are included in the new CSUR, in which the two innermost lanes are intended for BRT traffic.

**Can I set a dedicated marked zone for vehicles waiting to turn left in an intersection? (Such markings are common in Asian cities such as in China and Japan)**
- This is currently not supported in new CSUR. The game requires vehicles to stop before the intersection and extra mods are needed to make vehicles wait inside it.

