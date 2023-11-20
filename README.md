![image](https://github.com/Xeify0/dbm-rawdata/assets/29692306/dbdfd182-c75d-49b3-b601-965974565449)
# Xeify's Raw Data for Discord Bot Maker
#### If you like this resource please consider **staring it** :) 
#### If you're feeling generous you can donate here: https://buy.stripe.com/9AQcQg4Ev2uCeA0144
> I've created this github to include any missing information, and give back to the community.
> If you were linked here odds are you should be reading the information below.

<p align="left">
<img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="Xeify#9155" height="30" width="40" /></a> For support join our discord: https://discord.gg/W3jWWdDWsx
</p>


> [!NOTE]
> The music system is synced together, and requires each other to work. Utilize each commmand/event or configure it properly to make it work.
>
> AN API KEY IS REQUIRED FOR THE PLAY COMMAND TO WORK PROPERLY
> 
> Create an api key here: https://console.cloud.google.com/apis/library/youtube.googleapis.com?authuser=1&project=nobis-hosting and replace the key already in the command.

### Changelog 11/18/23

↦ Added music events/commands I've created. 

↦ Added utility commands/events.

#### **Commands added**
- `Play Music/Playlist command`
  - Plays the specificed song through youtube search & has functionality for playlists
     > This command has a prerequisite event [[Event] Disconnect-Kick](https://github.com/Xeify0/dbm-rawdata/blob/main/Music%20System%20v1/Events/%5BEvent%5D%20Disconnect-Kick.txt).
<!-- Commands below this are not exactly required. Besides pause&resume. -->
- `Volume command`
  - Changes the volume that the bot plays audio at.
- `Join VC command`
  - Forces the bot to join the voice channel you're connected to.
- `Stop playing command`
  - Can be used if the bot is not playing music correctly or there is an error.
  - DM me if there's any issue
- `Resume & Pause command`
   - Can be used to pause, and resume the current track.
- `Queue Command`
  - Lists the current songs in the queue, and the current song playing.
  - **WARNING
- `Skip Command`
  - Skips the current song.
- `Loop Command`
  - Enables the option to loop the queue, track, or autoplays music. Options can be disabled simply by removing the choice in the slash parameters.
- `Shuffle Command`
  - Shuffles the queue randomly.
 #### **Events added**
 
 - `Event Disconnect-Kick`
   - On bot disconnect or kick from server stop instance from playing audio. Fixes audio not playing afterwards. Requirement for play command.
 - `Event Music Resume`
   - Event required for pause/resume command. Simply sets a variable to 0 or 1 based on info.

## Last bits of information
Ranked Network [^1].
Mods [^2].
Future Progress [^3].
[^1]: Queue/play command: https://prnt.sc/glNGSwahe0Kg
[^2]: The music command is setup using the [play music mod](https://github.com/dbm-network/mods).
[^3]: I plan on adding more commands I create/created. DM me if you have any ideas for things to create. Discord: Xeify 
