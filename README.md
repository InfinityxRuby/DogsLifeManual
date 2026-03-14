# Dog's Life - Manual APWorld
A Manual APWorld for Dog's Life on PS2, made with [Manual for Archipelago.](https://github.com/ManualForArchipelago/Manual) This project is in active development and content, checks, locations and features are subject to change. Presently, the current release is best compared to a proof-of-concept, placing checks on all available bone locations and Top Dog contests in each of Clarksville's sub-areas and a meta "goal" location that can be sent once the Player boards the train and departs for Lake Minniwahwah.

## What are the rules?
- Smellovision is off-limits (after the forced Smellovision perspective in the opening tutorial) until it is received from the pool.
- The Player cannot use any dogs other than Jake to acquire bones until they have received the corresponding dog's "Unlock" item from the pool. If the Player has less "Progressive Bone" items than the total bone power of another dog, they may not control that dog even if they've acquired the "Unlock" item for that dog. For example, Lopez the Chihuahua has a bone power of 1. The Player cannot control Lopez until they have received the "Lopez Unlock" item and at least 2 "Progressive Bone" items.
- Bones buried in the ground can be collected without Smellovision, but doing so will be considered "out of logic" - Currently, logic expects Smellovision to be acquired before the Player digs up buried bones.
- In the base game, the train to Lake Minniwahwah only requires 16+ bones. However, to incentivise longer playtimes, the Player must acquire a few more items than that since the train is the goal. See below for that list.

## Locations (Clarksville Demo)
Currently, the locations implemented in the AP World include:
- Every bone found lying around in each sub-area.
- Every bone given to the Player via side-quests.
- Every bone awarded via purple/violet/blue scent challenges.
- Every victory in Top Dog challenges.
- Boarding the train in `Clarksville - Centre` to Lake Minniwahwah.

## Items (Clarksville Demo)
- `Progressive Bone` - The main collectible of Dog's Life, bones allow the Player to surpass other dogs in Top Dog challenges, earning the right to command them.
- `Clarksville - [Dog] Unlock` - A series of new items for the manual. Even if a Dog is beaten in a Top Dog challenge, the Player must have that dog's "Unlock" item before they are allowed to make use of the dog.
- `Smellovision` - One of Dog's Life's major mechanics. Smellovision allows the Player to enter first-person and sniff out differently-coloured scents, granting bones and challenges for doing so.
- `Beg 1` & `Beg 2` - These moves allow Jake to perform different beg moves once the Player wins a Doggy Do challenge. Currently, these do nothing but they're cute and fun.
- `Train Ticket: Lake Minniwahwah` - A necessary item to goal. Collecting this gives the Player the right to board the train in `Clarksville - Centre` to Lake Minniwahwah.

## Goal Requirements (Clarksville Demo)
In the current demo of the Dog's Life manual, the goal is reached when the Player departs for Lake Minniwahwah. A handful of items are required in order to make this possible.
- `16+ Progressive Bones` are required to surpass the Doberman guarding the train station.
- `Smellovision` is required to challenge the Doberman to a Top Dog challenge.
- `Clarksville - Doberman Unlock` is required, to signify that the Doberman "respects" the Player enough to let them pass.
- `Train Ticket: Lake Minniwahwah` is required to give the Player the right to board the train.
In order to track these efficiently, I recommend the use of [Universal Tracker](https://github.com/FarisTheAncient/Archipelago/releases?q=Tracker). Given that Dog's Life is a fairly unknown game to begin with, this tool can be especially helpful for tracking what can and can't be done.

## Planned Features
These are subject to change, and suggestions are always appreciated.
- Begsanity: Receiving a treat from each NPC that gives one when Jake begs would be a check.
- Shavesanity: Grabbing an animal and pressing the Bark button to "shave" its fur/feathers once per sub-area would award a check.
At this stage, the only thing holding me back from implementing these is a lack of ideas for items to place in these locations.

## Supported Versions and Disclaimer
The manual was created using the NTSC-U version of Dog's Life for PS2 (`SLUS-21018`) running on the PCSX2 emulator. However, as this is a manual and the game is relatively identical in all regions, any support offered for the NTSC-U version of the game should apply to all other versions. I do not condone piracy and will not distribute, or assist with distributing, illegitimate copies of the game. Please only indulge in this manual on official hardware or via an emulator running your own legal dump of the game.
