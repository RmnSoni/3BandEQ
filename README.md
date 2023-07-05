# VoiceEnhancer Eq
A small line-in equalizer VST3 plugin made with JUCE and C++.

## Features
- Three adjustable frequency bands: low, mid, and high.
- Graphical representation of the frequency response curve.
- Real-time audio processing using JUCE framework.
- User-friendly GUI for easy control and visualization.
- Compatibility with different audio applications and systems.

## Prerequisites
- Visual Studio 2019 or higher. 
- A C++ environment usually included in Visual Studio.
- JUCE v6.0.8 library (**not** included in the source code).
- Audio input/output device (sound card or virtual audio device).

## Installation
1. Clone the repository or download the source code.
2. You can get the same Juce version from [this repository](https://github.com/juce-framework/JUCE/releases/tag/6.0.8) or work with the newer versions.
3. Build Projucer using the `.sln` file.
4. Initiate a new project in Projucer, set its location in the repository.


## Usage
- Launch the 3-band equalizer application.

- Adjust the knobs for the low, mid, and high frequency bands or input values directly to modify the audio levels.

- The frequency response curve graphically represents the changes made to the audio levels in real-time.

- Test the equalizer by playing audio through your configured audio input/output device.

- Experiment with different settings and adjust the frequency bands to achieve the desired audio output.


## Acknowledgements
This project utilizes the following open-source software:

 - JUCE Framework - https://juce.com/

This project is based on learnings from MatKat Music's 
- PFM: Programming for Musicians course.