pd-grainders (granular synthesis in Pure data)
=======================================

This repository contains a few prototypes based on granular synthesis, including sample-based, live-input and synthesis-based granulation. All or some of these patches need the following externals:

*cyclone else iemlib mapping purepd zexy*

List of Contents:

file-grainder. Takes a mono soundfile (.wav) and performs granular synthesis on it.

input-grainder. Stores incoming audio to a delay line and performs basic granular synthesis operations.

pulse-grainder. Granular synthesis with unit-pulses and karplus-strong resonances.

sine-grainder. Granular synthesis with sine waves.


Branch optimised to work with plugdata 0.9.
