# Legacy-Town-Of-Us-Among-Us-v2021.6.30s-

![image alt](https://github.com/ryszarddev/Legacy-Town-Of-Us-Among-Us-v2021.6.30s-/blob/main/Images/toulogo.png?raw=true)


## *Note: This repository is an unofficial repository of Town of Us! For support join https://discord.gg/gH47VYGJ2E*
## *2nd Note: This project is not being actively worked on right now for more information join the discord server!*

Current game version : v2021.6.30 (This might change!)

!! TO PLAY YOU NEED TO DOWNLOAD RADMIN VPN AND HAVE STEAM OPEN.

Currently you can't change your username caused by 480 steam appid to allow players that don't own the game to play! (This might change!)

How to download:
1. Click releases on the github page.
2. Download the newest one.
3. Make sure you have WinRAR or 7zip installed.
4. Extract the file
5. Open Among Us.exe and wait for it to finish loading
6. Done!

How to play online:
1. Download Radmin VPN (https://www.radmin-vpn.com)
2. Connect to the network your host has shared
3. Open Among Us.exe
4. Open Local Tab
5. Connect to the gameserver (Same name as the host's nickname)
6. Done!

How to host a game:
1. Download Radmin VPN (https://www.radmin-vpn.com)
2. Create a network
3. Host the game using the local tab. (Online doesn't work caused by outdated version)
4. Share the network name and password to the players
5. Done!


-----------------------
# Roles
# Crewmate Roles

![image alt](https://github.com/ryszarddev/Legacy-Town-Of-Us-Among-Us-v2021.6.30s-/blob/main/Images/CrewRoles.png?raw=true)

## Haunter
### **Team: Crewmates**

The Haunter is a dead Crewmate that can reveal Impostors if they finish all their tasks.\
Upon finishing all of their tasks, Impostors are revealed to alive crewmates after a meeting is called.\
However, if the Haunter is clicked they lose their ability to reveal Impostors and are once again a normal ghost.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Haunter | The percentage probability of the Haunter appearing | Percentage | 0% |
| When Haunter Can Be Clicked | The amount of tasks remaining when the Haunter Can Be Clicked | Number | 5 |
| Haunter Alert | The amount of tasks remaining when the Impostors are alreted that the Haunter is nearly finished | Number | 1 |
| Haunter Reveals Neutral Roles | Whether the Haunter also Reveals Neutral Roles | Toggle | False |
| Who can Click Haunter | Whether even other Crewmates can click the Haunter | All / Non-Crew / Imps Only | All |

-----------------------
## Investigator
### **Team: Crewmates**
The Investigator is a Crewmate that can see the footprints of players.\
Every footprint disappears after a set amount of time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Investigator | The percentage probability of the Investigator appearing | Percentage | 0% |
| Footprint Size | The size of the footprint on a scale of 1 to 10 | Number | 4 |
| Footprint Interval | The time interval between two footprints | Time | 0.1s |
| Footprint Duration | The amount of time that the footprint stays on the ground for | Time | 10s |
| Anonymous Footprint | When enabled, all footprints are grey instead of the player's colors | Toggle | False
| Footprint Vent Visible | Whether footprints near vents are shown | Toggle | False

-----------------------
## Seer
### **Team: Crewmates**
The Seer is a Crewmate that can reveal the alliance of other players.\
Based on settings, the Seer can find out whether a role is Good or Evil.\
A player's name will change color to their team.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Seer | The percentage probability of the Seer appearing | Percentage | 0% |
| Seer Cooldown | The Cooldown of the Seer's Reveal button | Time | 25s |
| Crewmate Killing show up as Evil | Crewmate Killing roles show up as Red | Toggle | False |
| Neutral Benign show up as Evil | Neutral Benign roles show up as Red | Toggle | False |
| Neutral Evil show up as Evil | Neutral Evil roles show up as Red | Toggle | False |
| Neutral Killing show up as Evil | Neutral Killing roles show up as Red | Toggle | False |

-----------------------
## Snitch
### **Team: Crewmates**

The Snitch is a Crewmate that can get arrows pointing towards the Impostors, once all their tasks are finished.\
The names of the Impostors will also show up as red on their screen.\
Based on game settings, the Snitch may not know who they are until they have one task left.\
However, when they only have a single task left, the Impostors get an arrow pointing towards the Snitch.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Snitch | The percentage probability of the Snitch appearing | Percentage | 0% |
| Snitch knows who they are on Game Start | Whether the Snitch knows their role at the start of a game | Toggle | False |
| Snitch Sees Neutral Roles | Whether the Snitch also Reveals Neutral Roles | Toggle | False |
| Tasks Remaining When Revealed | The number of tasks remaining when the Snitch is revealed to Impostors | Number | 1 |
| Snitch Sees Impostors in Meetings | Whether the Snitch sees the Impostor's names red in Meetings | Toggle | True |

-----------------------
## Spy
### **Team: Crewmates**

The Spy is a Crewmate that gains more information when on Admin Table and Vitals.\
On Admin Table, the Spy can see the colors of every person on the map.\
On Vitals, the Spy can see how long killed bodies have been dead for.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Spy | The percentage probability of the Spy appearing | Percentage | 0% |

-----------------------
## Tracker
### **Team: Crewmates**

The Tracker is a Crewmate that can track other players by tracking them during a round.\
Once they track someone, an arrow is continuously pointing to them, which updates in set intervals.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Tracker | The percentage probability of the Tracker appearing | Percentage | 0% |
| Arrow Update Interval | The time it takes for the arrow to update to the new location of the tracked player | Time | 5s |
| Track Cooldown | The cooldown on the Tracker's track button | Time | 25s |
| Tracker Arrows Reset Each Round | Whether Tracker Arrows are removed after each meeting | Toggle | False |
| Maximum Number of Tracks Per Round | The number of new people they can track each round | Number | 3 |

-----------------------
## Sheriff
### **Team: Crewmates**
The Sheriff is a Crewmate that has the ability to eliminate the Impostors using their kill button.\
However, if they kill a Crewmate or a Neutral player they can't kill, they instead die themselves.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Sheriff | The percentage probability of the Sheriff appearing | Percentage | 0% |
| Sheriff Miskill Kills Crewmate | Whether the other player is killed if the Sheriff Misfires | Toggle | False |
| Sheriff Kills Jester | Whether the Sheriff is able to kill the Jester | Toggle | False |
| Sheriff Kills The Glitch | Whether the Sheriff is able to kill The Glitch | Toggle | False |
| Sheriff Kills Executioner | Whether the Sheriff is able to kill the Executioner | Toggle | False |
| Sheriff Kills Arsonist | Whether the Sheriff is able to kill the Arsonist | Toggle | False |
| Sheriff Kill Cooldown | The cooldown on the Sheriff's kill button | Time | 25s |
| Sheriff can report who they've killed | Whether the Sheriff is able to report their own kills | Toggle | True |

-----------------------
## Veteran
### **Team: Crewmates**

The Veteran is a Crewmate that can go on alert.\
When the Veteran is on alert, anyone, whether crew, neutral or impostor, if they interact with the Veteran, they die.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Veteran | The percentage probability of the Veteran appearing | Percentage | 0% |
| Can Be Killed On Alert | Whether the Veteran dies when someone tries to kill them when they're on alert | Toggle | False |
| Alert Cooldown | The cooldown on the Veteran's alert button. | Time | 5s |
| Alert Duration | The duration of the alert | Time | 25s |
| Maximum Number of Alerts | The number of times the Veteran can alert throughout the game | Number | 3 |

-----------------------
## Vigilante
### **Team: Crewmates**

The Vigilante is a Crewmate that can kill during meetings.\
During meetings, the Vigilante can choose to kill someone by guessing their role, however, if they guess incorrectly, they die instead.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Vigilante | The percentage probability of the Vigilante appearing | Percentage | 0% |
| Vigilante Kill | The number of kill the Vigilante can do with his ability | Number | 1 |
| Vigilante Guess Neutral  | Whether the Vigilante can Guess Neutral roles | Toggle | False |
| Vigilante Multiple Kill  | Whether the Vigilante can kill more than once per meeting | Toggle | False |

-----------------------
## Altruist
### **Team: Crewmates**

The Altruist is a Crewmate that is capable of reviving dead players.\
Upon finding a dead body, the Altruist can hit their revive button, risking sacrificing themselves for the revival of another player.\
If enabled, the dead body disappears, so only they Altruist's body remains at the scene.\
After a set period of time, the player will be resurrected, if the revival isn't interrupted.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Altruist | The percentage probability of the Altruist appearing | Percentage | 0% |
| Altruist Revive Duration | The time it takes for the Altruist to revive a dead body | Time | 10s |
| Target's body disappears on beginning of revive | Whether the dead body of the player the Altruist is reviving disappears upon revival | Toggle | False |

-----------------------
## Medic
### **Team: Crewmates**
The Medic is a Crewmate that can give any player a shield that will make them immortal until the Medic dies.\
A Shielded player cannot be Shifted into, Hacked or Killed by anyone, unless by suicide.\
If the Medic reports a dead body, they can get a report containing clues to the Killer's identity.\
A report can contain the name of the killer or the color type (Darker/Lighter)
### Colors
- Red - Darker
- Blue - Darker
- Green - Darker
- Pink - Lighter
- Orange - Lighter
- Yellow - Lighter
- Black - Darker
- White - Lighter
- Purple - Darker
- Brown - Darker
- Cyan - Lighter
- Lime - Lighter
- Maroon - Darker
- Rose - Lighter
- Banana - Lighter
- Gray - Darker
- Tan - Darker
- Coral - Lighter
- Watermelon - Darker
- Chocolate - Darker
- Sky Blue - Lighter
- Beige - Darker
- Hot Pink - Lighter
- Turquoise - Lighter
- Lilac - Lighter
- Olive - Darker
- Azure - Lighter
- Rainbow - Lighter

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Medic | The percentage probability of the Medic appearing | Percentage | 0% |
| Show Shielded Player | Who should be able to see who is Shielded | Self / Medic / Self + Medic / Everyone | Self |
| Show Medic Reports | Whether the Medic should get information when reporting a body | Toggle | True |
| Time Where Medic Reports Will Have Name | If a body has been dead for shorter than this amount, the Medic's report will contain the killer's name | Time | 0s |
| Time Where Medic Reports Will Have Color Type | If a body has been dead for shorter than this amount, the Medic's report will have the type of color | Time | 15s |
| Who gets murder attempt indicator | Who will receive an indicator when someone tries to Shift into, Hack or Kill them | Medic / Shielded / Everyone / Nobody | Medic |
| Shield breaks on murder attempt | Whether the Shield breaks when someone attempts to Shift into, Hack or Kill them | Toggle | False |

-----------------------
## Engineer
### **Team: Crewmates**
The Engineer is a Crewmate that can fix sabotages from anywhere on the map.\
They can use vents to get across the map easily.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Engineer | The percentage probability of the Engineer appearing | Percentage | 0% |
| Engineer Fix Per | Whether the Engineer can fix 1 sabotage per round or per game | Round / Game | Round |

-----------------------
## Mayor
### **Team: Crewmates**
The Mayor is a Crewmate that can vote multiple times.\
The Mayor has a Vote Bank, which is the number of times they can vote.\
They have the option to abstain their vote during a meeting, adding that vote to the Vote Bank.\
As long as not everyone has voted, the Mayor can use as many votes from their Vote Bank as they please.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Mayor | The percentage probability of the Mayor appearing | Percentage | 0% |
| Initial Mayor Vote Bank | The number of votes in the Vote Bank at the start of a game | Number | 1 |
| Mayor Votes Show Anonymous | Whether the Mayor's extra votes will show up anonymously | Toggle | False |
| Mayor Can Button | Whether the Mayor Can Press the Button | Toggle | True |

-----------------------
## Swapper
### **Team: Crewmates**
The Swapper is a Crewmate that can swap the votes on 2 players during a meeting.\
All the votes for the first player will instead be counted towards the second player and vice versa.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Swapper | The percentage probability of the Swapper appearing | Percentage | 0% |
| Swapper Can Button | Whether the Swapper Can Press the Button | Toggle | True |

-----------------------
## Time Lord
### **Team: Crewmates**
The Time Lord is a Crewmate that can rewind time and reverse the positions of all players.\
If enabled, any players killed during this time will be revived.\
Nothing but movements and kills are affected.\
If enabled, the Time Lord can't use Vitals to make things more balanced.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Time Lord | The percentage probability of the Time Lord appearing | Percentage | 0% |
| Revive During Rewind | Whether the Time Lord revives dead players when rewinding | Toggle | False |
| Rewind Duration | How far the rewind goes back in time | Time | 2s |
| Rewind Cooldown | The cooldown of the Time Lord's Rewind button | Time | 25s |
| Max Uses | The amount of times the Rewind ability can be used | Number | 5 |
| Time Lord can use Vitals | Whether the Time Lord has the ability to use Vitals | Toggle | False |

-----------------------
## Transporter
### **Team: Crewmates**
The Transporter is a Crewmate that can change the locations of two random players at will.\
Players who have been transported are alerted with a blue flash on their screen.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Transporter | The percentage probability of the Transporter appearing | Percentage | 0% |
| Transport Cooldown | The cooldown of the Transporter's transport ability | Time | 25s |
| Max Uses | The amount of times the Transport ability can be used | Number | 5 |
| Transporter can use Vitals | Whether the Transporter has the ability to use Vitals | Toggle | False |

-----------------------
# Neutral Roles

![image alt](https://github.com/ryszarddev/Legacy-Town-Of-Us-Among-Us-v2021.6.30s-/blob/main/Images/NeutralRoles.png?raw=true)

## Amnesiac
### **Team: Neutral**
The amnesiac is a Neutral role with no win condition.\
They have zero tasks and are essentially roleless.\
However, they can remember a role by finding a dead player.\
Once they remember their role, they go on to try win with their new win condition.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Amnesiac | The percentage probability of the Amnesiac appearing | Percentage | 0% |
| Amnesiac Gets Arrows | Whether the Amnesiac has arrows pointing to dead bodies | Toggle | False |
| Arrow Appear Delay | The delay of the arrows appearing after the person died | Time | 5s |

-----------------------
## Jester
### **Team: Neutral**
The Jester is a Neutral role with its own win condition.\
If they are voted out after a meeting, the game finishes and they win.\
However, the Jester does not win if the Crewmates, Impostors or another Neutral role wins.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Jester | The percentage probability of the Jester appearing | Percentage | 0% |
| Jester Can Button | Whether the Jester Can Press the Button | Toggle | True |
| Jester Can Vent | Whether the Jester Can Vent | Toggle | False |

-----------------------
## Executioner
### **Team: Neutral**

The Executioner is a Neutral role with its own win condition.\
Their goal is to vote out a player, specified in the beginning of a game.\
If that player gets voted out, they win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Executioner | The percentage probability of the Executioner appearing | Percentage | 0% |
| Executioner becomes on Target Dead | Which role the Executioner becomes when their target dies | Crewmate / Jester / Amnesiac | Crewmate |
| Executioner Can Button | Whether the Executioner Can Press the Button | Toggle | True |

-----------------------
## Phantom
### **Team: Neutral**

The Phantom is a Neutral role with its own win condition.\
They become half-invisible when they die and has to complete all their tasks without getting caught.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Phantom | The percentage probability of the Phantom appearing | Percentage | 0% |
| When Phantom Can Be Clicked | The amount of tasks remaining when the Phantom Can Be Clicked | Number | 5 |

-----------------------
## Arsonist
### **Team: Neutral**

The Arsonist is a Neutral role with its own win condition.\
They have the ability to douse other players with gasoline.\
Once they have doused every player remaining, they can Ignite everyone at once.\
Upon Igniting every player, they win the game.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Arsonist | The percentage probability of the Arsonist appearing | Percentage | 0% |
| Douse Cooldown | The cooldown of the Arsonist's Douse button | Time | 25s |
| Game keeps going so long as Arsonist is alive | Whether the game keeps going while the Arsonist remains | Toggle | False |
| Arsonist Can Button | Whether the Arsonist Can Press the Button | Toggle | True |

-----------------------
## The Glitch
### **Team: Neutral**

The Glitch is a Neutral role with its own win condition.\
The Glitch's aim is to kill __everyone__ and be the last person standing.\
The Glitch can Hack players, resulting in them being unable to report bodies and do tasks.\
Hacking prevents the hacked player from doing anything but walk around the map.\
The Glitch can Mimic someone, which results in them looking exactly like the other person.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| The Glitch | The percentage probability of The Glitch appearing | Percentage | 0% |
| Mimic Cooldown | The cooldown of The Glitch's Mimic button | Time | 30s |
| Mimic Duration | How long The Glitch can Mimic a player | Time | 10s |
| Hack Cooldown | The cooldown of The Glitch's Hack button | Time | 30s |
| Hack Duration | How long The Glitch can Hack a player | Time | 10s |
| Glitch Kill Cooldown | The cooldown of the Glitch's Kill button | Time | 30s |
| Glitch Hack Distance | How far away The Glitch can Hack someone from | Short / Normal / Long | Short |
| Glitch can Vent | Whether the Glitch can Vent | Toggle | False |

-----------------------
# Impostor Roles

![image alt](https://github.com/ryszarddev/Legacy-Town-Of-Us-Among-Us-v2021.6.30s-/blob/main/Images/ImpRoles.png?raw=true)

## Camouflager
### **Team: Impostors**

The Camouflager is an Impostor that can turn everyone into colorless characters.\
Everyone then goes grey for a certain period of time, along with their names disappearing, making them become unrecognizable.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Camouflager | The percentage probability of the Camouflager appearing | Percentage | 0% |
| Camouflage Cooldown | The cooldown of the Camouflager's Camouflage button | Time | 25s |
| Camouflage Duration | How long the Camouflage lasts for | Time | 10s |

-----------------------
## Grenadier
### **Team: Impostors**

The Grenadier is an Impostor that can throw smoke grenades.\
During the game, the Grenadier has the option to throw down a smoke grenade which blinds crewmates so they can't see.\
However, a sabotage and a smoke grenade can not be active at the same time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Grenadier | The percentage probability of the Grenadier appearing | Percentage | 0% |
| Flash Grenade Cooldown | The cooldown of the Grenadier's Flash button | Time | 25s |
| Flash Grenade Duration | How long the Flash Grenade lasts for | Time | 10s |
| Grenadier can Vent | Whether the Grenadier can Vent | Toggle | False |
-----------------------
## Morphling
### **Team: Impostors**

The Morphling is an Impostor that can Morph into another player.\
At the beginning of the game and after every meeting, they can choose someone to Sample.\
They can then Morph into that person at any time for a limited amount of time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Morphling | The percentage probability of the Morphling appearing | Percentage | 0% |
| Morph Cooldown | The cooldown of the Morphling's Morph button | Time | 25s |
| Morph Duration | How long the Morph lasts for | Time | 10s |
| Morphling can Vent | Whether the Morphling can Vent | Toggle | False |

-----------------------
## Swooper
### **Team: Impostors**

The Swooper is an Impostor that can temporarily turn invisible.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Swooper | The percentage probability of the Swooper appearing | Percentage | 0% |
| Swooper Cooldown | The cooldown of the Swooper's Swoop button | Time | 25s |
| Swooper Duration | How long the Swooping lasts for | Time | 10s |
| Swooper can Vent | Whether the Swooper can Vent | Toggle | False |

-----------------------
## Poisoner
### **Team: Impostors**

The Poisoner is an Impostor who has to poison another play instead of kill.\
When they poison a player, the poisoned player dies either upon the start of the next meeting or after a set duration.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Poisoner | The percentage probability of the Poisoner appearing | Percentage | 0% |
| Poison Cooldown | The cooldown of the Poisoner's Poison button | Time | 25s |
| Poison Kill Delay | The delay of the kill after being poisoned | Time | 5s |
| Poisoner can Vent | Whether the Poisoner can Vent | Toggle | False |

-----------------------
## Traitor
### **Team: Impostors**

If all Impostors die before a certain point in the game, a random crewmate is selected to become the Traitor.\
The Traitor has no additional abilities and their job is simply to avenge the dead Impostors.\
Once this player has turned into the Traitor their alliance sits with the Impostors.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Traitor | The percentage probability of the Traitor appearing | Percentage | 0% |
| Latest Spawn | The minimum number of people alive when a Traitor can spawn | Number | 5 |

-----------------------
## Underdog
### **Team: Impostors**

The Underdog is an Impostor with a prolonged kill cooldown.\
When they are the only remaining Impostor, they will have their kill cooldown shortened.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Underdog | The percentage probability of the Underdog appearing | Percentage | 0% |
| Kill Cooldown Bonus | The amount of time added or removed from the Underdog's Kill Cooldown | Time | 5s |
| Increased Kill Cooldown  | Whether the Underdog's Kill Cooldown is Increased when 2+ Imps are alive | Toggle | True |

-----------------------
## Janitor
### **Team: Impostors**
The Janitor is an Impostor that can clean up bodies.\
Both their Kill and Clean ability have a shared cooldown, meaning they have to choose which one they want to use.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Janitor | The percentage probability of the Janitor appearing | Percentage | 0% |

-----------------------
## Miner
### **Team: Impostors**

The Miner is an Impostor that can create new vents.\
These vents only connect to each other, forming a new passway.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Miner | The percentage probability of the Miner appearing | Percentage | 0% |
| Mine Cooldown | The cooldown of the Miner's Mine button | Time | 25s |

-----------------------
## Undertaker
### **Team: Impostors**

The Undertaker is an Impostor that can drag and drop bodies.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Undertaker | The percentage probability of the Undertaker appearing | Percentage | 0% |
| Undertaker Drag Cooldown | The cooldown of the Undertaker Drag ability | Time | 25s |
| Undertaker can Vent | Whether the Undertaker can Vent | Toggle | False |
| Undertaker can Vent while Dragging | Whether the Undertaker can Vent when they are Dragging a Body | Toggle | False |

-----------------------

# Modifiers
Modifiers are added on top of players' roles.
## Bait
### **Applied to: Crewmates**
Killing the Bait makes the killer auto self-report.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Bait | The percentage probability of the Bait appearing | Percentage | 0% |

-----------------------
## Diseased
### **Applied to: Crewmates**
Killing the Diseased triples the killer's Kill cooldown.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Diseased | The percentage probability of the Diseased appearing | Percentage | 0% |

-----------------------
## Torch
### **Applied to: Crewmates**
The Torch's vision doesn't get reduced when the lights are sabotaged.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Torch | The percentage probability of the Torch appearing | Percentage | 0% |

-----------------------
## Button Barry
### **Applied to: All**
Button Barry has the ability to call a meeting from anywhere on the map, even during sabotages.
They have the same amount of meetings as a regular player.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Button Barry | The percentage probability of Button Barry appearing | Percentage | 0% |

-----------------------
## Drunk
### **Applied to: All**
The Drunk's controls are inverted.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Drunk | The percentage probability of the Drunk appearing | Percentage | 0% |

-----------------------
## Flash
### **Applied to: All**
The Flash travels at twice the speed of a normal player.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Flash | The percentage probability of the Flash appearing | Percentage | 0% |

-----------------------
## Giant
### **Applied to: All**
The Giant is a gigantic Crewmate, that has a decreased walk speed.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Giant | The percentage probability of the Giant appearing | Percentage | 0% |

-----------------------
## Lovers
### **Applied to All**
The Lovers are two players who are linked together.\
These two players get picked randomly between Crewmates and Impostors.\
They gain the primary objective to stay alive together.\
If they are both among the last 3 players, they win.\
In order to so, they gain access to a private chat, only visible by them in between meetings.\
However, they can also win with their respective team, hence why the Lovers do not know the role of the other lover.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Lovers | The percentage probability of the Lovers appearing | Percentage | 0% |
| Both Lovers Die | Whether the other Lover automatically dies if the other does | Toggle | True |
| Loving Impostor Probability | The chances of one lover being an Impostor | Percentage | 20% |
| Neutral Roles Can Be Lovers | Whether a Lover can be a Neutral Role | Toggle | True |

-----------------------
## Sleuth
### **Applied to: All**
The Sleuth is a crewmate who gains knowledge from reporting dead bodies.\
During meetings the Sleuth can see the roles of all players in which they've reported.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Sleuth | The percentage probability of the Sleuth appearing | Percentage | 0% |

-----------------------
## Tiebreaker
### **Applied to: All**
If any vote is a draw, the Tiebreaker's vote will go through.\
If they voted another player, they will get voted out.\
If the Tiebreaker is the Mayor, it applies to the Mayor's __first__ vote.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Tiebreaker | The percentage probability of the Tiebreaker appearing | Percentage | 0% |

-----------------------
# Custom Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Camouflaged Comms | Whether everyone becomes camouflaged when Comms are sabotaged | Toggle | False |
| Camouflaged Meetings | Whether everyone is camouflaged during meetings while Comms are sabotaged | Toggle | False |
| Impostors can see the roles of their team | Whether Impostors are able to see which Impostor roles their teammates have | Toggle | False |
| Dead can see everyone's roles and Votes | Whether dead players are able to see the roles and votes of everyone else | Toggle | False |
| Max Neutral Roles | The maximum number of Neutral roles a game can have | Number | 1 |
| Probability of a completely vanilla game | The percentage probability of a vanilla Among Us game happening | Percentage | 0% |
| Game Start Cooldowns | The cooldown for all roles at the start of the game (excluding Impostor's Kill Cooldown) | Time | 10s |
| Parallel Medbay Scans | Whether players have to wait for others to scan | Toggle | False |
| Disable Level Icons | Whether all level icons are removed in meetings | Toggle | False |
| Disable Player Nameplates | Whether all decorative nameplates are disabled in meetings | Toggle | False |

-----------------------
# Task Tracking Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| See Tasks During Round | Whether people see their tasks update in game | Toggle | False |
| See Tasks During Meetings | Whether people see their task count during meetings | Toggle | False |
| See Tasks When Dead | Whether people see everyone's tasks when they're dead | Toggle | False |

-----------------------
## Assassin Ability
### **Team: Impostors**

The Assassin Ability is given to a certain number of Impostors.\
This ability gives the Impostors a chance to kill during meetings by guessing the role of non-Impostors.\
If they guessed wrong, they die instead.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Number of Assassins | How many Impostors can Assassinate | Number | 1 |
| Amnesiac Turned Impostor Can Assassinate | Whether former Amnesiacs now Impostor can Assassinate | Toggle | False |
| Traitor Can Assassinate | If someone turns into a Traitor they can Assassinate | Toggle | False |
| Assassin Kill | The number of kill the Assassin can do with his ability | Number | 1 |
| Assassin Guess Crewmate | Whether the Assassin can Guess "Crewmate" | Toggle | False |
| Assassin Guess Neutral  | Whether the Assassin can Guess Neutral roles | Toggle | False |
| Assassin Multiple Kill  | Whether the Assassin can kill more than once per meeting | Toggle | False |
| Assassinate Snitch via Crewmate Guess  | Whether the Assassin can kill the Snitch by Guessing Crewmate | Toggle | False |

-----------------------
# Extras
## New Colors!
New colors are added for crewmates to pick from: watermelon, chocolate, sky blue, beige, hot pink, turquoise and lilac.
## Rainbow Color!
A rainbow color has also been added. Anyone who equips this color will constantly switch between the colors of the rainbow.
## Custom Hats!
Custom hats have been added, made by some very talented artists. These are mostly hats for streamers.

-----------------------
# Bug / Suggestions
If you have any bugs or any need to contact me, join the [Discord Server](https://discord.gg/ugyc4EVUYZ) or create a ticket on GitHub.

-----------------------
# Credits & Resources
[Reactor](https://github.com/NuclearPowered/Reactor) - The framework of the mod\
[BepInEx](https://github.com/BepInEx) - For hooking game functions\
[Among-Us-Sheriff-Mod](https://github.com/Woodi-dev/Among-Us-Sheriff-Mod) - For the Sheriff role.\
[Among-Us-Love-Couple-Mod](https://github.com/Woodi-dev/Among-Us-Love-Couple-Mod) - For the inspiration of Lovers role.\
[ExtraRolesAmongUs](https://github.com/NotHunter101/ExtraRolesAmongUs) - For the Engineer & Medic roles.\
[TooManyRolesMods](https://github.com/Hardel-DW/TooManyRolesMods) - For the Investigator & Time Lord roles.\
[TorchMod](https://github.com/tomozbot/TorchMod) - For the inspiration of the Torch modifier.\
[XtraCube](https://github.com/XtraCube) - For the RainbowMod.\
[PhasmoFireGod](https://twitch.tv/PhasmoFireGod) and [Ophidian](https://www.instagram.com/ixean.studio) - Button Art.\
[TheOtherRoles](https://github.com/Eisbison/TheOtherRoles) - For the inspiration of the Vigilante, Tracker and Spy roles, as well as the Bait modifier.\
[5up](https://www.twitch.tv/5uppp) and the Submarine Team - For the inspiration of the Grenadier role.\
[Guus](https://github.com/OhMyGuus) - For support for the new Among Us versions (v2021.11.9.5 and v2021.12.15).\
[ItsTheNumberH](https://github.com/itsTheNumberH/Town-Of-H) - For the code used for Bait, Poisoner and partially for Tracker.\
[Ruiner](https://github.com/ruiner189/Town-Of-Us-Redux) - For lovers changed into a modifier and Task Tracking.\
[Term](https://github.com/ImTerm/Town-Of-Us-R) - For porting v2.5.0 to the new Among Us version (v2021.12.15).

[Essentials](https://github.com/DorCoMaNdO/Reactor-Essentials) - For created custom game options.\
v1.0.3 uses [Essentials](https://github.com/DorCoMaNdO/Reactor-Essentials) directly.\
v1.1.0 uses a modified version of Essentials that can be found [here](https://github.com/slushiegoose/Reactor-Essentials).\
v1.2.0 has Essentials embedded and can be found [here](https://github.com/slushiegoose/Town-Of-Us/tree/master/source/Patches/CustomOption).

#
<p align="center">This mod is not affiliated with Among Us or Innersloth LLC, and the content contained therein is not endorsed or otherwise sponsored by Innersloth LLC. Portions of the materials contained herein are property of Innersloth LLC.</p>
<p align="center">© Innersloth LLC.</p>
