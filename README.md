# Spawns config

This cs2 config adds balloon entities on the spawn locations of all 14 competitive map.

If you interact with a balloon (shoot at it, knife it, or press your use-key), you get teleported to that spawn position - similar to the feature in refrag.

![20C3E9~1](https://github.com/user-attachments/assets/459d9d45-9d12-4737-ad49-326c60dec97d)

### Visualization of the balloons:

🟥 No insta lineup from that spawn possible

🟨 Unknown. Insta lineups could be possible, but not widely spread.

🟩 A well known insta lineup exists for this spawn

🟦 This map is not supported. Automatically generated balloon

Definition insta lineup: A lineup that is performed directly from a spawn location. Only one movement key (WASD) can be pressed, a sequence of multiple movement keys doesn't count.

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

### Unsupported map
On unsupported maps the config automatically generates blue balloons for all spawn positions (including casual & wingman spawns).

Add this to your launch options, otherwise the balloons won't work on workshop maps:
```-disable_workshop_command_filtering```

<img width="1440" height="1080" alt="image" src="https://github.com/user-attachments/assets/a637ac31-5512-4018-8c48-2d50efb1274b" />


# Installation 
1. Download the config
2. Place the ```spawns``` folder in your ```Counter-Strike Global Offensive\game\csgo\cfg```-directory
3. Edit the ```main.cfg``` in the spawns folder. Change your ```toggleSpawns```-key (default: F3)
4. Add ```exec spawns/main``` to your autoexec.
5. Join a competitive map in practice mode.
6. Press ```F3 / your toggleSpawns-key``` to toggle the spawn balloons on/off.
7. Interact with a balloon to tp to that spawn position

The config automatically detects which map you are on and loads the correct spawn balloons accordingly.

