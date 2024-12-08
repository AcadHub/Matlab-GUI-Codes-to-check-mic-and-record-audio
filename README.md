# Matlab-GUI-Codes-to-check-mic-and-record-audio
This Matlab GUI code will allow user to test their computer Microphone and record audio. 

This code is inspired by a article on <a href="https://www.academicblock.com/technology/web-tools/test-my-mic">Test my mic</a> page.

This code is provided by Dr. Goan,  <a href="https://www.academicblock.com/">Academic Block</a>


Requirements

Make sure you have the necessary MATLAB toolboxes (Audio Toolbox and DSP System Toolbox) installed.
Adjust the recordTime variable to change the recording duration.
  

Setup in this GUI:

The script creates a GUI for saving the audio file and uses a timer to update the live plot.
Define recording parameters like sampling frequency, bit depth, and the number of channels.
Display the live audio waveform.
Start the recording and display a message indicating the recording has started.
After recording, retrieve the audio data and plot the final waveform.
Save the recorded audio in MP3 format using audiowrite.
    

   
    
