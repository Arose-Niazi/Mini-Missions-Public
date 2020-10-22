
# Mini Missions v14 (outdated)
Developed By Arose Niazi (Sasuke_Uchiha)

## Features
### Lobby
- Spawns in lobby normally.
- Location: LS Atrium
- You can exit lobby to the world of free-roam.
- You can spawn one vehicle.
- You can remove the vehicle. 

### Login/Register.
- Auto-Login.
- Login dialog shows the join date and register the country as well.
- 5 Attempts before you are kicked.
- Before registering you have to read and accept the server rules.
- Top 54 passwords from the last 4 years are disabled.
- Passwords such as, aaaaaa, bbbbbb, 111111, etc are disabled.
- Auto-Login can be enabled or disabled by settings, set to enabled by default.

### Stats
- Players stats are saved on criteria of
    - Per Year
    - Per Month
    - Per Mission
- Stats are saved before a mission starts, and after you pass your mission.
    - Saving twice so data of lobby could be separated from the mission.
- On server being closed manually, your data will also get saved.       

### Chatbox
- Server message sync to Discord.
- Anti-spam.
- Anti advertisement

### Discord
- Discord channels.
    - #echo -> A channel for Everyone. 
    - #echo-admins -> A channel for admins.
    - #echo-managers -> A channel for managers.
    - #cho-bans -> A channel for ban messages.
- !s(ay).
- To get your rank for discord you need to use command /discord in the server.

### Mute system
- You need to complete your punishment, this means if you leave the server your punishment will be saved and then resumed later on.

### Ignore system.
- You can ignore anyone except head admins or higher. 
- Players you ignore, won't be shown in your chatbox.

### Jail system.
- You need to complete your punishment, this means if you leave the server your punishment will be saved and then resumed later on.

### Textdraws.
- Connect. 
- Missions Info. 
    - Made by @TheChaoz
- New clock.
    - Made By @Bullet
- Countdown. 
    - Made by @TheChaoz
- Pos o Meter, checkpoints. 
    - Made by @Bullet
- Ghost Mode.
    - Made by @Bullet    
- Infobox.
- Total XP, Current XP, and Current Level. 
    - Current XP/Level
        - Bullet
- XP Gained.
- Cool menu. 
    - Made by @Ziggi
- Objective.   
    - Made by @Bullet     
- Warnings.
- Spectate
    - Made by @Bullet

### Cycle Handler
- Votemode.
- votemode2.
- Open vote.
- Random cycle.
- Random cycle 2.
- The default cycle would be the random cycle.
- Made sure the server doesn't get stuck even if there is one/no mission in the server. 
- mforce,m(next)mission is for must force, it will force the mission even if it's disabled. So this means event maps like duels can be added.  
- New missions added, or any change done to missions via UCP will take effect in a 5 mins timer that runs and checks all missions. 
- Setting world weather and world time as -1 to set random world weather and world time.
- Scripter/Mapper name can now use their account ID, this way maps of user can be tracked along with nick changes.

### Mission Handler
- Loading and unloading of missions.
- Working timer for mission time.
- Loading the next mission should take around 1 second at max.

### Mission Types
- Race Type. -> 0
- LTS Type. -> 5
- TDM Type. -> 6
- Parkour Type. -> 7


### TDM 
- A champion will be selected from the winning team, the player with best K/D ratio.
- Reward for champion, $25 and a cookie. 

### LTS 
- A champion will be selected from the winning team, the player with most kills.
- Reward for champion, $25 and a cookie. 

### Personal Best / Race Records / Top 5
- Your personal best for each mission will be recorded, missions where you have to race with others. This will be used in race records.
- Breaking and making a record has different rewards.
- Breaking 5th record will be considered as making a reward, while any other will be breaking.
- You get a reward for improving your record. 

### Ranks
- Regular Player.
- Retired Staff.
- VIP.
- Moderator.
- Administrator
- Head Administrator
- Manager
- Owner

#### VIP
- Skip mission by pressing escape on mission info dialog. 

#### Moderators
- Skip mission by pressing escape on mission info dialog. 
- Duty mode will hide you from non-moderator players. 
- Duty mode gives unlimited health.

### Settings
- Auto-Login.
- Change Username.
    - All changed usernames are logged.
- Change password.
    - All changed password (hashed) are logged.
- Connect messages.
    - This includes disconnect messages too. 
- Change/remove titles.
- Menu position change.
    - You can reset it to default by settings or /resetmenu in case you can't access it properly.
- Tab list. (The menu you see on pressing TAB key)
- Change GMT Timezone.

### Levels system
- XP.
- Each level has it's own XP level up, and every level can have different XP level up. Even some higher levels can have a very low XP level up. 

### World Weather/Time
- Random world weather when -1.
- Random Mission weather when -1. 
- There are specific random weathers that will be selected.
- Mission Info dialog would say weather name instead of weather id. 
    - Thanks to @Ryses for weather names.

