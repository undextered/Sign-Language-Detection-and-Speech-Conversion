# Sign Language Detection and Speech Conversion
The project was created for Smart India Hackathon 2022 by our team under the problem statement 'RK-759'

<h2>Contributors:</h2>
Abhimanyu Gabhrani<br>
Chirag Mathur<br>
Anand Singh Gahlout<br>
Ayushi Khandelwal<br>
Ayushi Joshi<br>

<h2> Purpose of the Project </h2>
The project was made in order to help the specially abled people by making a significant change in their day-to-day lifestyle and making them more inclusive in our society. Our focus is on the group which is speech impaired, which includes both people who cannot speak and the ones who cannot hear as well.

<h2> Outcome </h2>
The project can enable any speech impaired person to use their knowledge of Sign Language and communicate efficiently with the common folk via audio and video calls.

<h2> Requirements and Dependencies: </h2>
<ul>
  <li>Python 3.9.10 or above</li>
  <li>OpenCV</li>
  <li>Jupyter Notebook</li>
  <li>Pyaudio</li>
  <li>PYTTSX3</li>
  <li>Speech-Recognition</li>
</ul>
<br>
  The rest of the dependencies are installed in the code
  
 <h2> Details of the Project </h2>
 The entire program is broken down into two parts:<br>
 <ul>
  <li>Sign Language to Audio (for speech impaired to speak)</li>
  <li>Speech to Sign Language (for speech impaired to listen)</li>
 </ul>

<h3>1. Sign Language to Audio:</h3>
<ul>
  <li>Create a virtual python environment and run the jupyter notebooks.</li>
  <li>Open the jupyter notebook 'Image Collection'. This script is to be run only once during the initial setup so as to train the model according to your environment and yourself.</li>
  <li>Edit the labels section to increase the vocabulary of your model. The words mentioned in the labels dictionary will be the ones which will be detected by the model.</li>
  <li>Run the code block by block from the beginning. All the dependencies will also be installed automatically.</li>
  <li>The script will run your webcam and as per the instructions written, show the hand sign of the respective word so that it's images can be captured.</li>
  <li>Now, run the jupyter notebook named 'Training and Detection'.</li>
  <li>If doing initial setup, run every code block. Otherwise check the labels and run only the necessary ones.</li>
  <li>The script will train the model and speak the input given by you via hand signs.</li>
</ul>

<h3>2. Audio to Sign Language:</h3>
<ul>
  <li>Run the script 'speech to text'.</li>
  <li>>Give your voice input when the console says 'Listening..'</li>
  <li>Your speech input will be converted into Sign Language</li>
