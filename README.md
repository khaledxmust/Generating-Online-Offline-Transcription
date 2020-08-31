# Generating-Online-Offline-Transcription
Generating Online/Offline Transcription based on Audio-Files

This Notebook has two main sections Online and Offline Transcription which is prefered to run each in independent enviroment.

1. Online Transcription
    - Based on Google-API 
    *which after experments turns out to be the most accurate and the fastest.
    
2. Offline Transcription
    - Based on at16k DeepLearning Model
    *Not the best time wise, but it does the job.
    
Both of the two appraches takes audio-files converting them into Mono-channel audio, then splitting the audio into sentences based on the audio pauses (Silences), then fed to the APIs and generate a text file called "recognized.txt" where each recognized sentence is appended there.
