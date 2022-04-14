# Voice-Based-Organizer

The project has a prototype part to view the GUI (how it would look with voice support) and a code section that separated the functionality, allowing us to evaluate and focus on both separately.

# Setup

These instructions have been tried for Windows 10. They may differ for other platforms.

1. Install miniconda for Python 3.8
2. Once installed, open the Miniconda Prompt and make sure there is a (base) prefix on the prompt.
3. Install speech_recognition using conda install -c speech_recognition.
4. Install pyaudio.
5. Using pip (make sure it is conda's built in pip) install pyttsx3.

[Screenshots]
IF you have other python distributions on your system, you may have to include the path to the one shipped with this environment to run the program.

# Unit Test

This test attempts to detect the sound hardware on your system. The device_index listed is what is used as an argument for the speech recognition instance. For systems I have tested on, the device_index needed was 1. It may differ for your system. 
The test will attempt to record one phrase from you and display it. Please speak when you see the 'Listening' portion. If it worked, you should hear something back from the engine.

[Screenshots]

