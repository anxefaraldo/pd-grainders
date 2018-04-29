pd-grainders (granular synthesis in Pd)
=======================================

This repository contains a few patches to perform granular synthesis. From sample-based granulation to live-input to synthesised sound. All or some of these patches need the following externals:

*cyclone ggee hcs iemlib mapping maxlib motex purepd zexy*

List of Contents:

file-grainder. Takes a mono soundfile (.wav) and performs granular synthesis on it.

input-grainder. Stores incoming audio to a delay line and performs basic granular synthesis operations.

pulse-grainder. Granular synthesis with unit-pulses and karplus-strong resonances.

sine-grainder. Granular synthesis with sine waves.


Tested with Pd-0.48.1