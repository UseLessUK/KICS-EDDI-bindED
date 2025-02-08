# KICS 4.1.2
This is an updated [VoiceAttack](https://www.voiceattack.com/) profile for the Ripley Galactic [KICS](https://github.com/mwerle/KICS) Voice Pack for Elite Dangerous by Arflint

You'll need to grab the KICS profile from [here](https://github.com/mwerle/KICS) as you'll require the audio files, this VA profile doesn't have any included it's just the `vap` file for VA.

### Notes: Installing the KICS Profile & Audio files
After downloading and extracting the KICS Profile zip file, make sure you copy/move the `Ripley Galactic` dir **and** it's entire contents to the `VoiceAttack\Sounds\` dir. You should end up with the following dir structure;

• VoiceAttack\Sounds\Ripley Galactic

• VoiceAttack\Sounds\Ripley Galactic\KICS 4

• VoiceAttack\Sounds\Ripley Galactic\KICS 4\Audio

• VoiceAttack\Sounds\Ripley Galactic\KICS 4\Music

## For use with the EDDI + bindED Plugins
This version of the KICS VA profile is for use with the EDDI + bindED plugins, both plugins are **REQUIRED** for this profile to function.

# bindED
This updated version **requires** [bindED](https://github.com/alterNERDtive/bindED) in order to function.

All the **Key Bindings** entries have been updated to support variable keys, like so;
```
Begin Text Compare : [edDeployHeatSink] Has Been Set
    Press variable key(s) [edDeployHeatSink] and hold for 0.05 seconds and release
Else
    Write [Red] 'Missing keybind for:' to log
    Write [Gray] '[Cooling - 02. Deploy Heat Sink]' to log
End Condition
```

# EDDI
This updated version **requires** [EDDI](https://github.com/EDCD/EDDI) in order to function.

# Other profiles
This profile also requires the `common.commands` profile be included in to this profile, so don't forget to set that up once you import both profiles.

## ED:Odyssey
This profile has support for ED:Odyssey check out the **On Foot** category in the profile.

## 3rd Party Applications
The profile now has some options to start some 3rd party apps such as CMDRs Toolbox, Inara, EDSM, EDSY, Coriolis, Spansh and if you have them installed EDDiscovery and EDMC.

## Notes
1. You will need to enable plugin support within VA.

	• Click the Spanner (Wrench) icon on the lower right of the VA main window, make the General tab active and check (tick) `Enable Plugin Support` on the right and then click OK. You'll need to restart VA.

2. This VoiceAttack profile will **NOT** work without both the following plugins;

	• [bindED](https://github.com/alterNERDtive/bindED) being installed as a plugin in VoiceAttack. Also make sure you've setup keys for all the functions you wish to use in game, you will be shown an error if a keybind is missing (Red message) and the Category/Key that requires a keybind (Grey message).
	
	• [EDDI](https://github.com/EDCD/EDDI) being installed as a plugin in VoiceAttack.

3. **This is a work in progress, so it will be updated.**

	• Note: Work on this has been stopped for now, real life kind of got in the way along with working on the EliteVA profile.

4. If you have any feature requests then let me know.
