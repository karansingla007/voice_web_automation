# Voce Browser

![GPL License](https://img.shields.io/badge/license-GPLv3-green) ![Platforms](https://img.shields.io/powershellgallery/p/DNS.1.1.1.1)
![Python v3.7](https://img.shields.io/github/pipenv/locked/python-version/metabolize/rq-dashboard-on-heroku) ![Build passing](https://img.shields.io/github/workflow/status/actions/toolkit/Main%20workflow) ![Speech Recognition](https://img.shields.io/badge/speech-recognition-important) ![gTTS](https://img.shields.io/badge/gTTS-2.1.1-blueviolet) ![PyQt5](https://img.shields.io/badge/PyQt5-5.12.3-red)


voice web automation is a chrome based voice controlled browser using Selenium. It has all the basic browser features like Chrome or Firefox and in addition it can be controlled with voice commands.

![Voce Browser](https://github.com/trabdlkarim/voce-browser/blob/master/screenshots/VoceScreenshot3.png)

![Voce Browser](https://github.com/trabdlkarim/voce-browser/blob/master/screenshots/VoceScreenshot6.png)

## Table of contents

* [Description](#description)
* [Features](#features)
* [Dependencies](#dependencies)
* [Setup](#setup)
* [License](#license)

## Description

This project uses the Selenium Python binding as user interface. voice web browser can be taken voice commands which are translated and then exceuted using speech_recognition library

## Features

voice web browser has all standard browser features, and plus voice commands capabilities.

### Supported Voice Commands

- Open Google/Youtube tab: Open Google/Youtube in a new tab.
- Close tab: close current tab
- Close window: close current window
- Search: Search in Google/Youtube for a keyword. This command should be followed by a search google.
- Go back: go back to the previous page if any
- Go forward: go to the next page if any
- Exit, bye and quit: Close all windows and exit the browser

## Dependencies

This project is created with:

* selenium
* speech_recognition
* pyttsx3
	
## Setup

To run the browser, first download or git clone this project and then run in the IDE with python Environment.

Supposing that you have already **Python3** and **pip3** installed on your system, from the terminal change the current directory to the project root directory. Proceed then as follows:

```
pip3 install selenium
pinp3 install speech_recognition
pip3 install pyttsx3
```

## Notes:

## License 

![GPL License](https://img.shields.io/badge/license-GPLv3-green)

This is an open-source project under the GPL-3.0 License
