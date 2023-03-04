# Kerbal Attachment System (KAS) :: Change Log

* 2022-0604: 1.11 (IgorZ) for KSP ['1.12.3', '1.12.2', '1.12.1', '1.12.0']
	+ 1.11 (June 3rd, 2022):
		- [Enhancement #329] Bring back haroon and grapling hook.
* 2021-1021: 1.10 (IgorZ) for KSP ['1.12.2', '1.12.1', '1.12.0']
	+ 1.10 (October 20th, 2021):
		- [Fix #326] Error in the logs when an inactive vessel gets in range.
* 2021-0702: 1.9 (IgorZ) for KSP 1.12.0
	+ 1.9 (July 1st, 2021):
		- [Fix #324] Resources intermittently disappear from RTS transfer dialog.
* 2021-0628: 1.8 (IgorZ) for KSP 1.12.0
	+ 1.8 (June 27th, 2021):
		- [NOTICE] If a connected KAS part gets involved in a stock EVA construction operation, it will get immediately detached from the peer. To avoid unpexected behvior, it's recommended to manually break the link before using EVA construction mode.
		- [NOTICE] The interactive links (like in `PCB`) are now not possible in EVA construction mode.
		- [Compatibility] Drop AVC version check due to the KSP `1.12` duplicated mods handling bug.
		- [Change] Better detect if any of the peers in the KAS connection got destroyed for any reason. The link gets properly broken in this case.
		- [Enhancement] Allow attaching to the winches surface to let reinforcing them with struts.
		- [Enhancement] Don't show resources that cannot be transferred in the RTS GUI.
		- [Enhancement] Allow disabling the controls hints in the RTS resource transfer dialog. Use setting `showTransferDialogHints`.
		- [Enhancement] Allow disabling the controls hints in the winches remote control dialog. Use setting `showRemoteControlDialogHints`.
		- [Enhancement #248] Add ability to scale Transfer GUI.
		- [Enhancement #321] Scale the Winch GUI dialog.
		- [Fix #302] GUI does not respect hide/show function.
		- [Fix #306] Logs spam from the parts dropped on the ground.
		- [Fix #307] Interactive attach mode conflicts with construction mode.
		- [Fix #308] Linked parts can be dragged in construct mode.
		- [Fix #309] TJ parts cannot align when pulled out of cargo.
		- [Fix #311] Breaks the Asteroid Redirect Training Mission.
		- [Fix #313] Coupling vessels via the rigid link cause vessel breakage.
		- [Fix #314] Retract cable option is visible when the connector is locked.
		- [Fix #315] Attaching KAS links resets EVA editor parts highlighting.
		- [Fix #316] The detached physicsless parts stay physicsless.
		- [Fix #317] Coupling role delegation doesn't work.
		- [Fix #318] EVA construction mode highlighting stays on the KAS pipes after the mode is canceled.
		- [Fix #320] Renderer is active even on the locked winch connector.
* 2020-0731: 1.7 (IgorZ) for KSP 1.10
	+ 1.7 (July 30th, 2020):
		- [Change] Better react on the attached part(s) destruction to properly reset the link state.
		- [Change] Some performance improvement for the winch connector handling.
		- [Change] Update EN/RU localizations to version `6`.
		- [Change] Update Chinese localization.
		- [Fix #295] Stop using `MiniAVC.dll` in favor of `MiniAVC-V2.dll`.
		- [Fix #297] Decoupling near winch connected in editor causes the winch to break in to two separate vessels.
* 2017-0816: 1.0.6436.42780 (IgorZ) for KSP ['1.9.1', '1.9'] PRE-RELEASE
	+ Added initial version of the winch
* 2017-0623: 1.0.6383.1326 (IgorZ) for KSP ['1.9.1', '1.9'] PRE-RELEASE
	+ 1.0 (June 23rd, 2017):
		- [Fix #204] Link status is not restored on load.
		- [Fix #205] Bad link state doesn't restore on load.
		- [Fix #206] TJ-2 applies momentum on the vessel when linked.
* 2020-0427: 1.6 (IgorZ) for KSP ['1.9.1', '1.9']
	+ 1.6 (April 26th, 2020):
		- [Fix #289] RTS-1 docking mode is not reset on decoupling.
		- [Change] Stop complaining about KSP minor version change.
		- [Enhancement] Add two new localization strings for the custom corridors: `Corridor-1000` and `Corridor-1500`.
		- [Enhancement] Add an optional patch `MM-LegacyKASPipesPart.txt` to simulate the old `KAS` pipes. Use at your own risk!
* 2019-1028: 1.5 (IgorZ) for KSP 1.8
	+ 1.5 (pre-release):
		- [Change] `KSP 1.8` compatibility. __WARNING__: the mod won't work with version lower than `KSP 1.8`!
		- [Enhancement] Add Chinese localization.
		- [Fix #279] Can't surface attach the hw-80 winch.
* 2019-0608: 1.4 (IgorZ) for KSP ['1.7.3', '1.7.2', '1.7.1']
	+ 1.4 (June 7th, 2019):
		- [Change] Update ES-ES localization.
		- [Enhancement] Use icon of better resolution in the editor to avoid bluring.
		- [Fix #271] KSP 1.7.1 breaks grabbing connectors from winch type parts.
* 2019-0421: 1.3 (IgorZ) for KSP 1.7
	+ 1.3 (April 21st, 2019):
		- [Change] KSP 1.7 compatibility.
		- [Fix #263] Missing files trying to compile locally.
		- [Fix #264] It's seems that KAS v1.2 do not support KSP v1.7.
* 2019-0408: 1.2 (IgorZ) for KSP ['1.6.1', '1.6.0']
	+ 1.2 (Apr 8th, 2019):
		- [Change] ATTENTION! The lagacy parts are _not_ provided in this verison!!! Read [Wiki](https://github.com/ihsoft/KAS/wiki/Legacy-parts-destiny) for more details.
		- [Enhancement] Add French localziation.
		- [Enhancement] Add Portuguese localziation.
		- [Enhancement #260] Add a setting to control the couple state on link.
		- [Change] Major update to the basic renderer module to increase UX experience.
		- [Fix #236] Support action groups in winches.
		- [Fix #252] NRE when entering the vessel from EVA.
		- [Fix #255] KAS link throws when loading save file.
		- [Fix #258] Connectors break on entering the physics bubble.
		- [Fix #260] Add a setting to control the couple state on link.
* 2018-1030: 1.1 (IgorZ) for KSP ['1.5.1', '1.5']
	+ 1.1 (October 29th, 2018):
		- [Enhancement] Add ES-ES localization.
		- [Fix #249] Pylons are not get equipped when carried.
* 2018-1023: 1.0 (IgorZ) for KSP ['1.5.1', '1.5']
	+ 1.0 (October 21st, 2018):
		- [Change] KSP 1.5 compatibility.
		- [Fix #238] Multiple RTS dialogs conflict with each other.
		- [Fix #239] RTS dialog cannot be moved.
		- [Fix #240] RTS-1 doesn't see all the resources on the vessel.
		- [Fix #241] RTS-1 doesn't allow passing fuel in the docked mode.
		- [Fix #242] Use resource definition to check if it can be transferred in RTS.
		- [Fix #244] GP-20 & BGP-400 are not in the KAS tab in VAB.
		- [Fix #246] Timewarp doesn't affect the RTS-1 transfer speed.
* 2017-0527: 0.7.4-beta (IgorZ) for KSP 1.3 PRE-RELEASE
	+ 0.7.4 (May 26th, 2017):
		- [Enhancement] A brand new model for CH-1.
		- [Enhancement] PCB-1 cable now has a head that plugs into CH-1 model.
		- KSP 1.3 support.
* 2017-0204: 0.7.3-beta (IgorZ) for KSP ['1.4.2', '1.4.1', '1.4.0'] PRE-RELEASE
	+ 0.7.3 (pre-release):
		- [Enhancement] Add cable joint parts PCB-1 and CH-1.
		- [Change] Rename module: `KASModuleInteractiveJointSource` to `KASModuleInteractiveLinkSource`.
		- [Change] Rename module: `KASModuleTelescopicPipeStrut` to `KASModuleTelescopicPipeModel`.
		- [Fix #190] KAS 1.0: Bring back collider for the clutches.
* 2016-1119: 0.7.2-beta (IgorZ) for KSP ['1.4.2', '1.4.1', '1.4.0'] PRE-RELEASE
	+ Changes:
		- [Fix] #186: Loaded position of TJ-2 & T-60 is incorrect.
		- [Fix] #187: Vessel can auto save during interactive mode.
		- [Fix] #188: Incorrect unlinking when vessel root changes.
		- [Enhancement] TB-60 supports locking and active steering to increase stability.
* 2016-1023: 0.7.1-beta (IgorZ) for KSP ['1.4.2', '1.4.1', '1.4.0'] PRE-RELEASE
	+ Fixed:
		- 184: Free joint limit angles are checked incorrectly
		- 183: TJ-2 context menu doesn't update correctly
		- 182: TJ-2 incorrectly restores state on load
		- 181: ESC opens pause menu when in interactive mode
		- 177: Free joint stops working as free
* 2016-1017: 0.7.0-beta (IgorZ) for KSP ['1.4.2', '1.4.1', '1.4.0'] PRE-RELEASE
	+ No changelog provided
* 2018-0309: 0.6.4 (IgorZ) for KSP ['1.4.2', '1.4.1', '1.4.0']
	+ Do _not_ use this release to install the mod! It's only a sources snapshot. Go to the forum thread for the complete installation instructions.
	+ 0.6.4 (March 8h, 2018)
			- KSP 1.4 support.
* 2017-0527: 0.6.3 (IgorZ) for KSP 1.3
	+ Do _not_ use this release to install the mod! It's only a sources snapshot. Go to the forum thread for the complete installation instructions.
	+ 0.6.3 (May 26th, 2017)
			- [Fix] Show detach button when harpooned to a part (asmigala).
			- [Change] Support a new format of the `OnKISAction` parameter.
			- KSP 1.3 support.
* 2016-1227: 0.6.2 (IgorZ) for KSP ['1.2.2', '1.2.1', '1.2']
	+ 0.6.2 (December 26th, 2016)
		- [Fix #191] Unable to use winch with attached in VAB parts with wheels.
* 2016-1206: 0.6.1 (IgorZ) for KSP 1.2
	+ 0.6.1 (December 5th, 2016)
		- [Fix #194] Ground pylon part is not visible in editor.
		- [Fix #195] Put more parts into EVA items filter.
* 2016-1012: 0.6.0 (IgorZ) for KSP 1.2
	+ KSP 1.2 support
* 2016-0627: 0.5.9 (IgorZ) for KSP 1.1
	+ 0.5.9 (June 27th, 2016)
		- [Fix] #171: KSP 1.1.3 compatibility.
* 2016-0613: 0.5.8 (IgorZ) for KSP 1.1
	+ 0.5.8 (June 12th, 2016)
		- [Fix] #167: Loading winch connected same vessel.
		- [Fix] #169: Winch motor acceleration is not scaled to FPS.
		- [Fix] #168: #Disconnected winch head behaves against the gravity.
* 2016-0502: 0.5.7 (IgorZ) for KSP 1.1
	+ 0.5.7. (2 may 2016)
		- [Change] Compatibility change for KSP 1.1.2.
		- [Change] Migrate parts to the new enum in KISItem (see KIS 1.2.8 release notes).
* 2016-0422: 0.5.6 (IgorZ) for KSP 1.1
	+ 0.5.6 (21 April 2016)
		- [Change] KSP 1.1 supported!
		- [Change] Increase hooks break strength with respect to Unity 5 physics change.
		- [Change] Increase static attach strength on pylon to prevent joint breakage.
		- [Enhancement] Improved search tags and descriptions in parts.
		- [Fix] Fix bottom & srf attach nodes on pylon to make it more stable and prevent explosions on physics start.
* 2016-0421: 0.5.6-alpha.6 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ This is a testing version only. Do not install it unless you're participating in alpha testing.
* 2016-0417: 0.5.6-alpha.5 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ This is a testing version only. Do not install it unless you're participating in alpha testing.
* 2016-0416: 0.5.6-alpha.4 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ This is a testing version only. Do not install it unless you're participating in alpha testing.
* 2016-0414: 0.5.6-alpha.3 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ This is a testing version only. Do not install it unless you're participating in alpha testing.
* 2016-0411: 0.5.6-alpha.2 (IgorZ) for KSP 1.1 PRE-RELEASE
	+ This is a testing version only. Do not install it unless you're participating in alpha testing.
* 2015-1111: 0.5.5 (IgorZ) for KSP 1.0.5
	+ 0.5.5 (11 November 2015)
		- Compatibility fix for KSP 1.0.5
* 2015-0729: 0.5.4 (KospY) for KSP 1.0.4
	+ [Enhancement] Allow KAS to work without KIS (removed KIS dependancy)
	+ [Enhancement] Moving harpoons with KIS will not attach them on the ground anymore (attach key must now be used)
	+ [Change] Removed old container module (used to move old KAS v0.4 items to KIS items)
	+ [Fix] Fixed KIS dependancy checker not working as expected
* 2015-0711: 0.5.3 (KospY) for KSP 1.0.4
	+ [Fix] Compatibility update for KSP 1.0.4
	+ [Fix] Updated KAS to use the latest version of KIS (v1.2)
	+ [Fix] Updated pylon to use the new KIS module for ground attachement
* 2015-0531: 0.5.2 (KospY) for KSP 1.0.2
	+ [Enhancement] Converted parts textures to DDS
	+ [Enhancement] AVC is now used for version check
	+ [Enhancement] Added a KIS version dependancy check
	+ [Fix] Added stacking to connector port
	+ [Fix] Fixed a compatibility issue with Kerbal Joint Reinforcement
	+ [Fix] Updated OnKISAction to use BaseEventData (prevent KAS crash if KIS is missing)
* 2015-0514: 0.5.1 (KospY) for KSP 1.02 
	+ Added a warning if KIS is not detected
	+ Fixed radial winch not allowing stack attach
* 2015-05??: 0.4.7 (KospY) for KSP 0.23.5 PRE-RELEASE
