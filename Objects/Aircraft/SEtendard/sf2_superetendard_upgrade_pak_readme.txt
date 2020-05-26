Dassault Super Etendard, SF2 Upgrade Pak (by FoxMonter)                           10/6/2011

For SF2, Any & All (Full-4 Merged Prefered - At Minimum, =MUST= have SF2:I) 

*Note: There are 2 cockpit/Avionics ini provided - it's set up right now for one modified from the Kfir C1_77, hence the "must have Full-4/SF2I tag'. For those NOT having a Full-4 Merged and/or SF2I, the original 2005 cockpit is included. Instruction for switching back are in the "To Install" section.*

This is a complete aircraft package.
It is a major upgrade to the aircraft, with a new 95% SF2 compliant FM, adjusted weapons loadouts, new cockpit & avionics (albeit a stock one repurposed), skins, decals and French weapons* (mostly from the GunnyPak and modified to fit the situational needs).  Operational service years have been adjusted to fit, as the Super Etendard (Modernized) is also being released. There WILL be some major overlap. The aircraft is fully operational from carriers, having been tested on all available; both stock 3rdWire and add-ons.
(*Please Note: the nuke effects for the AN-52 and ASMP are =NOT= included)

3 skins are included, with their attendant decals:

Flotille 11 by MigFly
"FN" (French Navy dark blue, 14Flot?) by Pete "pappycksix" Fredico
ARA (Argentine Navy) also by Pete (iirc)

As expected, the canopy operates with the Shift/0 key. Wingfold is operated via Shift/9. 
The loadout ini has several "Year and Nation Specific" loadouts, that WILL change during year progerssions - from convention bombs to LGBs. Argentina has it's own, albeit with French weapons, specificed as well (dumb bombs, rocket pods, Exocet). They all work, at least during MY testing...

As always, fairly easy to follow, detailed install instructions are included. So, please read them!! I'd reccomend that you unzip this archive FIRST (to a temp folder or your desktop), and READ through this readme document before installing.
The "Notes" section also conatins a Change List of modifications. All original readmes are included.

Happy Hunting!

------------------------------------------------

=TO INSTALL:

As I always reccomend, unzip the "sf2_superetendard_upgrade_pak.zip" to a temp folder or your desktop or somewhere else that's easy to find

Then, simply, copy/paste the Objects folder supplied directly =OVER= your existing folders. The things will find their way to where they're supposed to be....
 
You'll WILL be asked "OVERWRITE?", just say YES 

I've already seperated out the various folders , so they'll drop right where they're supposed to be. Cause it just SOOOOOOOOOOOOOOOO much fraking easier this way, ain't it?

----------------------
Cockpit Information:

