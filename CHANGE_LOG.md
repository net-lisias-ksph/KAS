# Kerbal Attachment System (KAS) :: Change Log

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
