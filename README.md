# VolumeControlApp
This application harnesses the power of computer vision to allow users to adjust their computer's volume using hand gestures captured in real-time through a webcam.

The application offers the following features:

Gesture Recognition: It detects specific hand landmarks and calculates the distance between them to determine the desired volume level. Primarily, it focuses on the distance between the thumb and the index finger.

Visual Feedback: Alongside adjusting the volume, the application provides a visual representation of the current volume level in a gradient-filled canvas. This canvas dynamically adjusts its fill color based on the volume, providing immediate feedback to the user.

Decibel Scaling (Version 2.0): The newer version of the application includes a function to convert linear volume scales to decibels, offering a more precise volume control mechanism.

Logging: The application maintains a log file (app.log) to record any issues or important events, ensuring smooth troubleshooting and monitoring.

Integration with Audio Utilities: The application seamlessly interfaces with the system's audio utilities to adjust the master volume level.

Modern UI: The gradient canvas employed in the application adds a modern touch to the UI, enhancing user experience.