For those without SF2I or non merged installs (if that's even possible; you poor bastards!! lol!!):

The main ini (SEtendard.ini) is set up with commented-out section for reusing the old original cockpit, as seen below:

[AircraftData]
AircraftFullName=Super Etendard
AircraftShortName=Super Etendard
AircraftDataFile=SEtendard_DATA.ini
//CockpitDataFile=SEtendard_CABINA.ini  <---
LoadoutFile=SEtendard_LOADOUT.INI
HangarScreen=SuEtendard_Hangar.jpg
LoadingScreen=SEtendard_LOADING.jpg
LoadoutImage=SEtendard_LOADOUT.bmp

CockpitDataFile=SuE_2Cockpit.INI
AvionicsDataFilename=SuE_2Avionics.INI
AvionicsDLL=Avionics70.DLL

//AvionicsDLL=Avionics60.dll             <----
//AvionicsDataFilename=SuE_AVIONICS.INI  <----
UserList=SuE_UserList.ini

You just comment out the "new" sections, and uncomment the 'old' ones. Like below:

[AircraftData]
AircraftFullName=Super Etendard
AircraftShortName=Super Etendard
AircraftDataFile=SEtendard_DATA.ini
CockpitDataFile=SEtendard_CABINA.ini  
LoadoutFile=SEtendard_LOADOUT.INI
HangarScreen=SuEtendard_Hangar.jpg
LoadingScreen=SEtendard_LOADING.jpg
LoadoutImage=SEtendard_LOADOUT.bmp

//CockpitDataFile=SuE_2Cockpit.INI       <---
//AvionicsDataFilename=SuE_2Avionics.INI <---
//AvionicsDLL=Avionics70.DLL             <---

AvionicsDLL=Avionics60.dll             
AvionicsDataFilename=SuE_AVIONICS.INI  
UserList=SuE_UserList.ini

Although WHY you'd want to, when the Kfir pit looks & works SOOOOOOOOOO much better ... well, no accounting for taste, eh?

---------
Adding Squadron Listings to the SquadronList.ini:

Extract, if you haven't already, the SquadronList.ini from the MissionData001.cat. Place it in the /PilotData folder.

Then, copy/paste the info below at the end, where *** is the next number in sequence:


[Squadron***]
Name=14Flot
DisplayName=14 Flottille
Nation=FRENCHNAVY

[Squadron***]
Name=11Flot
DisplayName=11 Flottille
Nation=FRENCHNAVY

[Squadron***]
Name=2ARA
DisplayName=2da Escuadrilla Aeronaval de Caza y Ataque 
Nation=ArgentineNavy


I've used a small "decal cheat" to force the Game Engine (tm) to see a Level 1 decal, and turn on the Squadron name window in the Loadout Screen.

----------------------------
Notes:

The base load uses French weapons. For those wanting Argentine weapons, for a Falklands/Malvinas era, it's suggested to get the Argentine weapons, and create a nation-specific loadout (as seen in the Loadout.ini herein). 
You will most likely have to add ARGENTINA to the AttachmentType= on all the hardpoints. It also might be a *VERY GOOD IDEA* to create a nation-specific version of the aircraft itself for JUST CANA usage, with the appropriate weapons. "How To" is in covered in the CombatAce SF/Wo* Knowledge in a turorial by me.

As I have/couldn't find any data on possible Argentine PGMs, they are not set for up them. One can assume (oh! that word!) that a modernazation program is under way for them as well. (Wiki mentioned something to that effect)

Changes/Additions:

95% SF2 compliant FM - might still use some tweeking,
New Userlist.ini with correct dates and availability,
Avionics updated as per SF2 usage; RWR is audio only,
DDS damage textures,
Fixed/cleaned canopy glass on original cockpit,
Repainted original HUD tgas a brighter color,
New SF2 style hangar screens (jpg format),
Nationalized/Year Specific Loadouts,
The aforementioned 'decals cheat' for squadron name listing,
Wing position lights 'attached' to folding wings so they move with it

An interesting note on the original HUD displays -- they change brightness based upon sun angle. It's like FoxMonter built these transparant cylinders into the cockpit lod that react to shading and light. Very cool! (from the guy that knows next to nothing about working in MAX!!)

It should be noted that I've given the radar far greater capabilities than it should have. The Avionics Gurus are welcomed, !!welcomed I say!! to make any and all necessary adjustments to make it a bit more realistic, but keeping within the realms of fun & playability!

Any and all mistakes, as always, are mine.
---------------------------------------------------------------------------------
Credits:
FoxMonter for the Original Release (with some help by capun)
MigFly for the 11F found at the old C6 site
Pappycksix (Pete Fredrico) for ARA original skin
??? -meaning I don't know who did the original decals .. but Thanks!
Fubar512 and Baffmeister for FM assistance - couldn't have finished it without their insights and assistance!!
Me for most of the other stuff (solid gray lo-viz skin), all the ini work, modifiying decals, etc, assembling the package and so for
TK, of course, for the whole series

Some very good people at CombatAce;
Gunrunner for 'local intell'
Soulman Carlo for locating the 2 TMF skins
Florian for pointing me to the fix for the 2 nukes

Sources:
yah,right....see above
Osprey Combat Aircraft #28: Air War in the Falklands (good stuff here!!)
Super Profile Series: Super Etendard -- a hard to find, but good book on the subject.

---------------------------------------------------------------------------------
If you have any problems, questions, comments, I can be reached in the usual places; CombatAce, SimHQ, or via the email addy below.

Happy Hunting!
Wrench
Kevin Stein

kjstein@ca.rr.com

--------------------------------------------
Legal BS:
This is freeware; it CAN be distrubuted if the original readmes and all other pieces of the package remain intact.
The names of all contributors, modders, suppliers, etc =MUST= be listed in any new readmes.
This package may NOT in any way, shape or form be used in any payware additions. 
Bribes are accepted; ask for the day's going rates

-------------------------------------------
