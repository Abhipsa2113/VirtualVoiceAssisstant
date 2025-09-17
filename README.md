# VirtualVoiceAssisstant
This project is a real-time AI-powered voice assistant built using the ElevenLabs Conversational AI API . It allows you to interact with an assistant naturally through speech. The assistant listens to your voice, processes the input with an LLM, generates context-aware responses, and replies back using natural-sounding speech.

***SETTING UP ELEVENLABS***
#STEP-1 : Installed the required packages for audio

#STEP-2 : Setup ElevenLabs which provides a Conversational AI API that will be used to create the Voice Assistant

#STEP-3 : In "Conversational AI", Go to "Agents", Click on "Start from blank".

#STEP-4 : In my project folder created a .env file and added agent-id.

#STEP-5 : Go to the "Security" tab, enable the "First message" and "System prompt" overrides, and saved. This allowed me to customize the assistant's first message and system prompt using Python code.

#STEP-6 : In profile and go to "API keys". Created a new API key and copied it to .env file


***BUILDING THE VOICE ASSISSTANT WITH PYTHON***
#STEP-1 : Created a Python file named voice_assistant.py and load your API credentials

#STEP-2 : imported the necessary modules, then configured the conversation with the agent's first message and system prompt.

#STEP-3 : Underneath in the same file, setted configuration to ElevenLabs agent

#STEP-4 : Implemented Callbacks for Responses

#STEP-5 : Initiated the conversation session in the same file
