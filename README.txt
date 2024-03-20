Thank you for your purchase of CT_DragStrip! v4.2

If you have any questions, please post them on the CT_DragStrip FiveM Forums Thread:

https://forum.cfx.re/t/paid-standalone-ct-dragstrip-fully-functioning-drag-light-bradenton-motorpark-speedway-fl2k/4769739

Installation:

Download the following dependencies first:
PolyZone:
https://github.com/mkafrin/PolyZone
T-Notify:
https://github.com/TasoOneAsia/t-notify
QB-Input:
https://github.com/qbcore-framework/qb-input

Add the following to your server.cfg:
ensure PolyZone
ensure t-notify
ensure qb-input 
ensure ct_dragstrip

**NOTE** If you do not wish to use the Sandy Shores or Fort Zancudo Tracks, remove them from the stream folder. **DO NOT** Remove the [dragtree] folder.
**NOTE 2** You do not need to ensure qb-input if you're using ox_lib. If you are using ox_lib, make sure to uncomment the line in the fxmanifest.

Modifications:
client/_polyzones.lua -- Add/Modify Polyzones for each track
shared/_config.lua -- Add/Modify Light config, Edit client/server side config

Update from 4.1 to 4.2
- Added support for custom drag lights. (USE AT OWN RISK) ***I DO NOT GIVE SUPPORT FOR CUSTOM LIGHTS***
- Added Framework auto detection.


Update from 4.0 to 4.1
- Added ox_lib menu support.
- Added cfg.inputMenu option to config.

Update from 3.5 to 4.0
- Added Drag Strip Configuration Menu (qb-input dependent)
- Added Class Restrictions to Drag Strip Configuration Menu
- Added Class Restrictions to Drag Strip _config file (please update accordingly)
- Added Functions for CT_DragStrip_ELO v2.0
- Added Configurable /PersonalStats command
- Increased Finish Line PolyZone Size for Both Tracks (help prevent racers not finishing properly)
- Added a check for racers that quit the server in the middle of the race and reset the drag strip lights.

Update from 3.4 to 3.5
- Updated ESX core getter

Update from 3.3 to 3.4
- Added Support for ct_dragstrip_elo

Update from 3.2 to 3.3
- Moved all notifications server side.
- Made the official time notifications available to all within cfg.chatDistance
- Added cfg.announceOfficialTimesToAllNotification toggle for the mentioned above
- QB-Core Chat/Notifications now use character names instead of steam name

Update from 3.1 to 3.2
- Fixed randomized timers for each race.
- Removed cfg.randomTime
- Added cfg.randomTimeMin
- Added cfg.randomTimeMax
- Feature: Added ability to customize notifications. Default supported notifications: t-notify, qb, vrp, esx, okokNotify, with the ability to add your own notifications.

Update from 3.0 to 3.1
- Added Betting system - compatible with vRP, ESX, QBCore, and Standalone.
- Added Framework varible in config.
- Added Betting Command variable in config.
- Betting system is in a pool format, you will win the percentage of the total bet for your lane determined by how much you put in. 
Example: Left lane has 2 bets, 500$ each, and right lane has 1 bet 500$. Left Lane wins, the pot is split between the 2 500$ bets, 50/50.
Example2: Left lane has 2 bets, first bet 250$, second bet 750$, right lane has 1 bet, 1000$. Left lane wins, pot is split, 25/75. So you'd get your original bet back + whatever percentage you put in.


Update from 2.4 to 3.0
- Refactored code to handle multi-track support.
- Added example second track at Fort Zancudo. Slightly Modified Version of https://www.gta5-mods.com/maps/zancudo-drag-strip-fivem. (Removed light to make room for the drag light to spawn)
- Added track name to race results announcements.
- Added resource to FiveM Escrow System.
- Fixed bug where stats were not displayed to chat/discord log when using both lanes.

Update from 2.3 to 2.4
- Added 0-60MPH + 0-100MPH Trap Times to Dragy.
- Made some adjustments to chat/discord logging functions.

Update From 2.2 to 2.3
- Added Webhook abilities for race results.
- Added Chat Log (with configurable distance check)
- Added a Shared config file for client/server.
- Moved PolyZone config to seperate config file.
- Removed random wrench from map.

Update from 2.1 to 2.2
- Added Dragy Time Slip (UI Code courtousy of Kuzkay (kuzquality.com))
- Added Enable/Disable Dragy to Config.

Update From 1.1.1 to 2.1.0
- Added Solo Racing
- Added Lane Switcher Location (Toggle between Left, Right, Both Lanes)
- Added Winner Indicator to Staging Tree. (Winner's side will flash after a win.)
- Added several more options to the config to configure the new additions.
