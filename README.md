# Hexagone
60hp/desktop digital polysynth

preliminary info, nothing here is final.

this will be a semi-open source project like the orgone accumulator. code and panel are open, but you have to buy the main PCB.
teensy 3.6 running at 240mhz

This is not a VA synth, it is based on additive, wavetables, and "west coast" type sound building with folders, waveshaping, etc. lots of modulation!

currently it gets 5-6 notes of poly depending on oscillator forms

each voice has: 

OSCILLATORS each osc can be individually tuned with octave, semitone and cent, or coarse/fine.

noise osc, 
various noise and harsh digital sounds. controls are 1 parameter and level/AM

osc1, 
various forms from simple band limited saw, some modified orgone and some modified braids things, controls are 2 modulatable parameters + tune, FM, and level/AM some forms are antialiased and some are raw. (indicated on form name)

osc2/fx
can be an oscillator with subset of osc1 forms, or an effect such as resonator on noise and osc 1
controls are 2 modulatable parameters + tune, FM, and 1+N/2 mix

osc 3 simple/sub mixed post osc2.

MODULATORS
ADSR envelope
3x loopable AD envelope/LFO
dedicated LFO (can be MIDI sync or ext clock synced)
2x MOD knobs
4x CV in
MIDI velocity, note number, mod, bend, etc
random per note
all osc outputs can be mod sources

OUTPUT
stereo position per note can be modulated by any mod source. width by knob.

