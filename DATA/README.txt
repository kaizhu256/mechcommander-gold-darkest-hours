**From original cMunsta extract**

Just a quick note to say what the format for the file list used by MAKESOL and MAKEFST is as follows:

u filename
c filename

The first letter is a command to say if the file should be compressed or not. (u = uncompressed, c = compressed).

The filename can be any file relative to the directory to tool is in. That is, if the tool is in the MechCommander Gold game directory, the the tool will have access to all files in this dir and all subdirs below it.

Do not use a ".\" in front of the filenames. If you wanted to access say, "test.abi" in ".\data\missions", then
the filename to use would be data\missions\test.abi

Note that this precludes having spaces in the filenames.

The list should have one command/filename pair per line, the command should be at the start of the line.

// re-build savegame\start0.pkk
for /L %n in (0, 1, 14) do solextract.exe savegame\start0.pkk %n file%n.txt
makesol.exe filelist.txt savegame\start0.pkk

for ii in {0..14}; do ./solextract.exe savegame/start0.pkk "$ii" "file$ii.txt"; done

./makesol.exe filelist.txt savegame/start0.pkk

for ii in {0..18}; do ./pakextract.exe savegame/savegame000.sav.00 "$ii" "savegame_$ii.txt"; done

./makesol.exe savegame_list.txt savegame/savegame000.sav



mmmmAmm


SUPPLEMENTAL

BRIEFING


QISFIRATi M gASUi RES

mmmL wmfmi

ySiR'S MAmUAl,





**** CLASSIFIED COMMUNIQUE****

Commander, as I stated in the vidcom, I am canceling your orders to return home. I know this
is very tough on morale— you and your men deserve some R&R after your distinguished service
in the attacks on the Clan Homeworlds. But I know that you understand the need to finish the
job: to eliminate this threat to the Inner Sphere once and for all. On a positive note, Battalion
has sent some new ’Mechs and weapons your way that should help bolster spirits some.

• Three new Inner Sphere ’Mechs and the specifications for three new Clan ’Mechs.

• Six new vehicles.

• Rve new weapons.

• The waypoint feature.

• The ammo conservation fire command.

• Difficulty level settings.

• Rre support mission hotkeys (for large and small artillery, sensor probes,
and camera drones).

In addition, Commander, keep your troops at combat readiness with Mission Editor. Create
new solo or multiplayer missions on either Port Arthur or the latest battlefield, Cermak.

Mission Editor includes:

• Terrain, overlay, and building palettes for maximum geographic and structural flexibility.

• Toolbars that allow you to manipulate your map in a variety of ways.

• Unit and vehicle palettes through which you can detail variants, orders, speed, and colors,
to name a few.

• Objectives tools through which you can mastermind a scenario and play it out.

Good Luck and Good Hunting,

Colonel Reese


© 1999 Microsoft Corp. Developed by Microsoft Corporation. Published by Hasbro Interactive, Inc. BattleTech, MechCommander, MechWarrior, BattleMech and 'Mech are
trademarks or registered trademarks of FASA Corporation and Microsoft Corporation. Microsoft, MS, Windows, and the Windows logo are either registered trademarks or
trademarks of Microsoft Corporation in the US and/or other countries. BattleTech material © 1998-1999 FASA Corporation. Used under license. MicroProse is atrademark of
Hasbro Interactive or its affiliates. All other trademarks are the property of their respective holders.


MECHCOMMANDER DESPERATE MEASURES 1



Please follow the instructions below to Install MechCommander Gold. References In the manual
to “MechCommander Desperate Measures” should be read to mean “MechCommander Gold.”


MECHCOMMANDER DESPERATE MEASURES
SYSTEM REQUIREMENTS

MechCommander Desperate Measures requires the following minimum system requirements:

• 133MHz Pentium

• Windows® 95 or Windows® 98

• 32MB RAM

• Super VGA graphics (640 x 480 x 256 colors)

• Quad-speed CD-ROM drive

• Hard drive (210MB free)

• DirectX-compatible sound card

The following system requirements are recommended:

• 166MHz Pentium

• 64MB RAM

• 8x-speed CD-ROM drive

• Hard drive (620MB free)

The following system requirements are required for multiplayer:

• Null-modem serial cable; or

• Windows-compatible 28.8kps modem or faster; or

• Local area network using IPX or TCP/IP; or

• Internet play requires a true TCP/IP connection


2 MECHCOMMANDER DESPERATE MEASURES


INSTALLING MECHCOMMANDER DESPERATE MEASURES

You do not need to have the original MechCommander game installed on your computer In
order to install MechCommander Desperate Measures.

To install MechCommander Desperate Measures

(T) Place the MechCommander Desperate Measures disc into your CD-ROM drive.

If AutoPlay Is enabled, click Install MechCommander Desperate Measures, and then follow
the instructions that appear on the screen.

-or-

@ If AutoPlay is disabled, double-click the My Computer icon on your desktop, double-click
the icon for your CD-ROM drive, and then double-click the MechCommander Desperate
Measures Icon. When the Setup screen appears, click Install MechCommander Desperate
Measures, and then follow the instructions that appear on the screen.

When asked which files you would like to install, be sure to check the box for “Install Required
RIes.” If you wish to create your own missions, check the box for “Install Mission Editor.”

STARTING MECHCOMMANDER DESPERATE MEASURES

To start a MechCommander Desperate Measures campaign

(T) If the MechCommander Desperate Measures disc is already in your CD-ROM drive,

click Start, point to Programs, point to MicroProse, point to MechCommander Desperate
Measures, and then click MechCommander Desperate Measures.

You can skip the opening cinematics by pressing ESC.

@ On the main menu, click Expansion Campaign.

Notes

• If you are playing a multiplayer mission, all MechCommander participants must use the same
software, either the original MechCommander or MechCommander Desperate Measures.

• You can play a number of precreated missions or missions created by your friends and con-
verted by you by choosing the Solo Missions and Multiplayer commands on the main menu.

To set the difficulty level

(T) On the MechCommander main menu, click Preferences.

@ Under Difficulty, click Easy, Regular, or Hard.

At the Easy level, your units’ hit and damage points are significantly increased.


MECHCOMMANDER DESPERATE MEASURES





THE MISSION EDITOR


The Mission Editor iets you design your own MechCommander missions. Piece buiidings,
set mission objectives, iandscape the terrain— you controi everything. After you're finished
creating your mission, share missions with friends or piay theirs.

INSTALLING THE MISSION EDITOR

if you did not instaii the Mission Editor when you instaiied the game, you wiii need to instaii
the Mission Editor manuaiiy.

(T) insert the MechCommander Desperate Measures disc into your CD-ROM drive.

@ Open Windows Expiorer and ciick the icon for your CD-ROM drive (usuaiiy D:).

