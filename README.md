Steganography - Hide a Secret Text in an Image

Overview

This project is a Python-based steganography application that allows users to hide and reveal secret text messages within image files. The application is built using Tkinter for the graphical user interface (GUI) and the stegano library for Least Significant Bit (LSB) steganography.

Features

User-friendly GUI built with Tkinter.

LSB Steganography for embedding and extracting hidden messages in images.

Supports PNG and JPEG images for encoding and decoding.

Security Key Protection to ensure only authorized users can reveal hidden messages.

Image Display and Saving with seamless handling of modified images.

Cross-platform compatibility (Windows, Linux, macOS).

Technologies Used

Python (Programming Language)

Tkinter (GUI Development)

Pillow (PIL Fork) (Image Processing)

Stegano (Steganography Library)

Spyder IDE (Development Environment)

Installation

Install Python (Ensure Python 3.x is installed on your system)

Install required dependencies:

pip install tkinter Pillow stegano

Clone the repository:

git clone https://github.com/DouthubajiNaveen/steganography-app.git
cd steganography-app

Run the application:

python steganography.py

Usage

Hiding a Message

Open the application.

Select an image file (PNG/JPEG).

Enter the secret message and a security key.

Click 'Hide' to embed the message into the image.

Save the modified image.

Revealing a Message

Load the steganographed image.

Enter the correct security key.

Click 'Show' to extract the hidden message.

Project Structure

steaganography-app/
│── steganography.py  # Main application script
│── requirements.txt  # List of dependencies
│── README.md         # Project documentation
│── assets/           # Contains sample images

License

This project is licensed under the MIT License.


