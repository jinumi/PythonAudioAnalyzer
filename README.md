# Audio Visualizer

This is a Python script that analyzes and visualizes an audio file in real-time using the librosa and pygame libraries. The script loads the audio file, creates a spectrogram of it, and then displays it as a visualizer that rotates around the screen. Each frequency band in the spectrogram is represented as a bar that changes height based on the amplitude of the corresponding frequency band in the audio file.

## Requirements

This script requires Python 3.x, as well as the following libraries:

    * librosa
    * numpy
    * matplotlib
    * pygame
These can be installed via pip:

    pip install librosa numpy matplotlib pygame

## Usage

To use this script, simply run it from the command line:

    python audio_visualizer.py
When the script is running, you can use the following controls:

    Up arrow: Increase rotation speed
    Down arrow: Decrease rotation speed
    Left arrow: Decrease bar width
    Right arrow: Increase bar width
    Spacebar: Pause/unpause the visualizer
The script will prompt you to select an audio file to visualize. After selecting the file, the visualizer will begin.

## Credits

This script was inspired by a tutorial on Real Python The code for the binary search function is adapted from Stack Overflow.
