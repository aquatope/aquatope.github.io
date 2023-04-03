# aquatope
Scholar project

# Modules 
* pyttsx3


## pyttsx3
```py
engine = pyttsx3.init()

fr_voice = moteur.getProperty('voices')[0]
engine.setProperty('voice', fr_voice.id)

sentence = ""

# Dire la phrase en audio
engine.say(phrase)
engine.runAndWait()
```