### Money system
- On completing/winning a race, parkour, etc You get 100/Your Position.    

### Betting system
- You can place a bet, in first 20 seconds.
- If online players are less than 7, you can not place your bets.
- Bets outcome depends on the following factors;
    - Your level / 50.
    - Your Betting Money. 
    - Bot bet rate. 
    - Formula used; | Your bet + ((Your bet)[(Bot Bet Rate) + (Your level / 50) ]) | ~ Then rounding it off to nearest decimal place. 
- The maximum bet is $50 and the minimum is $1.
- Bet Winners;
    - Race -> 1st Pos.
    - Parkour -> 1st Pos.
    - TDM -> Champion.
    - LTS -> Champion.

### Titles System
- Titles have their color.
- Titles have their position, suffix, or prefix.
- You can remove/change your title from /settings.
- Titles are saved in the database, so they can be added/changed/deleted without a restart.
- Custom titles are saved in the database but have been limited to 1 per player which can easily be changed. 

### Tab list
- Each player can decide what tab list they want to see.
- Tab list for total XP.
- Tab list for mission data i.e mission kills, checkpoints, position, etc depending on mission's objective.
- Tab list can be changed from /settings.

### Time
- The Player's GMT will be zero by default. The player will be asked to set his GMT offset as soon as they register.
    - Skipping this will set it to zero too.
- The player can change it anytime from /settings
- All times in the server will be shown according to the player's GMT. 
- All times are saved according to the server's current host location when the player's GMT data won't be available the time will be displayed according to the server's location.

### Actions
- Players' important actions will be logged.
- These are stored in the database.
- Actions store date and time so are useful to find out a specific event.
- The player can view his 15 last actions.
    - This will display only the actions from the time player has been connected i.e current session.
    - Moderators+ can view anyone's actions.
- Actions logged are;
    - Mute actions (Type: Admin)
    - Jail actions (Type: Admin)
    - Level ups (Type: Levels)
    - Promotion/Demotions (Type: Admin)
    - Records (Type: Records)
    - Adding/Removing player in ignore list (Type: Miscellaneous)
    - Blackjack Games (Type: Gambling)
    - Kicks (Type: Admin)
    - Bans (Type: Admin)
    - Remove Warning (Type: Admin)
    - Cage (Type: Admin)
    - Slap (Type: Admin)
    - Hammer (Type: Admin)
    - Cookies (Type: Cookies)

### Blackjack;
- Max bet is $100.
- Min bet is $1.


### Warns System
- Maximum 5 warnings.
- The warning textdraw will be shown for 20 seconds.
- Once reached maximum warnings.
    - 3 Days ban.
    - All warnings will be removed. 
- A warning even after being removed remains in the database. 

### Reports System
- The last 10 reports are visible to admin.
- 3 Reports per minute to avoid spam.
- A successful ban on report leads to rewards.
    - Cookies (Rare).
    - Achievement (Exteremely Rare).
    - Money (Common)
    - XP (Common)

### Private Message
- Can't be send to players you are ignoring. 
- Can't recieve from players you are ignoring.
- Can be disabled.
    - Still staff members can send you pm. 

### Cookies
- Logged in actions.
- Ways to earn;
    - Win Mission.   
    - Report players.  
- Cookies can be bought/sold from/to players.
    - Min Sell Amount $0.
    - Max Sell Amount $1000.    

### Spectate
- Spectate in no respawn missions.
- Spectate team only option available.
- Spectate might take 1 second to update things. 

### Commands
- Players
    - General
        - /settings -> To chnage your accounts settings and prefrences.
        - /discord -> To connect your account with your discord nick-name. 
        - /resetmenu -> Set menu's position back to default.
        - /lastactions -> To see your last actions. 
        - /warn(ing)s -> Check your warnings.
        - /report -> To report a player.
    - Titles    
        - /mytitles -> To check your titles, and set it.
        - /mycustomtitles -> To check your titles, and set it.
        - /titles -> To check your or anyone's titles. This includes custom titles and simple titles. 
    - Chat
        - !s(ay) -> To send message to server from discord.
        - /privatemessage - /pm - /m(essage) -> Send private message.
        - /r(eply) -> Reply to last private message.
        - /nopm -> Disable/Enable private messages.
        - /ignore -> To add/remove players to your ignore list.
        - /ignorelist -> To check your ignore list.
    - Mission
        - /dpersonalbest -> Used to remove your personal best/record for that mission. 
        - /bet -> To place bet on a player for winning the mission.
        - /cycle -> To see next mission.
    - Lobby
        - /v -> Spawn Vehicle.
        - /remove -> Remove vehicle.  
        - /blackjack -> To start a blackjack match. 
    - Cookies
        - /sellcookies -> To put your cookies on sale.
        - /buycookies -> To purcahse cookies from other players.  
