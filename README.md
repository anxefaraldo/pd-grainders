pd-grainders (granular synthesis in Pure data)
=======================================

This repository contains a few prototypes based on granular synthesis, including sample-based, live-input and synthesis-based granulation. All or some of these patches need the following externals:

*cyclone else iemlib zezy*

Cyclone and else are included in Pludgata. You must download and install iemlib and zexy via deken, as they are needed to run file-grainder.

List of Contents:

file-grainder. Takes a mono soundfile (.wav) and performs granular synthesis on it.

input-grainder. Stores incoming audio to a delay line and performs basic granular synthesis operations.

pulse-grainder. Granular synthesis with unit-pulses and karplus-strong resonances.

sine-grainder. Granular synthesis with sine waves.


This branch is optimised to work with plugdata >= 0.9, which already includes the required externals.
