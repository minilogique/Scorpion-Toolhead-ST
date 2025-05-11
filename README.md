![alt text](https://github.com/minilogique/Scorpion-Toolhead-ST/blob/main/images/abs.PNG)


I wanted a toolhead for CNC TAPv2 that also supports big hotend, has CPAP cooling and has clear access and visibility to the nozzle and hotend for maintenance. It uses the same Stealthburner carriage pattern so if it holds the classic Stealthburner, this here also fits.

Let's start from the top - extruder carrier. Cutdown version of the original carrier from CrownCooler toolhead and possibly even the original Stealthburner extruder mount. I have not tested the fitment, but it might work. Added access holes for 3mm hex tool for easier access, strengthened frame around heat insert. Uses same hardware as official Stealthburner part.

The length of the microbowden for Rapido version is 27.5mm and for Goliath version it's 20.5mm.

Hotend carriage - originally with 4010 axial fan on CrownCooler toolhead and fairly chonky look with added duct for part-cooling-cooling so it would not melt. I did not have any luck with 4010 as the backpressure caused by the heatbreak ducting hindered the fan almost useless with PETG prints with closed enclosure. So, enter high-performance SUNON 2510 axial fan and heatbreak ducting with perfect ducting. Uncut Peopoly Lancer Long hotend at 220C took the heatbreak radiator with freshly added thermal paste just below 40C and hotend at 300C the heatbreak barely got over 51C. Measured with a bit more expensive multimeter with thermal probe up to 1000C. Installs with same hardware as Stealthburner for the main mounting points, additionally three 5mm M3 heat inserts that might need some filing in the radiator tunnel.

Part-cooling - original ducts that are available for CrownCooler cool great, look decent but do not work with CNC TAP carriage as the lower portions on the toolhead plate obstruct the space the ducts use. At first I tinkered around with asymmetrical front-mounted ducts that were single piece the part-cooling power was sub-par. Lurking around in other printers communities I stubled upon a dual-duct design for VzBot printers by VITALS. I got the thumbs-up for adapting it to my toolhead and after about a month or so I have the properly working and rigid part-cooling system. Uses two M3x6mm flathead bolts to mount the ducts to the lowest M3 holes on CNC TAP toolhead carrier and after that you install the manifold with two M3x12 regular hexheads to the duct and one M3x8 hexhead to the front top side to secure the manifold and note that - CPAP hose does not need a cable tie as if you pull the hose on the manifold and then tighten up the M3 bolt, it will squeeze the hose between the manifold and toolhead itself. Greatly benefits from having the CPAP hose tied to the umbilical/PTFE tube.


ATTENTION - the ducts themselves should be printed with something more heat-resistant if you plan to print with plate above 100C as these ducts will get soft and sag causing collision with the prints. So in that case use at least ASA-CF or something more baller like nylons or polycarbonate etc.

Models are not placed as how to print them. In my experience Orca slicer has automatically managed to choose the best orientation for these parts and it is higly recommended to tune in your supports for these prints as at least front piece and the manifold will need the supports so it might never get an official Voron Mod status, but it's an awesome toolhead nevertheless in my opinion.
 

Beta phase is over. Renamed the toolhead from ScorpionCooler to Scorpion Toolhead or ST for short and added a quick iteration of hevORT toolhead's TentaCool part cooling duct as a secondary option (this is as of today, untested, but the VITALS' duct is proven). Did some minor fixes here and there.

![alt text](https://github.com/minilogique/Scorpion-Toolhead-ST/blob/main/images/actual.JPG)