- Moderators
    - !/mute  -> Use it once to mute and then again to un-mute.
    - /ignorelist -> To check anyone's ignore list.
    - !/jailed -> To see a list of jailed players.
    - /lastactions -> To check players last actions. 
    - /!kick -> Remove a player from server.
    - /!nickcheck -> Get inforamtion about username.
    - /!idcheck -> Get information about account id.
    - !/ban -> Baning player.
        - 1 Day ban for moderators.
        - 0 for permenannt ban.
    - !/bancheck -> Details of a ban.
    - !/ipbancheck -> List of all bans with these ips/range.   
    - /duty -> To go on duty. 
    - /warn(ing)s -> Check anyone's warnings.
    - !/slap -> To slap a player.
    - !/hammer -> To reduce a players health by 30.
    - /goto -> Teleport to another player's location.
    - /reports -> To check last reports.
    - /spec(tate) -> To spectate a player.
    - /spectateoff - /specoff -> To turn off spectating.
    - /spec(tate)objective - /so -> To spectate objective.
    - /specv -> To spectate vehicle
- Admins
    - /unignore -> To remove anyone from someone's ignore list.
    - !/jail -> To jail and again to un-jail.
    - /!openvote -> Will open voting for new mission.
    - /!force - /!(next)mission -> Will force next mission.
    - !/deltime -> Subtract time from current mission.
    - !/addtime -> Add time in current mission. 
    - !/(end)mission -> Ends it, or cancels it.
    - !/forceend (!/fend) -> Skip Mission.
    - !/oban -> Offline Ban.
    - !/unban -> Complete unabn for a player.
    - !/warn -> Give player a warning. 
    - !d(elete)warn -> Remove a warning.
    - !/owarn -> Give offline player a warning.
    - !/explode -> Explodes player.
    - !/(un)cage -> cage/uncage player.
    - !/slapall -> Slap everyone.
    - /v -> Spawn Vehicle.
    - /remove -> Remove vehicle.
    - /get -> Teleport player to your location.
    - /gotoxyz -> Teleport to anywhere in map.
    - /setinterior -> Set player's interior.
    - /setvirualworld -> Set player's virtual world. 
- Head Admins
    - /!votemode(2) (vm)(2) -> Will set the mission selection mode.
    - /!randomcycle2 - /!rc2 - !/rcycle2 -> Will set the mission selection mode.
    - !/removerecords -> Remove players all personal best/records.
    - !/removerecord -> Remove players personal best/records for a specific mission.
    - !/enablerangeban -> Enables range ban for a ban.
        - 1 = Small Range
        - 2 = Big Range
    - !/unbanrange -> Unban range.
    - !/explodeall -> Explodes everyone in server.
- Managers
    - !/(un)jailall -> To jail/unjail all players, currently logged in.
    - !/setrank / !/makeadmin -> To set player as staff member or retired staff.
    - /!mforce - /!m(next)mission -> Will set next mission, even if it's disabled. 
    - !/enableserialban -> Enables serial ban for a ban.
    - !/unbanserial -> Unban serial.
    - !/rangeban has been added. -> Range ban a player.
- Owner
    - !/reloadtitles -> Reloads all the titels in game.
    - !/addcustomtitle -> Add Custom title for a player
        - Make sure to enter hex as color code without #
        - Place, 0 for Prefix, and 1 for Suffix.
        - The title should be more than 2 words, and less than 30. More than 30 will cut off. 

### Bans
- Nick Ban
- IP Ban.
- Range Ban.
    - Small Range. e.g 127.0.0
    - Big Range e.g 127.0
- Default ban would ban players IP, and Nick.
- Unbaning an IP would unban the range as well. 
- Shortcuts for ban reasons added
    - hh = Health Hacks
    - sh = Speed Hacks
    - ab = Airbreak
    - rf = Rapid Fire
    - wh = Wall Hacks
    - sm = Superman
    - vhh = Vehicle Health Hack
    - fk = Fake kills
    - fh = Fly Hacks    
    - ai = aimbot
    - th = Troll Hacks
    - vw = Vehicle Warp
    - be = ban evading
    - adv = advertising


### Vehicles
- Players can spawn vehicles in freeroam as well.
- Remove will delete players vehicle.
- After 20 mins, if vehicles are empty those will be deleted. 

### Barrels 
- Enabled in races, chance of being enabled 1/3.
- Base price $10.
- Price goes up by twice each time a barrel is dropped.
- 35 seconds after mission starts barrels can be dropped.
- 15 seconds cool down time between barrels.
- Maximum 40 barrels are allowed in the mission.  

### XP 
- On Dropping Barrel
    - 2 XP.

### Extra
- The San Andreas theme song will stop playing after being spawned. 
- For online player commands.
    - Part of the name.
        - Can be any position i.e. for Sasuke using ke will work too.
    - ID.
    - Complete name. 
- For offline player commands.
    - Name of player complete.
    - ID of complete player.
- Missions commands.
    - ID
    - Part of name.    
- Bans
    - Name
    - Ban ID
    - IP
    - Range
    - Serial
    
