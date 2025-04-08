# Harry-Potter-Invisibility-Cloak
Ever dreamed of having an Invisibility Cloak like Harry Potter?
This project brings that magic to life using Python and OpenCV!
By detecting a specific color (e.g., a red cloak), we can replace that region with the background — making you look invisible!

✨ Features

Real-time invisibility effect 🪄

Color detection using HSV color space 🎨

Simple OpenCV operations for background replacement 📷

Inspired by the Invisibility Cloak from the Harry Potter universe 🧥


📋 Requirements

Python 3.x
OpenCV


🛠️ How to Run

Clone/download this repository.

Connect your webcam.

Run the script.


🎯 How It Works

Capture the Background: Before starting, the background is recorded without any movement.

Detect Cloak Color: We detect a specific color (say, red) using the HSV color space.

Create a Mask: The cloak is isolated using masks.

Replace with Background: The detected cloak region is replaced by the previously captured background.

Result: You disappear — just like magic!