@ Doubie-ciick the Mcedsetp foider.

(4) Doubie-ciick the Disk1 foider.

@ Doubie-ciick the Setup.exe fiie.

@ Foiiow the instructions onscreen to instaii the Mission Editor.


STARTING THE MISSION EDITOR

To start the Mission Editor, if the MechCommander Desperate Measures disc is aiready in your
CD-ROM drive, ciick Start, point to Programs, point to MicroProse, point to MechCommander
Desperate Measures, and then ciick Mission Editor.



4 MECHCOMMANDER DESPERATE MEASURES


CREATING A NEW MISSION

When creating a mission, keep the foiiowing in mind

• Make the objectives fun and create multiple ways to achieve each objective

• Compartmentalize battles so they don’t run into each other

• Create terrain that assists and challenges the commander, such as mountains, cliffs,
bridges, etc.

• Create choke points (geography that constrains movement) for tactical maneuvers such as
ambushes or blowing up a bridge

• In a multiplayer game, provide only just enough resources for one team

To create a new mission

(j} Choose either Multiplayer Mission Editor or Solo Mission Editor at the first dialog box.

@ Select New Mission at the next dialog box.

@ Select a locale (Port Arthur or Cermak) and Terrain at the next dialog box. Then use the
slider bars to specify Water, Forest and Hill Coverage. Note that water coverage is mutually
exclusive with forest and hill coverage. Click the OK button to continue.

( 4 ) After the Mission Editor loads, apply your terrains, overlays and buildings. If you want to
place walls, runways, etc. where they normally cannot go, use the Force palette to force
them onto the map.

From the Units palette, select the classes,
teams and variants for the computer-
controlled units. You have a total of 45
’Mechs and vehicles to allocate between
Allied and Enemy teams.

To make changes to a unit’s settings,
double-click that unit.

To set mission objectives, select Objectives
from the Mission menu. If you are creating
a multiplayer mission, set objectives for
both Team 1 and then Team 2.

To set mission parametres such as resource points and drop weight, select Settings from
the Mission menu. Type in a briefing for the mission by clicking the Player Briefing button.

If you are creating a multiplayer mission, select Settings and create Player Briefings for both
Team 1 and Team 2.



MECHCOMMANDER DESPERATE MEASURES 5


@ To place at least one Drop Zone for your units, select Drop Zones from the Mission menu.

If you are creating a multiplayer mission, place three Drop Zones each for Team 1 and Team 2.

@ To save your mission, select Save from the Rle menu and type a name for your mission no
longer than eight characters.

For more information about how to use the Mission Editor, select Help Topics from the Help
menu. The Help topics include design tips, keyboard shortcuts, troubleshooting tips and
explanations of error messages. You can also right-click on an object (such as a unit)
and then select Help from the pop-up menu.

Creating a Map

You can customize the terrain for your mission. The Tactical Map gives you an overall view of
the mission map. Select Tactical Map from the View menu. Click anywhere on the Tactical
Map to zoom to that spot on the regular map. To view the gridlines on the map, select
Gridlines from the View menu. To zoom the map in, select Zoom In from the View menu or
press the PLUS key. To zoom out, select Zoom Out or press MINUS.

The Map Features Palette lets you add various elements to the map:
Terrains, Overlays, Force, Buildings and Units. Select Map Features
palette from the View menu. Click on a palette tab, click on an item on
that palette and then click on the map to place that palette item. If a map
tile is already selected, clicking a palette item will place that object on the
selected map tile. Drag an element along the map to create a path of that
item. The Terrains palette offers different terrain types such as Grass and
Dirt. The Overlays palette adds elements such as Forest and Roads. Use
the Force palette to break the normal map rules. Choose from the various
buildings from the Buildings palette. Select ’Mechs and vehicles from the
Units palette. For more information about the palettes, see the Help file.


The Main Toolbar and Tools Menu

Use the Main Toolbar and Tools menu to make changes to the map.






p




_t_

nir



1


1=



• Select selects a single map tile. Click a grid on the map and then either click a toolbar
button or a palette tile.

• Select Area selects a map area for large-scale changes such as Erase or applying terrain.
The selected area must include at least one vertex and three tiles on each side of the vertex.




6 MECHCOMMANDER DESPERATE MEASURES


• Drag View moves the map as you drag the cursor.

• Zoom In magnifies the map.

• Zoom Out reduces the map view.

• Spray Trees randomly places assorted trees in a 9-tile area.

• Erase deletes objects on the map. It does not delete map objects that were placed from
the Terrains palette. The cursor will look like an eraser when placed over an object it can
erase. If the object cannot be erased, the eraser will be all red.

• Rotate changes the selected object’s orientation. Click the object to cycle through the rotation.

• Raise Vertex raises the height of the selected vertex for two cells along its axis. Each
click raises the vertex and the transition area by one level. Use Raise Vertex to create
mountain ranges.

• Lower Vertex lowers the height of the selected vertex for two cells along its axis. Use
Lower Vertex to create troughs. You can lower the slope to sea level (0 height) and it will
be filled with water.

• Make Hilly randomly changes the slope of the selected area.

• Flatten flattens the slope of the selected level by one level in height.

• Link Buildings connects structures so that a control structure, such as a gate control,
commands all of its linked structures. For example, if a gate control is linked to a series of
gates, an enemy that captures the gate control gains commands of all the gates linked to
that gate control.


Make sure that controlling structures, such as a gate control, are set to the correct align-
ment (Allied, Enemy or Neutral) in order for the controlled structures, such as gates, to
react correctly to units.

• Unlink Buildings breaks a selected link between a control and controlled structure.

• Damage damages overlays and structures for a more realistic, war-torn environment.
Damaging a turret, for example, renders it inoperative.


Controlling Structure

Main or Auxiliary Power
Turret Control
Sensor Control
Gate Control


Controlled Structure

Turret Control
Turret
Sensor
Gate


MECHCOMMANDER DESPERATE MEASURES 7


• Repair fixes damaged overlays and structures.

The Standard Toolbar



• Display Grid either shows or hides the gridlines on the map.

• Undo reverses the last command you made or deletes the last item you placed on the
map. Click Undo repeatedly to undo to the point of the file’s last save.

• Redo reverses the Undo command.

• Set Height adjusts the height of a selected map area. Rrst, select an area on the map
by clicking the Select Area button on the toolbar. Then click the Set Height button, type
in a height and click the OK button. Click the Apply button to look at the height before
accepting the change.

Unit Settings

The Unit Settings dialog box is only available for solo missions. To set a unit's settings,

double-click a unit on the map and the dialog box below will appear.

Allied or Enemy selects which side the unit belongs to.

Variant determines which variant of the ’Mech it is.

Color specifies the color scheme for the unit.

Pilot determines which pilot is assigned to the unit.

