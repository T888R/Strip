# Strip
A multi function channel strip for Orac

Strip is a gate, de-esser, equalizer, and compressor all in one module which can process left and right inputs independently.
The gate section includes threshold, attack, hold, and decay controls and is off on both channels by default.
The de-esser section is very subtle but I added it as I often process a microphone on one of the inputs of my Organelle. It is implemented with a definable compressor band. The frequency range, Q factor, and threshold are available as controls.
The equalizer section is a fixed 6 band configuration with crossovers at 100, 300, 600, 4000, 8000, and 10000 hz. A hi pass filter at 80 hz is on always but can be removed. The 300 - 8000 can be accessed with the four knobs alone. The 100 and 10000 are adjusted by holding aux and turning the first and fourth knob respectively.
An instance of Bus-Comp by Audivit is provided as the compressor with a thin line gain reduction meter at the top of the screen.
Anyone of these effects can be applied or not to the left and right inputs with the use of the last page.

Things to fix:
Stickiness in the beginning stages of setting the equalizer amounts
