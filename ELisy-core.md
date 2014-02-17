ELisy — Embedded (system) Livecoded Synthetizer
=========
or: *a musical instrument surrogate* - general concept
---

An ELisy station can be thought as an integrated system that allows one or multiple users to perform audio livecoding on a capable embedded system with synth-like properties.
ELisy-R is its Raspberry Pi implementation.

ELisy-R
===
or: *Tidal implementation in Raspbian for audio performance*
---
The Rasberry Pi implementation of this idea is a Tidal instance running in Raspbian with the Emacs editor remotely and interchangeably accessed by one or multiple users via ssh shells.
Lets define the details considering the various components:

### Software Components 
- Tidal
- Dirt
- Emacs
- JACK

[Tidal][1] is an Haskell-embedded  mini-language for live coding of audio patterns. It uses the simple sample-player [Dirt][2] to interactively play loops of audio snippets and form sound patterns. Emacs is the editor and JACK the sound server of choice.
Also a home LAN is needed, although it must be considered as networking component.

In-depth configuration is shown separately.



### Hardware Components

The foundamental ones are:
- Raspberry Pi
- necessary cables (power, audio)
- speakers or headphones

combined with other things in three configuration categories:

- **boxed**: this is the setup that best represents the idea of a musical instrument as traditionally thought: an object that you play, or use to produce sound; a custom-made case that includes the RasPi together with a LCD screen and a keyboard, boxed in a unique body. So the livecoding happens on the station itself.
- **stand-alone**: a single object, with a custom or pre-made case, headless (without monitors) with only speakers or headphones plugged. The station should not explicitly be wired or attached to any input device, as the livecoding happens with a remote device like a PC, smartphone or another remote controller. This setup gives the idea of an instrument interactively used without direct physical interaction with the object.
- **bundled**: integrated or attached to other devices. These can be TVs, monitors, hi-fi or even home appliances. This is the most domotics- or workspace-friendly setup: gives the idea of an instrument that is part of another device, appliance or even of a room or physical space. In this case linked devices can be, as applicable: keyboard+monitor, remote PC or an input controller shared with the "host" system/machine.






[1]:https://github.com/yaxu/Tidal
[2]:https://github.com/yaxu/Dirt

    