Orders sets the specific orders for the unit. An explanation
of the order appears to the right when you select an order
from the drop-down list.

• Engage Radius sets the active radius for the unit. Short is 150 metres (12.5 tiles).
Medium is 350 metres (28 tiles) and Long is 650 metres (52 tiles).

• Tactic sets the tactic for the unit. For more information about each type of tactic, see
Unit settings dialog box In the Help file.



• Move Speed sets the movement rate for the unit: Walk or Run.



8 MECHCOMMANDER DESPERATE MEASURES


Mission Objectives

In order to successfully complete the mission you design, piayers must compiete the objectives
you set. Seiect Objectives from the Mission menu to set up to four primary objectives, each
with up to three parametres.



(T) Seiect an objective, such as Move to Area.

@ In the Description box, type an expianation of the task for the piayer (such as “Move to
compound centre”).

@ If the objective must be completed for the mission to be successful, check the Primary box.

(J) If you want a marker to be displayed for this objective in the Campaign Data box and the
tactical map, check the Marker box.

If the primary objective prior to one must be completed before this objective is started,
check the Complete Previous box.

@ To select a particular objective, click the Selection icon. The dialog box will disappear and
your icon will change to cross hairs. The cross hairs will turn white to indicate a valid
target. Click on the desired objective on the map.

To delete a mission objective, select it and press ESC.


MECHCOMMANDER DESPERATE MEASURES 9


Mission Settings


Select Settings from the



Mission menu to adjust the following settings for your mission:

• Smaii Artiliery is the maximum number of small artillery per
mission (5 is the maximum).

• Sensor Probes is the maximum number of sensor probes per
mission (5 is the maximum).


• Time Limit sets the time limit to complete a mission
(3 minutes is the minimum and zero means no limit).


• Camera Drones is the maximum number of camera drones available per solo mission
(5 is the maximum).

• Large Artillery is the maximum number of large artillery available per mission
(5 is the maximum).

• Resource Points set the resource points given to the player at the start of the mission
(100000 is the default and 9999999 is the maximum).

• Drop Weight sets the maximum drop weight, in pounds, for a mission (990 is the default,
1200 is the maximum and 5 is the minimum).

• Technoiogy Base determines which side you are playing during a solo mission: Inner
Sphere (the default) or Clan.


Player Briefing

Click on the Player Briefing button in the Settings dialog box to write the text for your own
mission briefings.

• Mission Titie provides a brief title for the mission.

• Objectives lists the objectives in the order in which they
must be completed.

• Description describes the overall mission.

• Tactical Warnings provides intelligence reports and other
critical information.

• Tactical Notices provides information about unit and
weapon strengths.





10 MECHCOMMANDER DESPERATE MEASURES


Drop Zones

Select Drop Zones from the Mission menu to dispiay the Drop Zones
cursor. Then ciick on the map to set ianding points for each piayer’s
or team’s forces. Solo missions must contain at ieast one Drop Zone.
Muitiplayer missions must contain three Drop Zones per team. A solo
mission or Team 1 Drop Zone is indicated by a green and yellow icon.
A Team 2 Drop Zone is indicated by an orange and red icon.

Your Mission File

Use the File menu to create, open, save and compress your mission fiie.

• New creates a new soio or muitiplayer mission fiie.

• Open loads a previously saved mission or map.

• Save saves your current map, inciuding its mission data. The file is saved to your
C:\Program Rles\MicroProse\MCX\Data\Terrain folder.

• Save As lets you save your map and mission data under a new fiie name.

• Write Distribution Fiie (DPK) compresses an aiready saved map and mission data into a
DPK file, which you can then share with other players. Missions you create with the
Mission Editor are dispiayed in the Select Mission list. Missions created by other people or
on other computers must be converted from a DPK file to be displayed in the Select
Mission list. For information on how to convert a DPK file, refer to Using DPK files to
Share Missions in the Help file.

• Save Map Only saves just the map without any mission data.

• Exit exits the Mission Editor.





MECHCOMMANDER DESPERATE MEASURES 11


NEW >MECHS


ComStar’s intelligence has done its work and obtained the specs for three new Clan ’Mechs.
BattleMech manufacturing concerns throughout the Inner Sphere have independently
responded with three new Inner Sphere ’Mechs. Get to know these specs: You’ll need them.

Payload capacity is the total tonnage available for components (including weaponry). Reminder:
Sensors, active probes, and electronic measurement systems are limited one per 'Mech.

Class encapsulates ’Mech tonnage, maneuverability, armour, and standard armaments to
describe the combat role of the ’Mech: Light, Medium (Med), Heavy (Hvy), and Assault.

Structure indicates how much damage a ’Mech can withstand: Light, Moderate (Mod), Heavy
(Hvy), and Very Heavy (V Hvy).

““TACTICAL NOTICE****

During a mission, to reallocate units and vehicles among Force Groups, select the units, press
CTRL+F1, CTRL+F2, CTRL+F3, or CTRL+F4 (where F<n> indicates the Force Group number to
which you want to assign the selected units), and then click a unit to make it the leader.


Inner Sphere 'Mechs

Stiletto
Bush w acker


Clan 'Mechs

Shadow Cat
Nova Cat


Mauler


Turkina



12 MECHCOMMANDER DESPERATE MEASU RES


STILEHO


INNER SPHERE
w LIGHT
35 TONS





VARIANT


COST


WEIGHT


CLASS


SPEED


ARMOUR


STRUCT


JUMP


Basic Armament


ARMOUR


36m/sec


1 Streak SRM Pack,

3 LRM Racks,

1 Sensor— Intermediate


WEAPON


1 Large Pulse Laser,

2 LRM Racks,

1 Sensor— Intermediate


JUMP


26780


35 Tons


36m/sec


Mod


1 Streak SRM Pack,

3 LRM Racks,

1 Sensor— Intermediate


SHADOW CAT NOVA CAT


The fastest ’Mech in the Inner Sphere
arsenal carries an Intermediate Sensor
for advance warning of opponents near
range. Its speed gives it unparalleled
ability to evade combat with sufficient
weaponry to extract itself from a skirmish
while damaging opponents. A good unit
for scouting or recon missions, the
Stiletto may be the Inner Sphere’s answer
to the Clan’s Uller, although its reliance on
ammo-based weapon systems make it
susceptible to resupply failures.

Version Manufacturer:

Coventry Metal Works
Armour Source: Unknown
Communication System: Unknown
Targeting and Tracking System: Unknown


? STiLETTO BUSHWACKER


MAULER


TURKINA





MECHCOMMANDER DESPERATE MEASURES 13




VARIANT


COST


WEIGHT


CLASS


SPEED


ARMOUR


STRUCT


JUMP


Basic Armament


ARMOUR


24m/sec


Short


