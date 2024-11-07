## Species
File: *natives/stm/gamedesign/common/enemy/enemyspecies.user.3*

![](./attachments/Pasted%20image%2020241106210014.png)

![](./attachments/Pasted%20image%2020241106210014.png)
## Enemy Data
File: *natives/stm/gamedesign/common/enemy/enemydata.user.3*
File: *natives/stm/gamedesign/enemy/commondata/enummaker/emid.user.3*
This whole directory contains tons of data about all the enemies in the game
- it also contains uuids for the enemy names, Icon Colors, and if they should be drawn on the map, or filtered from it
Ive also found another special attack type called LAST_BOSS
144 Enemies in total (large, small, endemic, fish)
Enum MAX is 204
EM0156 has a special culling enum, which might make it interesting, new mechanics
### Large Monsters
These first 30 seem to be actual bosses

![](./attachments/Pasted%20image%2020241106204605.png)
#### Attack Types
Pasted%20image%20
File: *natives/stm/gamedesign/common/enemy/enemyreportsepcialattacktypedata.user.3*

![](./attachments/Pasted%20image%2020241106210733.png)
### Small Monsters
File: *natives/stm/gamedesign/common/enemy/enemynamefishingsortdata.user.3*

![](./attachments/Pasted%20image%2020241106211333.png)

### Endemic Life
File: *natives/stm/gamedesign/common/enemy/enemynamefishingsortdata.user.3*


### Fish
File: *natives/stm/gamedesign/common/enemy/enemynamefishingsortdata.user.3*

![](./attachments/Pasted%20image%2020241106211246.png)
## Enemy Parts Data
Stuff with the frozen core is likely the final boss, which is also em0164
File: *natives/stm/gamedesign/common/enemy/enemypartstypedata.user.3*

![](./attachments/Pasted%20image%2020241106211430.png)
![](./attachments/Pasted%20image%2020241106211450.png)

![](./attachments/Pasted%20image%2020241106211501.png)
## Quest Data
File: *natives/stm/gamedesign/common/enemy/enemyquestdata.user.3*
Shows points earned from hunting different monsters. Includes large, small and fish.

![](./attachments/Pasted%20image%2020241106205744.png)

![](./attachments/Pasted%20image%2020241106205900.png)
### Quset Reward Rates
File: *.\REtool\re_chunk_000\natives\stm\gamedesign\mission\_userdata\_reward/rewardratedata.user.3*

![](./attachments/Pasted%20image%2020241106233921.png)
### Quest Types
File: *.\REtool\re_chunk_000\natives\stm\gamedesign\mission\_userdata\questsetting.user.3*

![](./attachments/Pasted%20image%2020241106234355.png)
## Hunter Rank
File: *\natives\stm\gamedesign\common\gamesystem\hunterrank.user.3*
No master rank, goes up to 8 stars in the village, up to 999

![](./attachments/Pasted%20image%2020241106213709.png)
## Events, Gimmicks and Environments
File: *re_chunk_000/natives/stm/gamedesign/environment/enummaker/exanimalevent.user.3*

![](./attachments/Pasted%20image%2020241106225050.png)
File: *natives/stm/gamedeisng/common/gimmick/gimmicktextdata.user.3*
File: *natives/stm/gamedeisng/common/exevent/exgimmickeventdata.user.3*
Not really sure what the gimmicks are, but my guess is special events that happen
Im guessing that they have to do with events that occur in the world.
VILLAGE_BOOST - something to do with the village
XXXX_VIEW - I think environment, desert is Thunder, not sure what GM037 would be
almost defnitely has something to do with the maps

![](./attachments/Pasted%20image%2020241106214151.png)
There also might be an elevator in the game based on:
File: *natives/stm/gamedeisng/gimmicks/_develop/enummaker/gimmickelevatorphase.user.3*
maybe in the oil area
## Map
All the different maps/stages

![](./attachments/Pasted%20image%2020241106220933.png)

Different Events in each

![](./attachments/Pasted%20image%2020241106214914.png)
## Areas
File: *natives/stm/gamedesign/stage/common/enummaker/areaid.user.3*

