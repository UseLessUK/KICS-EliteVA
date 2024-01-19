# KICS 4.1.2 [EliteVA]
This is an updated [VoiceAttack](https://www.voiceattack.com/) profile for the Ripley Galactic [KICS](https://github.com/mwerle/KICS) Voice Pack for Elite Dangerous by Arflint

You'll need to grab the KICS profile from [here](https://github.com/mwerle/KICS) as you'll require the audio files, this VA profile doesn't have any included it's just the `vap` file for VA.

## For use with the EliteVA Plugin
This version of the KICS VA profile is for use with the EliteVA plugin, the plugin is **REQUIRED** for this profile to function.

Grab the plugin from here [EliteVA](https://github.com/Somfic/EliteVA)

All the **Key Bindings** entries have been updated to support variable keys, like so;
```
Begin Text Compare : [EliteAPI.ToggleButtonUpInput] Has Been Set
    Press variable key(s) [EliteAPI.ToggleButtonUpInput] and hold for 0.05 seconds and release
Else
    Write [Red] 'Missing keybind for:' to log
    Write [Gray] '[Cooling - 1. Silent Running]' to log
End Condition
```

This profile also requires the `common.commands` profile be included in to this profile, so don't forget to set that up once you import both profiles.

## ED:Odyssey
This profile has support for ED:Odyssey check out the **On Foot** category in the profile.

## 3rd Party Applications
The profile now has some options to start some 3rd party apps such as CMDRs Toolbox, Inara, EDSM, EDSY, Coriolis, Spansh and if you have them installed EDDiscovery and EDMC.

## Notes
1. You will need to enable plugin support within VA.

	• Click the Spanner (Wrench) icon on the lower right of the VA main window, make the General tab active and check (tick) `Enable Plugin Support` on the right and then click OK. You'll need to restart VA.

2. This VA profile will **NOT** work without [EliteVA](https://github.com/Somfic/EliteVA) being installed as a plugin in VA

3. **This is a work in progress, so it will be updated.**

4. If you have any feature requests then let me know.