1 Laser, 1 SRM Pack,

1 LB-X Autocannon, 2 LRM F
1 Sensor— Basic


WEAPON


2 Lasers, 1 SRM Pack,

1 LB-X Autocannon, 2 LRM Racks,
1 Sensor— Basic


JUMP


35950


55 Tons


24m/sec


Mod


Short


1 Laser, 1 SRM Pack,

1 LB-X Autocannon, 2 LRM Racks,
1 Sensor— Basic


STILETTO ? BUSHWACKER MAULER


Built with flexibility in mind, the
Bushwacker's default weapons
mix is quite lethal against Inner
Sphere opponents, although com
Clan weapon systems out-range the
Bushwacker by up to 50%. A fast,
maneuverable ’Mech with a versatile
design, use Bushwackers with
Autocannons to attack Clan units at
close range through difficult terrain.

Version Manufacturer:

TharHes Industries
Armour Source: Unknown
Communication System:

TharHes Euterpe HM-14
Targeting and Tracking System:
TharHes Ares-8a




14 MECHCOMMANDER DESPERATE MEASURES


MAULER


INNER SPHERE
VERY HEAVY
I ^ 90 TONS



PAYLOAD CAPACITY


VARIANT A/ J:
VARIANT W:



VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

Basic Armament

ARMOUR

60740

90 Tons

Assault

ISm/sec

Hvy

VHvy

Short

1 Large Laser, 2 LRM Racks,

2 Light LB-X Autocannons, 2 Light
Gauss Rfles, 1 Sensor— Basic

WEAPON

66170

90 Tons

Assault

ISnVsec

Mod

VHvy

Short

2 Heavy LB-X Autocannons, 1 Large Laser,

1 Large ER Laser, 1 Light LB-X Autocannon,

2 Light Gauss Rfles, 1 Sensor— Basic

JUMP

65220

90 Tons

Assault

ISm/sec

Mod

VHvy

Short

1 Large Laser, 2 LRM Racks,

2 Light LB-X Autocannons, 2 Light
Gauss Rfles, 1 Sensor— Basic




An assault-class ’Mech produced under
high security by the Draconis Combine,
the Mauler \s proportionally smaller than
the Atlas, its 100-ton cousin. The Mauler
delivers a high volume of armour-shredding
firepower at a long range, due to the
LB-X Autocannons found in each variant.

Version Manufacturer:

Luthien Armour Works

Armour Source: New Samarkand Royal

Communication System:

Sipher Security Plus
Targeting and Tracking System:

Matabushi Sentinel







STILETTO BUSHWACKER ? MAULER SHADOW CAT


NOVA CAT


TURKINA











MECHCOMMANDER DESPERATE MEASURES 15






Inner Sphere 'Mech Comparison Chart


BattleMech

Weight

(tons)

Speed

(m/sec)

Commando

25

27

Firestarter

30

27

Raven

35

27

Stiletto

35

36

Hollander II

45

24

Centurion

55

18

Bushw acker

55

24

Catapult

65

18

Jagermech

70

18

Awesome

80

18

Mauler

90

15

Atlas

100

15


STILEHO

VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

ARMOUR

22420

35 Tons

Light

36m/sec

Mod

Mod

Long

WEAPON

22070

35 Tons

Light

36m/sec

Light

Mod

Long

JUMP

26780

35 Tons

Light

36m/sec

Light

Mod

Long


BUSHWACKER

VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

ARMOUR

34680

55 Tons

Med

24m/sec

Mod

Hvy

Short

WEAPON

33260

55 Tons

Med

24m/sec

Mod

Hvy

Short

JUMP

35950

55 Tons

Med

24m/sec

Mod

Hvy

Short


MAULER

VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

ARMOUR

60740

90 Tons

Assault

15m/sec

Hvy

VHvy

Short

WEAPON

66170

90 Tons

Assault

15m/sec

Mod

VHvy

Short

JUMP

65220

90 Tons

Assault

15m/sec

Mod

VHvy

Short


16 MECHCOMMANDER DESPERATE MEASURES


SHADOW CAT





PAYLOAD CAPACITY


VARIANT A/ J:
VARIANT W:


29.0

36.5



VARIANT


COST


WEIGHT


CLASS


SPEED


ARMOUR


STRUCT


JUMP


Basic Armament


ARMOUR


27m/sec


2 Clan ER Lasers,

2 Clan Large Pulse Lasers,
1 Clan Sensor— Basic


WEAPON


1 Clan ER Laser,

3 Clan Large Pulse Lasers,
1 Clan Sensor— Basic




T<r


JUMP


40870


45 Tons


Med


2 Clan ER Lasers,

2 Clan Large Pulse Lasers,
1 Clan Sensor— Basic


MAULER


? SHADOW CAT


Technically a heavy scout, the Shadow Cat
is well armed and armoured— ideal for
hazardous recon missions teamed with
other light- or medium-class ’Mechs as
part of a command Star. The Clan Nova
Cat’s apparent response to the Wolf Clan’s
ris ’Mech, it accelerates to top speed
at an astonishing rate and was used to
overwhelm the forward observation posts
at Luthien as they relayed reports of
oncoming enemy. Its default configuration
leaves it vulnerable to indirect fire.

Version Manufacturer: Unknown
Armour Source: Unknown
Communication System: Unknown
Targeting and Tracking System: Unknown


NOVA CAT


TURKINA


MECHCOMMANDER DESPERATE MEASURES 17


f . NOVA CAT




VARIANT


COST


WEIGHT


CLASS


SPEED


ARMOUR


STRUCT


JUMP


Basic Armament


ARMOUR


1 Clan Heavy Flamer, 3 Clan Pulse
Hvy 21m/sec Hvy Hvy Short Lasers, 2 Clan Heavy LB-X

Autocannons, 1 Clan Sensor— Basic


WEAPON


1 Clan Pulse Laser, 4 Clan Streak
SRM Packs, 2 Clan Heavy LB-X


JUMP


66210


70 Tons


21 m/sec


Mod


Short


1 Clan Heavy Flamer, 3 Clan Pulse Lasers,

2 Clan Heavy LB-X Autocannons,

1 Clan Sensor— Basic


STILETTO BUSHWACKER MAULER


Version Manufacturer:

Barcella Alpha, Irece Alpha
Armour Source: Unknown
Communication System:

JNE Integrated

Targeting and Tracking System:

Build 2 CAT TTS


A short-range killing machine, the Nova
Caf was designed to butcher anything that
gets too close. In 3059, the Nova Caf first
saw battle against the Smoke Jaguars as
part of Operation Bulldog. Here the Nova
Caf proved its awesome long-range fire-
power, but during the Operation several
Nova Cats were captured by the Smoke
Jaguar Clan. Periphery sources suggest
that Nova Caf variations have been added
to Clan arsenals.


