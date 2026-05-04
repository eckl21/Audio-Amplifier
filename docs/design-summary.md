# Design Summary

The Audio Amplifier project consists of two main stages:
- Pre-amplifier (buffering + tonal control)
- Main-amplification stage (Class AB)

The project includes circuit design, simulation, hardware verification, and PCB design. Major design updates will be recorded in the change log.

## Design update

The pre-amplifier will be an active circuit based on the TL072 op-amp. It will include a op-amp follower at the start, followed by a Baxandall EQ circuit
The main-amplifier will be a Class AB amplifier, which will amplify higher output current needed for the speaker load; 2W at 8 ohm
Each stage will be split between team members (2 per circuit), allowing tasks to be completed in parallel.
