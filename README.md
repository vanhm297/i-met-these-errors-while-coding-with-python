# i-met-these-errors-while-coding-with-python
1. No module named 'pywintypes after installing "pyttsx3" (Text to Speech):

Tbh I'm not sure how this error was solved. What I did just:

+ searched for answers on Stackoverflow but none of them helped
+ asked my friend but she didn't reply
+ wrote some bad commands in Command Prompt then be terrified by what appeared next on the screen
+ shut down the computer and went to sleep

and the next day my code run magically :)???

2. can't import pyaudio windows

again be terrified by what showed up on the screen while installing pyaudio.

Luckily I found a perfect answer on StackOverFlow hohoo

          pip install pipwin
          pipwin install pyaudio

3. Python Speech Recognition: AttributeError: module 'speech_recognition' has no attribute 'Recognizer'

The problem was, I named the file I'm working on 'speech_recognition'. Therefore python was looking not to the speech_recognition module but search the Recognizer in my module (file).

How to solve: rename the file and delete the old file