SHADOW CAT ? NOVA CAT


TURKINA



18 MECHCOMMANDER DESPERATE MEASURES


TURKINA



VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

Basic Armament

ARMOUR

84110

95 Tons

Assault

15m/sec

VHvy

VHvy

Short

1 Clan Pulse Laser, 2 Clan LB-X Autocannons,

2 Clan Lg ER Lasers, 2 Clan LR Missile Packs,
2 Clan Lt LB-X ACs, 1 Clan Sensor-Basic

WEAPON

104710

95 Tons

Assault

15nVsec

Hvy

VHvy

Short

1 Clan Pulse Laser, 2 Clan LB-X Autocannons,

2 Clan ER PCCs, 2 Clan LR Missile Packs,

2 Clan Lt LB-X ACs, 1 Clan Sensor-Basic

JUMP

90190

95 Tons

Assault

15nVsec

Hvy

VHvy

Short

1 Clan Pulse Laser, 2 Clan LB-X Autocannons,

2 Clan Lg ER Lasers, 2 Clan LR Missile Packs,
2 Clan Lt LB-X ACs, 1 Clan Sensor-Basic



BUSHWACKER MAULER SHADOW CAT


The Clan’s TZ/r/r™ assault-class ’Mech
carries crippling long-range firepower
and can smash anything that gets too
close. The Turkin^s flexible weapon system
packs exactly twice the punch packed by
the primary configuration of the Thor, but
it accomplishes this with only 40% more
weight. The increased use of energy
weapons in the Turkinais in direct
response to the Clan’s defeats on Tukayyid,
where ammo resupply efforts failed.

Version Manufacturer: Unknown
Armour Source: Unknown
Communication System: Unknown
Targeting and Tracking System: Unknown







MECHCOMMANDER DESPERATE MEASURES 19






Clan 'Mech Comparison Chart


BattleMech

Weight

(tons)

Speed

(m/sec)

Uller

30

27

Cougar

35

27

Shadow Cat

45

27

Hunchback IIC

50

18

Vulture

60

24

Loki

65

24

Thor

70

24

Nova Cat

70

21

Mad Cat

75

24

Masakari

85

18

Turkina

95

15





SHADOW CAT

VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

ARMOUR

39650

45 Tons

Med

27m/sec

Mod

Mod

Med

WEAPON

42000

45 Tons

Med

27m/sec

Light

Mod

Med

JUMP

40870

45 Tons

Med

27m/sec

Light

Mod

Med


NOVA CAT

VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

ARMOUR

61590

70 Tons

Hv

y

21 m/sec

Hvy

Hvy

Short

WEAPON

57490

70 Tons

Hv

y

21 m/sec

Mod

Hvy

Short

JUMP

66210

70 Tons

Hv

y

21 m/sec

Mod

Hvy

Short


TURKINA

VARIANT

COST

WEIGHT

CLASS

SPEED

ARMOUR

STRUCT

JUMP

ARMOUR

84110

95 Tons

Assault

15m/sec

VHvy

VHvy

Short

WEAPON

104710

95 Tons

Assault

15m/sec

Hvy

VHvy

Short

JUMP

90190

95 Tons

Assault

15m/sec

Hvy

VHvy

Short


20 MECHCOMMANDER DESPERATE MEASURES



As I mentioned earlier, we have new weapons for your forces. FedCom engineers continue to
refine weaponry to replace aging Inner Sphere weapon systems In all three armament types:
ballistic, energy, and missile. Reid modification kits have been issued and the new weapons
are available from regimental inventory.

Ammo conservation mode software has been retrofitted in all deployed 'Mechs. For informa-
tion on mode use, review the Tactics technical information.


HEAVY THUNDERBOLT


COST

Salvage

LOAD VAL

21

1 RECYCLE

6 sec (slow)

1 DAMAGE

12 (very heavy)

1 RANGE

Medium


This launcher fires one medium-range, ’Mech-crippling missile over
obstacles. It cannot arm itself at targets within 50 metres. It is not
available in the Battalion Inventory and must be obtained through
battlefield salvage. It carries limited ammo. (32 shots)


MECHCOMMANDER DESPERATE MEASURES 21




Light

Medium

Heavy

COST

3560

8480

12850

1 LOAD VAL

9.5

14.5

19.5

1 RECYCLE

1 .75 sec (v fast)

4 sec

6 sec

1 DAMAGE

0.5 (v light)

2

5

1 RANGE

Long

Medium

Short


The light version of the LB-X Autocannon fires at a faster rate
than the Light Autocannon. The heavy version fires a massive
short-range, shotgun-like round capable of striking multiple
armour sections simultaneously. All variations carry limited
ammo. (Light: 260 shots; Medium: 90; Heavy: 35)


CLAN LB-X AUTOCANNONS



Light

Medium

Heavy

COST

3560

8480

12850

1 LOAD VAL

8.5

13.5

17.5

1 RECYCLE

1.75 sec (vfast)

4 sec

6 sec

1 DAMAGE

0.5 (v light)

2

5

1 RANGE

Long

Medium

Short


(Light: 260 shots; Medium: 90; Heavy: 35)






22 MECHCOMMANDER DESPERATE MEASURES



COST

19570

LOAD VAL

13

1 RECYCLE

.075 sec (very fast)

1 DAMAGE

1.5 (light)

1 RANGE

Long


This rapid-firing energy weapon has the fastest recycle rate of any
component available and is capable of striking targets at long range.



COST

7110

LOAD VAL

13.5

1 RECYCLE

5 sec (slow)

1 DAMAGE

5 (heavy)

1 RANGE

Long


This new Inner Sphere design fires a smaller slug out to long range.
It carries limited ammo. (50 shots)



COST

33840

LOAD VAL

34

1 RECYCLE

7.5 sec (slow)

1 DAMAGE

8 (very heavy)

1 RANGE

Long


Long Tom shells deliver 8 points of damage to the target and an additional
8 points of damage to everything in its explosion radius. It carries limited
ammo. (25 shots)




MECHCOMMANDER DESPERATE MEASURES 23



NEW VEHICLES


Military research and development BattleMech advancements have yielded upgraded support
vehicles: five new combat vehicles and one new utility vehicle. Vehicle manufacturers have
readily adopted BattleMech power plant and ferro-fibrous armour improvements. Don’t
underestimate the effectiveness of vehicles at the front: The Battle of Tukayyid demonstrated
the cost effectiveness of fielding support vehicles in combination with ’Mechs.

Note: In the Expansion Campaign, vehicles are aligned with the Clan, but in the wargames you
can deploy vehicles aligned with your units.


CENTIPEDE SCOUT CAR



m




Originally planned as a highly maneuverable replace-
ment for the Inner Sphere’s Skulker, this fast and
heavily armed recon car is ideal for deep penetration
missions requiring more than a minimum level of
firepower. The Centipede is highly susceptible
to sustained fire.


