# DONNA_voice_assistant
DONNA is a voice assistant that answers to the questions 
This project is a simple voice assistant named "Donna," built using Python. The assistant is capable of performing various tasks such as searching on Wikipedia, sending emails, checking the weather, controlling media applications, and more.

Features:
Speech Recognition: Uses the speech_recognition library to capture commands via voice.

Text-to-Speech: Uses the pyttsx3 library to respond to commands with audio.

Wikipedia Search: Allows the user to search for information on Wikipedia.

Spotify Integration: Opens Spotify and plays music on command (requires Spotify credentials).

App Control: Opens and closes applications like Chrome, WhatsApp, Instagram, and more.

Email Functionality: Sends emails via Gmail based on voice commands.

Weather Updates: Fetches the current weather data for a given location using the OpenWeather API.

Jokes: Tells jokes using the pyjokes library.

Search on Google: Allows users to search Google via voice command.

System Control: Shuts down or restarts the computer based on voice commands.

Requirements
Python 3.x
Libraries:
pyttsx3
speech_recognition
wikipedia
webbrowser
os
smtplib
requests
json
pyjokes
random

To install the required libraries, you can use pip:

pip install pyttsx3 SpeechRecognition wikipedia requests pyjokes

Setup Instructions
Install Python 3.x: Ensure that Python 3.x is installed on your system. If not, download and install it from the official Python website.
Clone the Repository: Clone this repository to your local machine using the following command:
git clone https://github.com/yourusername/voice-assistant.git
Install Dependencies: Install the required Python libraries using the command mentioned above.
Modify the Code:
Replace the email and password in the send email section with your own Gmail credentials.
Set up your Spotify credentials to use the Spotify functionality.
Run the Program: Execute the script Jarvis.py to start the voice assistant.
python Jarvis.py

Commands
Here are some of the commands that "Donna" understands:

General Commands:
"Hello Donna"
"How are you?"
"Tell me a joke"
"What is the time?"
"Shutdown computer"
"Restart computer"
Media Commands:
"Play a song"
"Next song"
"Open Spotify"
"Open YouTube"
"Open Instagram"
"Open WhatsApp"
"Open Chrome"
System Commands:
"Search Google"
"Open Gmail"
"Send email to [Name]"
"What is the weather?"

Note
Some features (such as Spotify control and email sending) may require specific configuration (e.g., Spotify API keys or Gmail account setup).
The system control features (shutdown/restart) will only work on Windows.
