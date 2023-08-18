# Voice-Transcription-Using-Whisper-API
To access my code, you can follow the link given below :-
**https://colab.research.google.com/drive/1zd9CkVUGmTZb7a1p2xePxkaV_Y7_fjsv?usp=sharing**
<h2> NOTE : I have used Gradio.app instead of Next.js because I do not have any knowledge and experience Next.js.</h2>
I am definitely planning to learn Next.js in the upcoming weeks. This learning will undoubtedly benefit me in my future career.
<h3>Important Libraries Used in the Project</h3>
1. Whisper - Whisper is used for automatic speech recognition (ASR). It is an ASR system developed by OpenAI that converts spoken language into written text
2. Gradio - Gradio is a library used to quickly create user interfaces for machine learning models. 
3. Openai - OpenAI is an artificial intelligence research organization that focuses on developing advanced AI technologies and models.
4. TTS - TTS is a library for advanced text - to - speech generation.

**Understanding the Significance of Some Key Code**
1. model=whisper.load_model("base") - In this we are  trying to load a model named "base" using the "model-whisper" library.
2. tss=TTS('tts_models/en/ljspeech/tacotron2-DDC_ph') - We are using the "TTS" class to initialize a text-to-speech model with a specific path to the model file.
3. def voice_chat(user_voice): ......... return(reply, 'output.wav')  - Created a function named 'voice_chat' that facilitates a voice-based conversation between a user and an AI assistant. The function transcribes the user's voice input, create a conversation history, generate a response using the GPT-3.5-turbo model, convert the response to speech using a text-to-speech model, and return both the textual reply and the generated speech in a WAV file.

**Had completed the Bonus Point**
Integrate the solution with the ChatGPT API and use the transcribed voice input as a prompt for generating chatbot responses.

**Working**
The initial step involves providing input in the form of voice (user_voice), which then gets processed by Whisper AI to convert the voice input into text. This converted text is then used as a prompt for the ChatGPT model, generating a response based on the provided question. The output is presented both as text and in the form of voice.
**Flow Diagram**
![1](https://github.com/bhavya1239/Voice-Transcription-Using-Whisper-API/assets/100862671/0342542b-b35e-4860-bea0-406dc2dfb747)

Thats All 
Thanyou 
