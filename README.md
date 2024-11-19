Image Encryption Tool

This project is a simple Image Encryption Tool that uses pixel manipulation techniques to encrypt and decrypt images.
The tool applies basic operations like swapping pixel values or applying mathematical transformations to each pixel to obfuscate the original image. 
By reversing the encryption operations, users can decrypt the image back to its original form.

Features
    Encrypt Images: Convert an image to an encrypted form using pixel manipulation (e.g., swapping pixels or applying mathematical operations).
    Decrypt Images: Revert the encrypted image back to its original form by performing reverse operations.
    Simple & Easy-to-Use: Suitable for learning cryptography and image processing basics.

Technologies Used
    Python: The main programming language for this project.
    Pillow (PIL): Python Imaging Library for handling image loading, manipulation, and saving.

How It Works

Image Encryption:
    The tool reads the image and converts it to a list of pixel values.
    A series of operations, such as swapping pixel values or modifying the pixel intensity using basic math (e.g., adding/subtracting values), are applied to each pixel to create an encrypted version of the image.
    The encrypted image is saved and can be shared or transmitted securely.
    User can browser pictures need to be encrpyted and save them on thier machine local

Image Decryption:
    The tool reads the encrypted image.
    The reverse of the encryption operations are applied to retrieve the original pixel values.
    The decrypted image is saved as the original.

Installation

To use this tool, follow these steps:

Prerequisites:
    Python 3.x: Make sure Python is installed on your system.
    Pillow Library: Install the Pillow library for image processing.

Installation Steps:
1. Clone the repository to your local machine:
    >>> git clone https://github.com/your-username/image-encryption-tool.git
    >>> cd image-encryption-tool

2. Install the required Python dependencies:
    >>> pip install -r requirements.txt
    

### to Run the program: PixelManipulation.py