![](./attachments/Pasted%20image%2020241106220437.png)

![](./attachments/Pasted%20image%2020241106220454.png)

![](./attachments/Pasted%20image%2020241106220426.png)
st2xx to st5xx might be connecting areas or arenas/final boss arena

Dark areas in desert

![](./attachments/Pasted%20image%2020241106232757.png)
Exploration of Fulgurite high ground in 3 areas
PL creeping destination within 5 areas
Underground part of 10 areas
1 area valley floor
High ground general-purpose nest in 3 areas
Indoors of sand village
sand bc indoor
Chatakabra nest
sand sea dragon nest - balahara????
## Villages
File: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\stage\common\enummaker/lifearea.user.3*
5 basecamps
6 villages
st502??

![](./attachments/Pasted%20image%2020241106220750.png)
### Basecamps
File: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\\stage\basecamp\basecampmanagedata.user.3*

![](./attachments/Pasted%20image%2020241106232145.png)
## Armor
File: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\stage\common\player/enummaker/armorseries.user.3*
155 armor pieces  / 3 = 51 armor sets?? idk about lr/hr though

## Gestures
File: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\stage\common\player/enummaker/huntercommtype.user.3*

![](./attachments/Pasted%20image%2020241106221741.png)
## Slinger ammos
File: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\stage\common\player/enummaker/hunterslingerammotype.user.3*

![](./attachments/Pasted%20image%2020241106222038.png)
## Ammo Types
File: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\stage\common\player/enummaker/wpgunshelltype.user.3*

![](./attachments/Pasted%20image%2020241106222452.png)
## Sharpness
File: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\stage\common\player/enummaker/weaponkireajitype.user.3*
goes to purple

## Weapons
Files: *C:\Users\nikol\Desktop\REtool\re_chunk_000\natives\stm\gamedesign\stage\common\player/enummaker/_insert_wp_name_id.user.3*
Bows: 110 
Charge Blade: 128
Gun Lance: 129
Hammer: 127
HBG: 127
Lance: 129
LBG: 105
LS: 121
IG: 127
SnS: 146
Switch Axe: 129
GreatSword (tachi?): 110
Dual Blades: 137
Whistle (HH): 137
## Dialogue
File: *re_chunk_000/natives/stm/gamedesign/dialogue/commondata/enummaker/dialogueid.user.3*
6949 Dialogues
## Facilities
File: *re_chunk_000/natives/stm/gamedesign/facility/enummaker/facilityid.user.3*
BARREL BOWLING YEP
MACA/MAKA Alchemy is just alchemy from old games
HELP_NPCXXX has to do with events and gimmicks, i think you can rescue them from monsters (JUST THEORIZING)

![](./attachments/Pasted%20image%2020241106225426.png)
### Items
File: *re_chunk_000/natives/stm/gamedesign/facility/enummaker/itemid.user.3*
724 Items in the game
## NPCS
File: *re_chunk_000/natives/stm/gamedesign/npcs/enummaker/\**
milking?

![](./attachments/Pasted%20image%2020241106230232.png)

NPC Fishing

![](./attachments/Pasted%20image%2020241106230413.png)

NPC Types

![](./attachments/Pasted%20image%2020241106230544.png)
## Felynes/Otomo
File: *re_chunk_000/natives/stm/gamedesign/otomo/enummaker/otomospeechsituation.user.3*
Shows situations when your felyne would activate different voicelines\

![](./attachments/Pasted%20image%2020241106231612.png)
## Enum Files
```
enummaker
./re_chunk_000/natives/stm/_develop/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/camera/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/dialogue/commondata/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/enemy/commondata/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/environment/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/facility/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/gimmick/_develop/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/gui/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/input/enummaker:
_enummaker
./re_chunk_000/natives/stm/gamedesign/mission/_enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/npc/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/npc/partner/commondata/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/otomo/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/player/enummaker:
./re_chunk_000/natives/stm/gamedesign/player/enummaker/weapon:
enummaker
./re_chunk_000/natives/stm/gamedesign/porter/enummaker:
enummaker
./re_chunk_000/natives/stm/gamedesign/stage/common/enummaker:
```