COST

8580

WEIGHT

15 Tons

TYPE

Lt Scout

SPEED

21 m/sec

ARMOUR

Light

WEAP/COMP

1 Ig Laser

1 advanced Vehicle Sensor

1 guardian KM



This swift and agile tank carries a massive Gauss Rifle
capable of devastating most targets with one or two
shots and can use its speed to bring that weapon to
bear on weak rear ’Mech armour. Its design provides
long-range, medium-weight firepower. It should
not be underestimated.


COST

17250

. WEIGHT

45 Tons

TYPE

Med Tank

SPEED

21m/sec

ARMOUR

Light

WEAP/COMP

1 Gauss Rfle





24 MECHCOMMANDER DESPERATE MEASURES



MANTICORE HEAVY TANK


Rrst issued to the Lyran Royal Guard units, the Manticore
has seen combat throughout the Inner Sphere. It is an
impressive heavy tank, affording excellent armour protection
and effective, accurate firepower. Long regarded as a
powerful infantry weapon, the Manticore provides medium-
range armoured firepower with excellent fields of fire
from the missile packs’ location in the turret.


COST

13870

WEIGHT

60 Tons

TYPE

Hvy Tank

SPEED

ISm/sec

ARMOUR

Mod

WEAP/COMP


1 Particle Projector Cannon

1 Large Pulse Laser

2 SRM Packs



COST

12560

WEIGHT

70 Tons

TYPE

Hvy Tank

SPEED

ISm/sec

ARMOUR

Mod

WEAP/COMP

6 LRM Rocks


PILUM HEAVY TANK


This version of the Pilum Heavy Tank trades some of its
firepower for a larger power plant, making it faster than
any vehicle in its weight class. Its impressive flanking
speed of 65kph makes it the fastest of the heavy tanks,
yet it is still able to take significant damage and
maneuver. Its firepower is limited, however.


COST

47450

WEIGHT

95 Tons

TYPE

Assault

SPEED

12m/sec

ARMOUR

Hvy

WEAP/COMP

3 Gauss Rfis


ALACORN MKVIl HEAVY TANK




A Star League-era design first deployed in the Periphery,
General Aleksandr Kerensky took hundreds of Alacorns with
him at the time of his Exodus. The Alacorn packs reasonable
speed, superior armour, and a terrifying punch into one
sleek package with three Gauss Rifles mounted on a
rotary turret that provides a full 360-degree firing arc.



MECHCOMMANDER DESPERATE MEASURES 25






AMMO TRUCK






The Ammo Truck is a small, reasonably fast, vulnerable
vehicle capable of replacing a ’Mech’s ammunition on the
battlefield. Deploy it as you would the Refit Truck; move it
near a ’Mech until the Repair Icon (a wrench) appears,
and then click that ’Mech to reload its ammunition. Clever
MechCommanders have used its combustible payload as
an offensive weapon. If the vehicle is destroyed, the

ordnance it carries will explode, damaging everything
within the blast radius.


COST

1500

WEIGHT

10 Tons

TYPE

Light

SPEED

ISm/sec

ARMOUR

Light

WEAP/COMP

None



26 MECHCOMMANDER DESPERATE MEASURES



Lastly, Commander, you have no doubt seen the media’s recent focus on the evolution of
modern military tactics. As hinted in the reports. Inner Sphere military establishments
developed strategies that enable frontline commanders, such as yourself, to more effectively
deploy forces and resources under their command.

WAYPOl NTS

Waypoints give a commander greater control over his units’ movement by setting a specific
series of points for them to automatically follow, thus freeing up the commander’s attention for
other units. There are four different types of waypoints— walk, run, jump, and minelayer— and
you can place a total of 16 waypoints in any order.

Units traverse waypoints by the shortest possible move path. For example, if cliffs are directly
between two waypoints, the units must move around the cliffs. Therefore, by placing more
waypoints, you gain more control of the move path. For example, you may have a jump-capable
unit walk to the first waypoint, run to the second, jump to the third, and run to the fourth.

To create waypoints

(T) To create a wa//r waypoint, press and hold CTRL, or F9, while you click the waypoint location
on the main screen. <2

-or-

To create a run waypoint, press and hold CTRL+SPACEBAR, or F10, while you click the
waypoint location on the main screen. <3

-or-

To create a jump waypoint, press and hold CTRL+J, or F1 1 , while you click the waypoint
location on the main screen. '5^


-or-


MECHCOMMANDER DESPERATE MEASURES 27


To create a minelayer waypoint (mines are laid as the vehicle follows the move path), press
and hold CTRL+F while you click the waypoint location on the main screen.



@ Repeat step 1 as necessary for each waypoint
you want.


Notes


• You can assign a move path to any number of
units at one time, using the standard selection
methods. If a group of units is selected,
lead unit will move to the waypoints first


• You can view a unit's move path lines by
pressing and holding CTRL.

• You can add waypoints to an existing move
path at any time. The new waypoints are ad
to the end of the orders queue.

• You can clear a unit's move path by selecting
that unit and pressing BACKSPACE.

• Waypoints may be placed in unrevealed terrain;
they appear above the black background, similar to sensor traces.

• You can place waypoint markers while the mission is paused. Once a waypoint marker is
laid, it cannot be moved. Units will begin following their move paths when the mission is
resumed. This is helpful in organizing simultaneous movement.


• Once a waypoint marker is laid, it cannot be moved.


• While CTRL is pressed, you cannot assign targets or capture a unit.


• If a unit following a move path receives a new order, movement, or attack, the move path
and its waypoints are cancelled.

• If attacked while executing a walk waypoint, the units behave identically to units walking in
MechCommander. They will stray off their move path until the combat is resolved.

• If a unit cannot reach a given waypoint, it will behave identically to a unit that cannot
handle a move order.

• To set a move path through burned forest, place waypoints just before the burned forest,
just after the burned forest, and then toward your final destination.

• You may play the original MechCommander campaign using waypoints.


28 MECHCOMMANDER DESPERATE MEASURES


AMMO CONSERVATION MODE

To give the commander greater control over his resources in combat, he can order units to fire
energy weapons only, conserving precious ammunition until it is truly needed.

Energy weapons are those with an unlimited supply of shots— for example, Pulse Lasers,
Heavy Flamers, and Particle Projector Cannons. Ammo weapons are those that fire a limited
supply of shots or salvos— for example. Gauss Rifles, Autocannons, and Missile Packs.

To order ammo conservation mode

Hold down A and then, on the main screen, click the enemy you want to hit with energy
weapons only. The cross hairs will appear orange.

Notes

• To clear all orders, including ammo conservation mode, press BACKSPACE.

