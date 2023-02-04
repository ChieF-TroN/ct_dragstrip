To purchase CT_Dragstrip, please visit the link below!
https://forum.cfx.re/t/paid-standalone-ct-dragstrip-fully-functioning-drag-light-bradenton-motorpark-speedway-fl2k/4769739

Installation:

Download the following dependencies first:
PolyZone:
https://github.com/mkafrin/PolyZone
T-Notify:
https://github.com/TasoOneAsia/t-notify

Add the following to your server.cfg:
ensure PolyZone
ensure t-notify
ensure ct_dragstrip

**NOTE** If you do not wish to use the Sandy Shores or Fort Zancudo Tracks, remove them from the stream folder. **DO NOT** Remove the [dragtree] folder.

Modifications:
client/_polyzones.lua -- Add/Modify Polyzones for each track
shared/_config.lua -- Add/Modify Light config, Edit client/server side config

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
