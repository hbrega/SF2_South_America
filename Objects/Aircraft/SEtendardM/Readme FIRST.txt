Super Etendard v1.00
by foxmonter.
Revised by capun 3/27/06

--------------------
Read the History and specs to know about this craft.

Read The cockpit help to see the features of this cockpit. (is not 100% realistic but I try!)
--------------------

Credits
Model work by FoxMonter
Textures by FoxMonter
FM by Charles
Weapons Fix & Package by capun

Install.
--------
1- Just copy the SEtendar folder into your ...\objects\Aircraft\

2- Then Copy the files inside the weapons folder to your ...\objects\weapon\

3- Copy and paste this lines to your weapondata.ini, adjust the numbers to be the next sequential numbers in you weapondata.ini

[WeaponDataxxxx]
TypeName=Pod_SUE
FullName=External POD
ModelName=PodSUE
Mass=50.500000
Diameter=0.032000
Length=2.449000
AttachmentType=NATO,FRANCE,ARGENTINA
NationName=France
StartYear=1970
EndYear=0
Availability=1
BaseQuantity=8
Exported=TRUE
ExportStartYear=1970
ExportAvailability=1
WeaponDataType=4
JammerType=0
JammerStrength=0.000000

[WeaponDataxxxx]
TypeName=Rack_SUE
FullName=Double Rack Bomb
ModelName=RackSUE
Mass=50.000000
Diameter=0.040000
Length=2.011000
AttachmentType=FRANCE,ARGENTINA
NationName=France
StartYear=1970
EndYear=0
Availability=3
BaseQuantity=12
Exported=TRUE
ExportStartYear=1970
ExportAvailability=3
WeaponDataType=6
WeaponsRackType=TWIN_BOMB
NumWeapons=2
LoadLimit=900.000000
LengthLimit=3.050000
Attachment01Position=-0.253000,0.076000,-0.213000
Attachment01Angle=0.000000,0.000000,0.000000
Attachment02Position=0.253000,0.076000,-0.213000
Attachment02Angle=0.000000,0.000000,0.000000

[WeaponDataxxx]
TypeName=AM39
FullName=AM-39 Exocet
ModelName=am39
Mass=855.000000
Diameter=0.430000
Length=4.412000
AttachmentType=NATO,WP,UK,FRANCE,ARGENTINA,W_GERMANY
NationName=FRANCE
StartYear=1975
EndYear=0
Availability=1
BaseQuantity=2
Exported=TRUE
ExportStartYear=1975
ExportAvailability=1
WeaponDataType=1
RailLaunched=FALSE
RocketPod=FALSE
Retarded=FALSE
Streamlined=TRUE
FinStabilized=TRUE
SpinStabilized=FALSE
HasGrowl=FALSE
EffectClassName=LargeMissileEffects
ReleaseDelay=0.000000
WarheadType=0
Explosives=160.000000
FusingDistance=0.000000
ClusterBomblets=0
ClusterDispersion=0.000000
GuidanceType=5
Accuracy=95.000000
MaxTurnRate=20.000000
MaxLaunchG=3.000000
LockonChance=95.000000
LaunchReliability=95.000000
ArmingTime=2.000000
SeekerFOV=25.000000
SeekerGimbleLimit=25.000000
SeekerTrackRate=15.000000
SeekerRange=90000.000000
MinLaunchRange=5000.000000
MaxLaunchRange=80000.000000
Duration=600.000000
CounterCountermeasure=0.000000
NoiseRejection=0.000000
CapabilityFlags=0x00300003
BoosterStart=1.000000
BoosterDuration=10.000000
BoosterAccel=50.000000
BoosterEffectName=MissileFireEffect
BoosterSoundName=Missile
BoosterNodeName=
BoosterPosition=0.000000,-1.128000,0.000000
SustainerDuration=0.000000
SustainerAccel=0.000000
SustainerEffectName=
SustainerSoundName=
SustainerPosition=0.000000,-1.128000,0.000000
InFlightEffectName=MissileInFlightEffect
InFlightSoundName=
ReleaseAnimationID=-1

[WeaponDataxxxx]
TypeName=Tank_SUE
FullName=1100 Ltr Drop Tank
ModelName=TankSUE
Mass=855.000000
Diameter=0.670000
Length=4.269000
AttachmentType=
NationName=
StartYear=0
EndYear=0
Availability=0
BaseQuantity=0
Exported=FALSE
ExportStartYear=0
ExportAvailability=0
WeaponDataType=5
MaxFuelAmount=840.000000
Asymmetrical=FALSE

4- The current weapons pack has a "AM39 Exocet", it seems to be the Surface to Surface Missile version. Make the following changes to the entry

[WeaponData809]
TypeName=MM39                                ; Change to this from AM39
FullName=MM-39 Exocet SSM             ; Change to this
ModelName=mm39                                ; Change to this

5- Execute the weaponeditor, load the weapondata.ini and save it!.

DONE!

-------------------
If you got low FPS, disable the shadows!, the cockpit have high polys count and large textures! but is work great on my machine.

Post your comments in the forums or emailme. foxmonter@hotmail.com
-------------------

ENJOY THE FLIGHT.