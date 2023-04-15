# Kesha v3.0 very early (aka Jarvis update)
Simple Voice Assistant made as an experiment using [Silero](https://github.com/snakers4/silero-models) & [Vosk](https://pypi.org/project/vosk/).
<br>Later on [Picovoice Porcupine Wake Word Detection](https://picovoice.ai/platform/porcupine/) & [ChatGPT](https://chat.openai.com/) was added.

![image](https://i.pinimg.com/originals/63/e9/b7/63e9b72b983793f64bffc07fd14a0e62.jpg)


# Installation
First, install the requirements, the `requirements.txt` file is just an output of `pip freeze` from my test venv 'k.<br>
Second, check `config.py` and set required values (api key, device index).<br>
Next, run the `main.py` script and Voilà, as simple as that.<br><br>

And don't forget to put models of Vosk to main folder.<br>
You can get the latest from the [official website.](https://alphacephei.com/vosk/models)
<br>The one I was using is `small`.

# Python version
I was using Python `3.8.3`, but it should work on any newer version.

# Author
(2023) Bohdan Verbytskyi