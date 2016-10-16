pd-grainders (granular synthesis in Pd)
=======================================

This repository contains a few patches to perform granular synthesis. From sample-based granulation to live-input to synthesised sound.

List of tools:

input-grainder. Stores incoming audio to a delay line and performs basic granular synthesis operations.

file-grainder. Takes a mono soundfile (.wav) and performs granular synthesis on it.

osc-grainder. Granular synthesis with sine waves.

pulse-grainder. Granular synthesis with unit-pulses and karplus-strong resonances.

All or some of these patches need the following externals: *maxlib hcs iemlib mapping zexy ggee purepd motex cyclone*


