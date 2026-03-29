# Spawns config

This config adds balloon entities on the spawn location of every competitive map.

If you interact with an balloon (shoot at it, knife it, or press your use-key), you get teleported to that spawn position - similar to the feature in refrag.

![20C3E9~1](https://github.com/user-attachments/assets/459d9d45-9d12-4737-ad49-326c60dec97d)

### Visualization of the balloons:

🟥 No insta lineup from that spawn possible

🟨 Unknown. Insta lineups could be possible, but not widely spread.

🟩 A well known insta lineup exists for this spawn

Definition insta lineup: A lineup that is perfomed directly from a spawn location. Only one movement key (WASD) can be pressed, a sequence of multiple movement keys doesn't count.

### Supported maps:
- de_mirage
- de_inferno
- de_nuke
- de_overpass
- de_ancient
- de_anubis
- de_dust2
- de_train
- de_warden
- de_vertigo
- de_stronghold
- cs_italy
- cs_office
- cs_alpine

# Installation 
1. Download the config
2. Place the ```spawns``` folder in your ```Counter-Strike Global Offensive\game\csgo\cfg```-directory
3. Edit the ```main.cfg``` in the spawns folder. Change your ```toggleSpawns```-key (default: F3)
4. Add ```exec spawns/main``` to your autoexec.
5. Join a competitive map in practice mode.
6. Press ```F3``` (your toggleSpawns-key) to toggle the spawn balloons on/off.
7. Interact with a balloon to tp to that spawn position

The config automatically detects which map you are on and loads the correct spawn balloons accordingly.

