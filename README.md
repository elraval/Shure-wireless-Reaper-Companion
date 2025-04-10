# Shure Wireless and Reaper Companion configuration
Bitfocus Companion configurations to monitor Shure wireless receivers data and listen to them in Cockos Reaper. 
Used by A2's, RF and mic-up techs in live events to monitor Shure Wireless wireless microphones.
Usually used in conjunction with Dante Virtual Soundcard (DVS).

## SOFTWARE REQUIREMENTS
   - BitFocus Companion https://bitfocus.io/companion
   - Cockos Reaper https://www.reaper.fm/
   - Dante Virtual Soundcard (or any multitrack soundcard that can feed Reaper inputs)

## CONFIGURATION PAGES

### **1 - Reaper track unMute/Mute**

![Screenshot 2024-01-24 at 16 08 26](https://github.com/elraval/shure_wireless_reaper_companion/assets/22182319/a5d8c051-d598-4dc1-b9e1-49a7912564db)

This page allows for visual monitoring of Shure wireless equipment data on the button.
  
1) Pressing the button once unmutes a Reaper track, thus sending signal from that channel to the Master Bus. Red button after pressing.
2) Pressing the button a secong time mutes that track. Button restores to black background.

Companion Modules required:
 - Shure Wireless Microphones module (as many instances as your networked receivers) 
 - Cockos Reaper module (Arm and Unarm actions are built in the module)
   

### 2 - Reaper Volume control

![Screenshot 2024-01-24 at 15 39 57](https://github.com/elraval/shure_wireless_reaper_companion/assets/22182319/d7394489-14be-4c72-91d8-6284293b6380)

The page above controls Reaper Master volume fader

Companion Modules required:
- OSC Generic module

## REAPER CONFIGURATION

- Build youself a multitrack session in Reaper and patch your soundcard inputs to individual channels.
- Activate OSC in Reaper preferences. Here's an example of sucha a Reaper session and OSC settings:

![Screenshot 2024-01-24 at 19 36 41](https://github.com/elraval/Shure-wireless-Reaper-Companion/assets/22182319/25fa017c-9423-4885-8a01-087c2d98c246)

## COMPANION CONFIGURATION

- Set the IP addresses of all your receivers in Companion's shure-wx module:
  
![Screenshot 2024-01-24 at 19 44 05](https://github.com/elraval/Shure-wireless-Reaper-Companion/assets/22182319/508f5fe8-36bb-4b66-a59d-0d3f748177e6)

- Set the IP address and Ports in both your Reaper and Generic OSC modules. Here's an example of it when Reaper is running on the Companion machine:

![Screenshot 2024-01-24 at 20 03 18](https://github.com/elraval/Shure-wireless-Reaper-Companion/assets/22182319/af0353ae-74db-44c3-b2d3-5ef29c339173)


  
