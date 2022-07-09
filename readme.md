
# Twitch-Stream-Monitor
- [Twitch Stream Monitor](#Twitch-Stream-Monitor)
  - [Description](#description) 
  - [Settings Overview](#settings-overview)
  - [Features](#features)
    - [Actions](#actions)
    - [States](#states)
  - [F.A.Q](#FAQ)
  - [Bugs and Support](#bugs-and-suggestion)
  
# Description
### **Use the plugin and determine who is the best choice for you to Watch/Host/Raid without going to 20+ different Twitch Pages!**

Useful when you are ready to shut down your stream for the night but don't know who to raid 
or host or just not sure what streamer to watch and just want to see your favorite list

* Streamer Name
* Streamer Picture 
* Total Viewers
* Time Online
* Game Title Icon
* Game Art Icon
* Live Preview Icon
* Is the Stream 18+ ?




## Settings Overview

  
| Setting Name | Description | Type | Default Value |
| --- | --- | --- | --- |
| AutoUpdate | Auto Update - ON/OFF | text | OFF |
| Auto Update Seconds | How often to update, if enabled | number | 60 |
| Live Thumb Size | Change Retrieved Live Thumb Size | text | 250x140 |
| Game Thumb Size | Change Retrieved Game Thumb Size | text | 128x128 |




# Plugin Features

## Actions

| Action Name | Description | On Hold |
| --- | --- | --- |
| Manually Check Raid / Host List | Checks the Raid_List.txt and Updates States |  False |
| Force Refresh State Updates | Allows you to force refresh your UI  | False |



## States
<details id='gitago.tw_stream_monitor.mainstates'><summary><b>Category:</b> SM | Twitch Stream Monitor <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck.Channels_Online | SM | --- Total Channels Online | Un-Checked |   |
| .state.raidcheck.Total_Raid_List | SM | --- Total Channels |  |   |
| .state.raidcheck.AutoUpdate_Status | SM | --- Auto Update Status (TRUE/FALSE) |  |   |
| .state.raidcheck.AutoUpdate_Switch | SM | --- Auto Update Switch (ON/OFF) |  |   |
| .state.raidcheck.AutoUpdate_TIMELEFT | SM | --- Auto Update Time Left) |  |   |
| .state.raidcheck.RaidPreview | SM | --- Preview Raid Person) |  |   |
</details>

<details id='gitago.tw_stream_monitor.Raidcheck_1states'><summary><b>Category:</b> SM | Raid #1 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_1.user_name | SM | Raid #1: User Name |  |   |
| .state.raidcheck_1.game_name | SM | Raid #1: Game Name |  |   |
| .state.raidcheck_1.is_mature | SM | Raid #1: is_mature? |  |   |
| .state.raidcheck_1.title | SM | Raid #1: Title |  |   |
| .state.raidcheck_1.viewer_count | SM | Raid #1: Views |  |   |
| .state.raidcheck_1.livetime | SM | Raid #1 Live Time |  |   |
| .state.raidcheck_1.live_thumb | SM | Raid #1 Live Thumbnail |  |   |
| .state.raidcheck_1.user_thumb | SM | Raid #1 User Thumbnail |  |   |
| .state.raidcheck_1.game_thumb | SM | Raid #1 Game Thumbnail |  |   |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_2states'><summary><b>Category:</b> SM | Raid #2 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_2.user_name | SM | Raid #2: User Name |  |   |
| .state.raidcheck_2.game_name | SM | Raid #2: Game Name |  |   |
| .state.raidcheck_2.is_mature | SM | Raid #2: is_mature? |  |   |
| .state.raidcheck_2.title | SM | Raid #2: Title |  |   |
| .state.raidcheck_2.viewer_count | SM | Raid #2: Views Time |  |   |
| .state.raidcheck_2.livetime | SM | Raid #2 Live Time |  |   |
| .state.raidcheck_2.live_thumb | SM | Raid #2 Live Thumbnail |  |   |
| .state.raidcheck_2.user_thumb | SM | Raid #2 User Thumbnail |  |   |
| .state.raidcheck_2.game_thumb | SM | Raid #2 Game Thumbnail |  |   |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_3states'><summary><b>Category:</b> SM | Raid #3 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_3.user_name | SM | Raid #3: User Name |  |   |
| .state.raidcheck_3.game_name | SM | Raid #3: Game Name |  |   |
| .state.raidcheck_3.is_mature | SM | Raid #3: is_mature? |  |   |
| .state.raidcheck_3.title | SM | Raid #3: Title |  |   |
| .state.raidcheck_3.viewer_count | SM | Raid #3: Live Time |  |   |
| .state.raidcheck_3.livetime | SM | Raid #3 Live Time |  |   |
| .state.raidcheck_3.live_thumb | SM | Raid #3 Live Thumbnail |  |   |
| .state.raidcheck_3.user_thumb | SM | Raid #3 User Thumbnail |  |   |
| .state.raidcheck_3.game_thumb | SM | Raid #3 Game Thumbnail |  |   |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_4states'><summary><b>Category:</b> SM | Raid #4 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_4.user_name | SM | Raid #4: User Name |  |   |
| .state.raidcheck_4.game_name | SM | Raid #4: Game Name |  |   |
| .state.raidcheck_4.is_mature | SM | Raid #4: is_mature? |  |   |
| .state.raidcheck_4.title | SM | Raid #4: Title |  |   |
| .state.raidcheck_4.viewer_count | SM | Raid #4: Live Time |  |   |
| .state.raidcheck_4.livetime | SM | Raid #4 Live Time |  |   |
| .state.raidcheck_4.live_thumb | SM | Raid #4 Live Thumbnail |  |   |
| .state.raidcheck_4.user_thumb | SM | Raid #4 User Thumbnail |  |   |
| .state.raidcheck_4.game_thumb | SM | Raid #4 Game Thumbnail |  |   |
</details>

<details id='gitago.tw_stream_monitor.raidcheck_5states'><summary><b>Category:</b> SM | Raid #5 <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.raidcheck_5.user_name | SM | Raid #5: User Name |  |   |
| .state.raidcheck_5.game_name | SM | Raid #5: Game Name |  |   |
| .state.raidcheck_5.is_mature | SM | Raid #5: is_mature? |  |   |
| .state.raidcheck_5.title | SM | Raid #5: Title |  |   |
| .state.raidcheck_5.viewer_count | SM | Raid #5: Live Time |  |   |
| .state.raidcheck_5.livetime | SM | Raid #5 Live Time |  |   |
| .state.raidcheck_5.live_thumb | SM | Raid #5 Live Thumbnail |  |   |
| .state.raidcheck_5.user_thumb | SM | Raid #5 User Thumbnail |  |   |
| .state.raidcheck_5.game_thumb | SM | Raid #5 Game Thumbnail |  |   |
</details>

**Up to 15 Total Pre-Created User Folders**

<br>

# FAQ
  
### **Q)** How do I add names to the List to search for?
**A)** There is a plugin action called #SET-CHANNELS you can utilize to open the raid_list.txt file
 
### **Q)** Why arent my states aren't updating?
**A)** If your set to Auto Update and see the update timer ticking, then try a manual refresh. 
  
### **Q)** Why are the images blurry?
**A)** You may adjust the size of the icon displayed in the plugin settings.<br />
  Please be aware this may take up CPU usage when it retrieves a new photo.
  
### **Q)** The plugin seems to not work anymore?
**A)** Please check your plugin settings and make sure its approved/running.<br />
  If you have confirmed it is running then a quick restart of TouchPortal may be needed to make it work properly again. 
  
  
# Bugs and Suggestion
Open an issue on github or join offical [TouchPortal Discord](https://discord.gg/MgxQb8r) for support.


# License
This plugin is licensed under the [GPL 3.0 License] - see the [LICENSE](LICENSE) file for more information.

