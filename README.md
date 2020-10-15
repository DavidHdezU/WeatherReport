# Climatronic 3000
[![Generic badge](https://img.shields.io/badge/version-3.09.10-<COLOR>.svg)](https://shields.io/)
[![Open Source Love png1](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Generic badge](https://img.shields.io/badge/contributors-2-blue)](https://shields.io/)  
[![forthebadge made-with-python](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  


## Table of contents
* [About the project](#About-the-project)
* [How to start](#how-to-start)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Use](#uso)





# About the project
Basically this project aims to use OpenWehatherMap requests, to provide information about the weather in different cities.
This consists of a src folder, which contains all the readable, interpretable and executable code, in turn a folder
```
resources
```

This folder contains 4 folders and a .mp3 file, there are important to the functionality of the program
```
Documentacion
```

This folder contains a PDF written in LaTeX, about everything you need to know about the program: Costs, operations, Development and what does not seem like it today but in the future its maintenance and revision will be very necessary


```
dataset
```
The effects can cause damage to the general execution of the program as it contains the .csv files that allow you to obtain the requests for the data you want.

```
greeting
```
It contains text files, which allow the voice to greet in an almost unpredictable way, they can be manipulated, but remember that any phrase written there could be read through the loudspeaker

```
tones
```
It includes the entrance curtain to announce the entrance of the voice, if you modify it, it must be a file with the same name, we recommend a .mp3 file with a duration <= 10 seconds, as it will be played before each announcement

```
speaking.mp3
```
We recommend not manipulating it during the execution of the program, since the voice is there, however before the execution of the program and after finishing, it can be used as any file with an .mp3 extension

# How to start
First of all, it is necessary to mention that it is written in Python, under versions greater than or equal to Python 3.8, so it is advisable to update your computer to the most recent version of Python, otherwise some failures could occur, and Similarly, we recommend running on computers with GNU LINUX Operating System in any of its versions.
It is also necessary to install some extra libraries, you do not need to worry about installing each one of them correctly, thanks to a self-installation script: install_librarys.sh


## Prerequisitos
* Verify to use a version higher than Python 3.6:
```
python --version
```
> `Python 3.8+` is adviced  

  Note, on some Linux distros, you will run it like: 
  ```
  python3 --version
  ```


* You can check if you have PyPI installed as well as Python
   Available in the following article
  [PyPI](https://www.tecmint.com/install-pip-in-linux/) up.  

## Instalation
1. Clone the repository
```
git clone https://github.com/IanGarciaUnam/climatronic_3000.git
```
3. Verify the installation of the packages with our installer
  ```
  bash Tarea01/src/install_librarys.sh
  ```
  It will install
  * `gTTS`
  * `playsound`
  * `pandas`
  * `keyboard`
  * `googletrans`
 4. After installing the libraries, run the unit tests (PruebasUnitarias.py), the legend should appear
 ```
 OK
 ```
 



# Use

You'll have to execute
```
bash Tarea01/src/launcher.sh
```
or 
```
python3 Tarea01/src/Menu.py
```


# Developed by:
#### David Hernández Urióstegui | @DavidHdezU   <-> Ian Israel García Vázquez | @IanGarciaUnam

[<img src="https://img.shields.io/badge/gmail-D14836?&style=for-the-badge&logo=gmail&logoColor=white"/>](https://mail.google.com/mail/?view=cm&source=mailto&to=iangarcia@ciencias.unam.mx)
[<img src="https://img.shields.io/badge/gmail-D14836?&style=for-the-badge&logo=gmail&logoColor=white"/>](https://mail.google.com/mail/?view=cm&source=mailto&to=Dhdezu@ciencias.unam.mx)





---
![forthebadge biult-with-love](https://forthebadge.com/images/badges/built-with-love.svg) 
[![forthebadge powered-by-electricity](https://forthebadge.com/images/badges/powered-by-electricity.svg)](http://ForTheBadge.com)  

---
[Go up](#climatronic-3000)
