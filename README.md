pd-grainders (granular synthesis in Pd)
=======================================

This repository contains a few patches to perform granular synthesis. From sample-based granulation to live-input to synthesised sound. All or some of these patches need the following externals: *cyclone ggee hcs iemlib mapping maxlib motex purepd zexy*

List of tools:

input-grainder. Stores incoming audio to a delay line and performs basic granular synthesis operations.

file-grainder. Takes a mono soundfile (.wav) and performs granular synthesis on it.

osc-grainder. Granular synthesis with sine waves.

pulse-grainder. Granular synthesis with unit-pulses and karplus-strong resonances.

VoSim. Simple implementation of the VoSim (Voice Simulation) synchronous granular technique.
