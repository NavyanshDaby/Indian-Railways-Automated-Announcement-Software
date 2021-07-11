# Indian Railways Automated Announcement Software

It is an **automated software** which will generate the Railway Station Announcement by maintaining a database of required information in an excel sheet.

![Cover Image](https://user-images.githubusercontent.com/68781375/125184803-67aa5d00-e23e-11eb-9b81-15924a3fbf6b.jpg)

## Announcement Languages 

Announcement is generated in the below three languages:

* Hindi

* English

* Gujarati

## Development Environment

* Used **Python Language** with a **bunch of its libraries** like **pyAudio**, **pydub**, **pandas**, **openpyxl** and **gTTS** to **generate announcement status** of thousands of trains.

* Used **pyAudio** to play and record audio.

* Used **pydub** and **pandas** for audio manipulation.

* Used **openpyxl** to read excel(.xlsx) file.

* Used **gTTS(Google Text-to-Speech)** to translate text to speech.

## Process

* First of all record the announcement of any of the train from the railway station or download it from the internet.

* Then trim the recorded sound of the train number and name, source, route, destination, platform number on which train is arriving, and so on.

* Maintain a database in excel sheet of various information regarding the train number and name, source, route, destination, platform number, etc.

* Read that excel file and convert all those text to speech according to the languages(Hindi / English / Gujarati) and create seperate audio files.

## Demo Video

https://user-images.githubusercontent.com/68781375/125184784-42b5ea00-e23e-11eb-80bf-7809181d3b0b.mp4