• If a unit in ammo conservation mode receives a new attack order, ammo conservation
mode is cancelled and the unit will fire all of its weapons.

• If a unit has only ammo weapons and is given the ammo conservation mode order, that
unit will not fire (as if it were out of weapons).

• A commander orders a group of units to use ammo conservation mode in the same
manner he would make any other order. If one of the units in the group has only ammo
weapons, then that unit will not fire (as if it were out of weapons).

• You may play the original MechCommander campaign using ammo conservation mode.

DIFFICULTY LEVELS

MechCommander Desperate Measures offers three levels of gameplay: easy, regular, and hard.
These levels can also be used to play the original MechCommander missions.

To set the difficulty level

(T) On the MechCommander Desperate Measures main menu, click Preferences.

® Under Difficulty, click Easy, Regular, or Hard.

Note: You can change level difficulty before you start a mission or between missions. If a
mission proves to be too challenging, you can lower the difficulty setting, win the mission,
and then return to the former difficulty setting for the next mission.




MECHCOMMANDER DESPERATE MEASURES 29






KEYBOARD COMMANDS


Combat/ Tactical


To

Press

Assault from current location

C+Left mouse button

Assault from long range

L+Left mouse button

Assault from medium range

M+Left mouse button

Assault from short range

S+Left mouse button

Attack head

8+Left mouse button

Attack left torso

7+Left mouse button

Attack right torso

9+Left mouse button

Attack centre torso

5+Left mouse button

Attack left arm

4+Left mouse button

Attack right arm

6+Left mouse button

Attack left leg

1+Left mouse button

Attack right leg

3+Left mouse button

Order ammo conservation mode

A+Left mouse button


Keyboard Commands continues . . .


30 MECHCOMMANDER DESPERATE MEASURES


Fire Support

Rre support gives the commander greater control over his combat resources. Launch small
artillery strikes, large artillery strikes, sensor probes, and camera drones by pressing a key on
the keyboard (not the numeric keypad) and clicking the mouse on the target— no wasting time
moving the cursor to the multifunctional display (MFD).

When a fire support hotkey is depressed, the corresponding button is highlighted on the MFD
per the RUN, JUMP, and GUARD hotkeys in original MechCommander. The fire support cursor
may be moved until it is deployed by clicking the left mouse button.

To Press


Drop small artillery strike at cursor
Drop large artillery strike at cursor
Drop sensor probe at cursor
Drop camera drone at cursor


1+Left mouse button on target
2+Left mouse button on target
3+Left mouse button on target
4+Left mouse button on target


Note; You must press a number key each time you want to drop artillery and so forth. For
example, to drop three small artillery strikes, you must press 1 and click the left mouse button
once on each of the targets.


Orders


To Press


Hold fire/stop

BACKSPACE


Guard

G+Left mouse click on target


Capture

Left mouse click context-sensitive cursor on

item

Repair/refit

Left mouse click context-sensitive cursor on

item

Lay mines

F+Left mouse button


Power up

PAGE UP


Power down

PAGE DOWN


Eject

HOME+Left mouse button





MECHCOMMANDER DESPERATE MEASURES 31






Unit Control


To

Press

Reassign Force Groups

CTRL+F1 through F4

Select all units in battlefield view

E


Deselect all units

Right mouse button on battlefield view

Get information on unit

l+Left mouse button

Moving Units


To

Press

Move half-power

Left mouse button

Move full-power

SPACEBAR+Left mouse button

Jump (jump-enabled ’Mechs only) J+Left mouse button


Create walk waypoint

CTRL or F9

Create run waypoint

CTRL+SPACEBAR or F10

Create jump waypoint

CTRL+J or F1 1

Create minelayer waypoint

CTRL+F

Battlefield View


The commands in this section can be triggered by pressing the appropriate key

on either the keyboard or the

numeric keypad.

To

Press

Zoom view in

PLUS SIGN

Zoom view out

MINUS SIGN

Scroll down

DOWN ARROW

Scroll up

UP ARROW

Scroll left

LEFT ARROW

Scroll right

RIGHT ARROW


32 MECHCOMMANDER DESPERATE MEASURES


Multifunctional Display (MFD)


To Press

Open/close M FD ALT

Open MFD (Briefing Active) ALT+B

Open MFD (Information/ ALT+D

Briefing Active)

Open MFD (Map Active) ALT+M

Open MFD (Salvage Active) ALT+S

Open MFD (Chat Active) ALT+C

(multipiayer missions oniy)


Open/close MFD (Command Paiette) TAB

Tactical Map


To Press


Scroli down

CTRL+DOWN ARROW

Scroli up

CTRL+UP ARROW

Scroli ieft

CTRL+LEFT ARROW

Scroli right

CTRL+RIGHT ARROW

Zoom in

CTRL+PLUS SIGN

Zoom out

CTRL+MINUS SIGN

System Commands


To

Press

Pause game

ESC or PAUSE

Enter chat mode (muitiplayer)

ENTER


MECHCOMMANDER DESPERATE MEASURES 33



FASA Interactive/ Microsoft


Producer

Mitch Gitelman

Lead Developer


John Whitmore
TJ Wagner
Jordan Weisman


Frank Savage

Lead Designer

Mike Lee

Lead Artist

Tom Buriington

Product Planner

Jon Kimmich

Technical Art Director

Jamie Marshall

Composer/Sound Designer

Duane Decker

Programming

Glenn Doren
Heidi Gaertner
Jon Marcus
Frank Savage

Design

Mitch Giteiman
Mike Lee
Denny Thorley


Mission Design

David Abzug
Mike Lee
Rob Nicholls
Joe Sislow

Muitipiayer Mission Design

David Abzug
Derek Carroll
Terry Cokenour
John Howard
“Evil” John Moreland

Art

Vic Bonilla
Tom Burlington
Andrew Hura
Todd Labonte
Jamie Marshall
Larry Mast
Duane Molitor
Allen Nunis
Charles Oines
Steve Scott
Lex Story


Quality Assurance

Michael Horn
Michel Lowrance
Mark McNulty
Todd Squire
Harris Thurmond
TJ Wagner

Documentation

Vic Bonilla
Tom Burlington
Mark Duncan
Dana Fos
Mitch Gitelman
Chris Lassen
Daj Oberg
Heinz Schuller
Lex Story
Jordan Weisman

Special thanks:

To Mort Weisman, Bryan
NystuI, and the entire staff
of FASA Corporation. Also
to PaleRider, Mishima,
and the Hardcorps Online
who advised, encouraged,
and flamed


34 MECHCOMMANDER DESPERATE MEASURES


CUSTOMER SERVICES

If you have problems and require assistance you can contact our Customer Services:

Phone: +44 (0) 1454 893900

Hours of operation; 0900-1730 GMT/BST, Monday to Friday

