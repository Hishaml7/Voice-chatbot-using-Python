Voice Chatbot:

The purpose of this task is to use the services of IBM Watson (Speech to text, text to speech) and merge them with the chatbot that I created earlier by using Python. 

Detailed description:

Speech to text service is used to receive the user’s voice and output text. In the Python program, the output of this service is stored in .txt file. Text to speech service is used to receive text and output speech. In the Python program, the output of this service is stored in .mp3 file. In the program, Watson assistant takes the output of speech to text as input to the chatbot and outputs the assistant’s response to text to speech service. This makes it a voice chatbot. The chatbot is also able to hold conversations and stores the user’s input and the chatbot’s output in multiple .txt and .mp3 files.

‘recordings’ folder contains the chatbot’s answers in the most recent conversation stored as .mp3 files.

‘text files’ folder contains the user’s input in the most recent conversation stored as .txt files.

To see my chatbot visit the following link: https://github.com/Hishaml7/Coffee-Chatbot.git 

How to run the program:

-	Install ‘pyaudio’, ‘playsound’, ‘ibm_watson’, and ‘ibm_cloud_sdk_core’ by using the command line. For example, “pip install pyaudio”.

- Create 2 empty folders named 'recordings', and 'text files' in the same folder as the other python files.

-	Run ‘transcribe.py’ file using the command line.

First, navigate to the folder that contains the files. 

Second, run the command ‘python transcribe.py – t 10’. 10 is the number of seconds that you want the program to record your voice, and you can change it.
