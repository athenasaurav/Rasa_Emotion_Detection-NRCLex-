# Rasa_Emotion_Detection-NRCLex-

This repo is is for detecting emotions in text using a popular library NRCLex.

You can watch the tutorial video on [Youtube](https://www.youtube.com/watch?v=REU0bh6wkm4&t=4s)

## Prerequisites:
- RASA
- Anaconda Prompt
- Visual Studio Code
- NCRLex

## Instructions:

### For installing Depencies on Windows:

### RASA Installation

If python is installed in your system, then pip comes in handy.
So simple steps are:
1) Install virtualenv using

- > pip install virtualenv 

2) Now in which ever directory you are, this line below will create a virtualenv there

 - > virtualenv myenv

And here also you can name it anything instead of myenv.

3) Now if you are same directory then type,

- > myenv\Scripts\activate

4) Upgrade pip (Please use this command in administrator mode)

- > pip install --upgrade pip

5) Install RASA

- > pip install rasa==2.5.0

NOTE : Please check Python version should be 3.7 or greater and pip should be installed previously

If the rasa installation gives error, try this [solution](https://stackoverflow.com/questions/64291087/matplotlib-module-sip-has-no-attribute-setapi)

### Installating other dependencies

NCRLex

```
pip install NRCLex
```
# Installation Done

## Get files

Clone the repo

```
git clone https://github.com/athenasaurav/Rasa_Emotion_Detection-NRCLex.git
```

Move into the project directory

```
cd Rasa_Emotion_Detection-NRCLex
```

Open a new Anaconda Prompt

- > rasa train

## RUN RASA NLU 

Open one Ananconda prompt and move into ```Rasa_Emotion_Detection-NRCLex``` folder

- > rasa shell

## RUN RASA NLU 

Open a new Anaconda Prompt

- > rasa run actions

Voila! Start Texting your Bot that understand your Emotions.

connect with us on our [Website](https://prescient-automation.com)
