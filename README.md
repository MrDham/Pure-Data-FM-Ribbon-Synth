# Pure-Data-FM-Ribbon-Synth
A Pure Data very simple 3 operator FM synth that works well with MIDI Theremin (version 2.4 and above) https://github.com/MrDham/OpenTheremin_V3_with_MIDI

This synth is developed in Pure Data language. for more information go to : www.puredata.info/.

It consist in 3 serialised FM operators (Modulator 2 --> Modulator 1 --> Generator), a filter, a VCA and a vibrato (mod wheel).

yml file gives configuration options to use it in Zynthian project https://zynthian.org/.

Control is very simple: CC 07 or CC11 control the volume in 7 bit resolution, CC16 (MSB) and CC48 (LSB) are combined together to control the pitch in 14 bits resolution.
(Send CC48 (LSB) 1st, CC16 (MSB) 2nd ). No need to send Note On/Off messages or Pitch Bend messages. 
