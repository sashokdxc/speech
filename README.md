# Hello and Welcome to the Speech to Speech Magician!
This app is a game designed for your entertainment!
Choose the figure you want to talk to, say or ask whatever you want, and hear the figure answering you!
The game is integrated with AI, so all the responses are generated by ChatGPT 
and your voice is being transcribed using Whisper model by openai.

<div style="text-align:center;">
  <img src=src/pics/magician.png width="400" alt="Magician">
</div>

# High Level Description
This is a Python project that enables users to interact with AI
using speech-to-text and text-to-speech technologies.


# Installation
1. Clone the repo `git clone https://github.com/NaomiKriger/speech_to_speech_magician.git`
2. `pip install -r requirements.txt`
3. Set up your environment variables:
   * Get your openai API key (check out [openai](https://openai.com) website to learn more)
   * Create a `.env` file in the project directory.
   * Add your OpenAI API key to the .env file: `OPENAI_API_KEY=your_api_key_here`
4. Run the server `python main.py`

# How to Play the Game
Once the server is running, you will hear the app "talking", 
offering you to choose the figure you want to talk to, and to start talking to your figure.
Each time you want to talk out loud - press and hold an arrow key on the keyboard while talking.
Once you finish talking (and un-press the key) - your recording will be transcribed by Whisper, 
and the transcription will be sent to ChatGPT for a response. 
The response will be read out loud via a text-to-speech library, and you'll hear it.

# Tech Stack
* Python
* openai
  * ChatGPT API
  * Whisper - speech-to-text
* pyttsx3 library for text-to-speech

# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details