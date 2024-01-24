# shure_wireless_reaper_companion
Bitfocus Companion configurations to monitor Shure wireless receivers data and listen to Cockos Reaper channels

SOFTWARE REQUIRED:
- BitFocus Companion https://bitfocus.io/companion
- Cockos Reaper https://www.reaper.fm/


CONFIGURATION PAGES

PAGE 1) Reaper track Arm/UnArm with Shure wireless equipment feedback

![Screenshot 2024-01-24 at 16 08 26](https://github.com/elraval/shure_wireless_reaper_companion/assets/22182319/a5d8c051-d598-4dc1-b9e1-49a7912564db)

  This page allows for visual monitoring of Shure wireless equipment data on the button.
  
  STEP 1) Pressing the button once arms a Reaper track, thus sending signal from that channel to the Master Bus.
  
  STEP 2) Pressing the button a secong time un-arms that track.

Companion Modules required:
 - Shure Wireless Microphones module (as many instances as your networked receivers) 
 - Cockos Reaper module (Arm and Unarm actions are built in the module)
   



PAGE 2) Reaper Volume control

![Screenshot 2024-01-24 at 15 39 57](https://github.com/elraval/shure_wireless_reaper_companion/assets/22182319/d7394489-14be-4c72-91d8-6284293b6380)

The page above controls Reaper Master volume fader and requires the OSC Generic module running in Companion.
