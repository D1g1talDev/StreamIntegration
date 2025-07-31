# Stream Integration
Allows your live stream chat to vote on modifiers/events to affect your game, YouTube &amp; Twitch are supported, You can also use this mod without the crowd control in the config.

## How To Setup
Go into the config, Then select what platform you want to connect to, Then follow the steps the game tells you to do.

### What The Mod Contains
- 39 Modifiers/Events, (with more to be added in the future)
- Crowd Control/Chat Control
- YouTube &amp; Twitch Support (you can do both at the same time)
- Changes to the shop terminals

### Adding Your Own Events (Not Required)
Requirement:
- ULTRAKILL Modding Knowledge (C#)

<img width="647" height="412" alt="refShot" src="https://github.com/user-attachments/assets/c97f8992-d252-415f-907c-112121d3bf58" />


- Add the .dll in the manual thunderstore download as a reference
- Add a "BepInDependency" for "com.d1g1tal.streamint" (so it doesn't break) <img width="776" height="118" alt="Screenshot 2025-07-30 152433" src="https://github.com/user-attachments/assets/91afa071-86c3-47f9-92a5-f319ae4e7907" />

- Code your event(s)
- Do "using StreamIntegration.CrowdControl"
- Call "EventManager.RegisterEvent" to add an event into the mod, Heres an example: "EventManager.RegisterEvent("My Event", MyEventsClass.PlayEvent)"


Now go into the config and go into Chat & Crowd Control, Crowd Control, then "Events (SPOILERS)"
<img width="929" height="351" alt="howtofind" src="https://github.com/user-attachments/assets/ce6d35ee-75ea-4e7e-a987-79091972880d" />

You'll find your event(s) there.

### Special Thanks
- truokyt - Made the mod icon
- Jace the ace - Additional playtesting
- PITR - For leaving his crowd control UI in the game

