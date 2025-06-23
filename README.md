<h1>✋ Hand Gesture-Based Volume Control System</h1>

<p>
This project is a real-time hand gesture-based volume control system built using <strong>Python</strong>, <strong>OpenCV</strong>, <strong>MediaPipe</strong>, and <strong>PyCAW</strong>. It allows users to control the system volume by simply moving their fingers in front of the webcam.
</p>

<h2>🔧 Features</h2>
<ul>
  <li>Detects hand landmarks using <strong>MediaPipe</strong></li>
  <li>Tracks thumb and index finger tips</li>
  <li>Calculates the distance between fingers to adjust system volume</li>
  <li>Displays a live volume bar and percentage on the screen</li>
  <li>Provides real-time feedback with smooth and responsive UI</li>
  <li>Runs directly from webcam input</li>
</ul>

<h2>🛠 Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>OpenCV</li>
  <li>MediaPipe</li>
  <li>PyCAW (Python Core Audio Windows Library)</li>
  <li>NumPy</li>
</ul>

<h2>📂 File Structure</h2>
<ul>
  <li><code>handTrack.py</code>: Hand tracking module using MediaPipe</li>
  <li><code>test.py</code>: Main application to control volume based on finger distance</li>
</ul>

<h2>📌 How It Works</h2>
<ol>
  <li>The system captures video from the webcam.</li>
  <li>Detects the user's hand and tracks landmarks.</li>
  <li>Measures the distance between the <strong>thumb tip</strong> and <strong>index finger tip</strong>.</li>
  <li>Maps that distance to the system's audio volume level.</li>
  <li>Updates the volume and shows a visual representation on the screen.</li>
</ol>

<h2>▶️ Usage</h2>
<p>Run the following command to start the application:</p>
<pre><code>python test.py</code></pre>
<p>Press <code>q</code> to quit the program.</p>

<h2>⚠️ Requirements</h2>
<ul>
  <li>Windows OS (required by Pycaw)</li>
  <li>Webcam</li>
  <li>Python packages:</li>
  <ul>
    <li>opencv-python</li>
    <li>mediapipe</li>
    <li>pycaw</li>
    <li>numpy</li>
    <li>comtypes</li>
  </ul>
</ul>

<p>Install all dependencies:</p>
<pre><code>pip install opencv-python mediapipe pycaw numpy comtypes</code></pre>
