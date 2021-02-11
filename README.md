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

4. webbrowser.Error: could not locate runnable browser

To open a website in my web browser, I followed the model codes:

          import webbrowser
          webbrowser.open("https://google.com")
          
It worked, but it opened in my default browser, which is Microsoft Edge, the browser I didn't want. I would be very happy if it was Google Chrome. 

How I changed it into Google Chrome (follow the instruction on StackOverFlow of course):

 + get Google Chrome's location (mine is: C:\Program Files\Google\Chrome\Application)
 + Start - Settings - Edit Enviroment variables - Enviroment variables - Path in System variables - Edit - Paste the Google Chrome's location - OK
 + rewrite the codes:
 
           import webbrowser
           webbrowser.get("chrome %s).open("https://google.com")
                    
 
