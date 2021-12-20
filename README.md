# MIDI-Gate-Outputs

This sketch turns your teensy into a gate sequencer for integrating your DAW and modular or other hardware synthesizer. The gate outputs each correspond to different notes in your DAW, with notes C, D, E, F, G, & A on any octave triggering gate high signals at the gate outputs. In addition, the master clock and reset output allow for syncing sequencers and clock dividers to the master tempo of your DAW. The clock master clock division can be changed with an external gate signal, causing it play quarter, eighth, or sixteenth notes. 
