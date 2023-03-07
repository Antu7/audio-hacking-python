# Audio HACKING

This is a simple Python script continuously recording audio from the microphone and saving it as .wav files. The recorded audio is saved in 15 second increments, with each recording being saved as a separate .wav file with a unique filename based on the current time. You can recode & listen people's conversations without their permission.

For more please check this Medium [Link](https://medium.com/@textmeantu/create-an-audio-bug-using-python-a8cbf07994a8)

## Requirements
- Python 3.x
- `pyaudio` library for audio

## Installation

```bash 
$ sudo apt-get install build-essential libasound-dev portaudio19-dev libportaudio2 libportaudiocpp0 python3-dev
$ pip install pyaudio
```

## Usage

```bash 
$ python audio.py
```


You will be prompted to enter the host to scan and the protocol (TCP or UDP). After entering the required information, the script will check the availability of all ports on the host and identify the service running on the open ports.

## Features

- Capture audio from microphone or headphone after every 15 Sec
- Save audio into a folder with .wav

## Note

This script is not a substitute for a proper security assessment, and it should only be used for educational and testing purposes. The use of this script for malicious activities is strictly prohibited.


## Contributing

We welcome contributions to this project! Here are some ways you can contribute:

1. **Report bugs or suggest new features.** If you find a bug or have an idea for a new feature, open an issue on Github.

2. **Fix bugs or add new features.** If you are a developer, you can submit a pull request with your changes. Please make sure to follow the existing code style and write tests for your changes.

3. **Documentation.** If you see any unclear or incorrect documentation, feel free to suggest changes.

4. **Testing.** Test the code and make sure it works as expected on different systems and configurations. Report any issues you find.


Thank you for your contributions!