Fax: +44 (0) 1454 894296

Note: Phoning this number costs the same as a standard rate call no matter where you call from in
the UK. If you do telephone the Technical Support line, if possible please be sitting in-front of your
computer and have a pen and paper at the ready. Before contacting our Technical Support Hotline,
piease try to have the following information ready so that we may help you more efficiently:

The name of the game, the make and model of your computer, the processor and it's speed,
peripherials, graphics card with it's driver date and version, sound card with it's driver date and
version, which version of Windows you are using, total memory installed, exact error message (if
any) version of DirectX installed, type of CD-ROM drive, total system resources free before running
the program and finally the name of any programs running in the background.

EMAIL

Alternatively you can email our Technical Support operators:

uksupport@hiuk.com

WEBSITE

http://www. hasbrointeractive.com

To ensure a prompt reply please summarise your issues as concisely as you can, giving
details, as above, of the game, the problem or error, any circumstances that you feel relevant
and your particular computer system. We will endeavour to return your mail within the day.

All letters should be addressed to:

Hasbro Interactive (Europe) Customer Support

The Ridge, Chipping Sodbury

South Gloucestershire

BS37 6BN

England, UK

CUSTOMER SERVICES - AUSTRALIA

If you have problems and require assistance you can contact our Customer Services:

Phone: 1902 262 667

(calls charged at $1.50 per minute, a higher rate applies to mobile and public phones).


MECHCOMMANDER DESPERATE MEASURES 35


NOTICE/ WARRANTY


1. LICENCE

The software and all images, photography, animations, video, audio, music and text contained on the
enclosed CD-FIOM and this manual, (together, 'the Product') are protected by copyright and other
inteiiectual property rights which are owned by or licensed to Hasbro Interactive Limited of
2 Fioundwood Avenue, Stockley Park, Uxbridge, UB1 1 1 AZ ('Hasbro').

Hasbro grants to you as the original purchaser of this Product a non-transferable right to use the Product
for your own personal and private use and not in connection with any business activity. Unless otherwise
permitted by law, no part of this Product may be copied, reproduced, translated, modified, decompiied or
reduced into any electronic or other form without the prior written consent of Hasbro. You may not rent or
lease, or sell or transfer copies of the Product or any part of it.

2. WARRANTY

Hasbro warrants to you oniy that for a period of ninety days from purchase the Product wili perform
substantially in accordance with the specifications set out in this manual and that the original CD-ROM
disk itself will be free from defects in materials and workmanship.

During this period the Product, if defective, wiii be repiaced free of charge if returned to Hasbro at
Casweil Way, Newport, Gwent, NP9 OYH, together with a dated proof of purchase, a brief description
of the defect and the address to which it is to be returned. Any repiacement will be warranted for
a further 90 day period. This warranty does not affect your statutory rights in any way.

TTiis warranty does not apply to defects caused by misuse, negiect, incorrect installation, damage,
alteration, repair or excessive wear.

3. LIABILITY

Except as stated at 2 above, all conditions, warranties, terms, representations and undertakings express
or impiied, statutory or otherwise, in respect of the Product are expressiy excluded.

Hasbro's liability to you shall under no circumstances exceed the original retail price of the Product and
Hasbro does not accept liability for any indirect or consequential damage or loss (even if it is aware that
the possibility of such damage or loss) including lost profits or revenues, or for any damages, costs
or loss incurred as a result of loss of time or data or from any other cause.

Nothing set out above shall limit or exclude the Hasbro's liability to you for death or personal injury
resulting from its own negligence or any other liability not capable of exclusion or limitation by law.

If you do not agree to be bound by these terms, you should immediately return the Product to Hasbro
at Caswell Way, Newport, Gwent, NP9 OYH, together with a dated proof of purchase, for a full refund.


36 MECHCOMMANDER DESPERATE MEASURES


HASBRO INTBRACnVE'S WEB SITES

Hasbro Interactive has exciting, full and active web sites dedicated to ensure you get the most
out of your new games. You can visit us at:

http://www. hasbro-interactive. com

¦ Technical Support

¦ Hints and Tips

¦ Software Upgrades

¦ Demos

¦ Interaction

¦ Interviews

¦ Competitions
and much more.

We are constantly updating our web sites so stop by and visit us frequently. With events and
new additions planned, you won’t want to miss out.


MECHCOMMANDER DESPERATE MEASURES 37







IQTES







MECHCOMMANDER

KEYBOARD

FUNCTION

CHART


? COMBAT/TACTICAL

Assault from current location

C+Left mouse button

Assault from long range

L+Left mouse button

Assault from medium range

M+Left mouse button

Assault from short range

S+Left mouse button

Attack head

8+ Left mouse button

Attack left torso

7+Left mouse button

Attack right torso

9+ Left mouse button

Attack centre torso

5+Left mouse button

Attack left arm

4+ Left mouse button

Attack right arm

6+ Left mouse button

Attack left leg

1+Left mouse button

Attack right leg

3+ Left mouse button

Order ammo conservation mode

A+Left mouse button

? FIRE SUPPORT

Drop small artillery strike

1 +Left mouse button

Drop large artillery strike

2+Left mouse button

Drop sensor probe

3+ Left mouse button

Drop camera drone

4+Left mouse button

? ORDERS


Hold fire/stop

BACKSPACE

Guard

G+Left mouse click on target

Capture

Left mouse click context-sensitive cursor on item

Repair/refit

Left mouse ciick context-sensitive cursor on item

Lay mines

F+Left mouse button click

Power up

PAGE UP

Power down

PAGE DOWN

Eject pilot

HOME+Left mouse button on unit

? UNIT CONTROL


Reassign Force Groups

CTRL+F1 through F4

Seiect all units in view

i

Deselect all units

Right mouse button on battlefield view

Get information on unit

i+Left mouse button on unit

? MOVING UNITS


Move ha If- power

Left mouse button

Move full-power

SPACEBAR+Left mouse button

Jump (jump-enabled ’Mechs only)

J+Left mouse button

Create walk waypoint

CTRL or F9

Create run waypoint

CTRL+SPACEBAR or F10

Create jump waypoint

CTRL+J or F11

Create minelayer waypoint

CTRL+F

? BATTLEFIELD VIEW

Zoom view in

PLUS SIGN

Zoom view out

MINUS SIGN

Scroll down

DOWN ARROW

Scroll up

UP ARROW

Scroll left

LEFT ARROW

Scroll right

RIGHT ARROW

? MULTIFUNCTIONAL DISPLAY (MFD)


Open/close MFD

ALT

Open/close MFD (Command Palette)

TAB

? SYSTEM COMMANDS


Pause game

ESC or PAUSE

Enter chat mode (multiplayer)

ENTER


SUPPLEMENTAL

BRIEFING






Mknvsoft
