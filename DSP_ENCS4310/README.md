Audio Encoder/Decoder GUI
This Python application provides a Graphical User Interface (GUI) for encoding text into audio signals and decoding audio signals back into text. It utilizes the tkinter library for GUI development and matplotlib for signal visualization. The encoding and decoding processes involve the manipulation of audio signals based on predefined frequency mappings for characters.

Features
Text to Audio Encoding: Encode input text into audio signals with customizable duration and sample rate.
Audio to Text Decoding: Decode audio signals back into text using either frequency analysis or filtering techniques.
Signal Visualization: Visualize the encoded audio signal in both time and frequency domains.
User-friendly Interface: Intuitive GUI with buttons for encoding, decoding, browsing files, and playing audio.
Prerequisites
Python 3.x
Required Python libraries: tkinter, matplotlib, numpy, scipy
Usage
Enter the text to be encoded in the provided input field.
Click the "Encode" button to generate the corresponding audio signal.
Optionally, play the generated audio signal using the "Sound" button.
Browse and select a WAV file containing the audio signal to be decoded.
Click either "Decode by frequency analysis" or "Decode by using filter" button to decode the audio signal and display the resulting text.
Contributors
