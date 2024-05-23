# KICS 4.1.2 [EliteVA]
This is an updated [VoiceAttack](https://www.voiceattack.com/) profile for the Ripley Galactic [KICS](https://github.com/mwerle/KICS) Voice Pack for Elite Dangerous by Arflint

If you already have the Ripley Galactic KICS profile audio files installed then all you need to download and import, into VoiceAttack, are the .**vap** files, you will need both the `Common.commands-Profile.vap` along with the `Ripley Galactic KICS 4.1.2 [Build 0.26] [EliteVA]-Profile.vap` files. Don't forget to include the common.commands in to the KICS profile via the profile options dialogue.

If you **DO NOT** have the Ripley Galactic KICS profile audio files installed then you should download and import, into VoiceAttack, the .**vax** file, this contains the audio files along with the VoiceAttack profile.

## Changes
See the [changes](Changes.md) file for a list of changes.

## For use with the EliteVA Plugin
This version of the KICS VA profile is for use with the EliteVA plugin, the plugin is **REQUIRED** for this profile to function.

Grab the plugin from here [EliteVA](https://github.com/Somfic/EliteVA)

All the **Key Bindings** entries have been updated to support variable keys, like so;
```
Begin Text Compare : [EliteAPI.DeployHeatSink] Has Been Set
    Press variable key(s) [EliteAPI.DeployHeatSink] and hold for 0.05 seconds and release
Else
    Write [Red] 'Missing keybind for: (The key needs to be set in game)' to log
    Write [Gray] '[Cooling - 2. Deploy Heat Sink]' to log
End Condition
```

This profile also requires the `common.commands` profile be included in to this profile, so don't forget to set that up once you have both profiles imported.

## Profile first use
Upon first use of the profile you'll be asked a series of questions, your answers will be saved so should you need to update the profile you won't need to answer the questions again.

## ED:Odyssey
This profile has support for ED:Odyssey check out the **On Foot** category in the profile.

## 3rd Party Applications
The profile now has some options to start some 3rd party apps such as CMDRs Toolbox, Inara, EDSM, EDSY, Coriolis, Spansh and if you have them installed EDDiscovery and EDMC.

## Commands ~ Selection of available commands

See the Ripley Galactic [KICS](https://github.com/mwerle/KICS) page for commands. The ones shown here are either new to the profile or have been altered in some way.

### Additional Commands:

Current Game Mode

Disembark from the ship; Disembark from the SRV

Prepare for take off;prepare to take off;prep for departure *[modified to now optionally check for limpets/crew member]*

what cargo;what cargo do I have

enter FSS;enter fss Mode

how much fuel do I have left; fuel level

### On Foot Commands: [Odyssey]

backpack consumables;backpack assets;backpack goods;backpack data;backpack transfer

open insight hub; close insight hubc

crouch;walk;sprint

hub back; hub close

hub codex

hub commander

hub contacts

hub engineer

hub fleet carrier

hub galnet news

hub navigation

hub powerplay

hub shuttle

hub squadrons

hub transactions

next weapon;previous weapon

open backpack;close backpack; show backpack

open comms; show comms; hide comms

throw grenade; grenade

toggle tool mode; tool Mode

battle stats

clear authority

flashlight on; flashlight off

genetic sampler

holster weapon

interact; use

open emote wheel

open item wheel

reload

secondary interact; alternative use

select primary weapon; select secondary weapon

select frag grenade; select emp grenade; select shield grenade

sheilds on; sheilds off

switch weapon

### Option Commands:

auto stop on; auto stop off

clear va log

crew check on; crew check off

honorific use on; honorific use off

jump count on; jump count off

limpet check on; limpet check off

scan after jump on; scan after jump off

silent mode on; silent mode off

system announce on; system announce off

va listening on; va listening off


# Notes
1. You will need to enable plugin support within VA.

	• Click the Spanner (Wrench) icon on the lower right of the VA main window, make the General tab active and check (tick) `Enable Plugin Support` on the right and then click OK. You'll need to restart VA.

2. This VA profile will **NOT** work without [EliteVA](https://github.com/Somfic/EliteVA) being installed as a plugin in VA

3. **This is a work in progress, so it will be updated.**

4. If you have any feature requests then let me know.

5. If VLC Player does **NOT** open the music playlists and instead reports an error then you should watch [this](https://www.youtube.com/watch?v=9oqCRz7CUkQ) video on how to solve the problem. Which worked for me.
