# Steganography


# Secure Data Hiding in Images using Steganography (Python)

This Python-based project demonstrates how steganography can be used to hide a secret message within an image. By leveraging Python libraries such as OpenCV and Tkinter, this project provides a simple yet effective way to encrypt and decrypt text messages embedded inside images. The encryption process embeds the secret message into image pixels using a diagonal embedding technique, ensuring the data remains hidden and can only be securely retrieved with the correct passcode.

Features:

1. Data Hiding (Encryption):
   - Hide a secret text message inside an image.
   - The message is encoded using ASCII values of each character and embedded into the image pixels with a diagonal embedding approach.
   - The altered image is saved in a lossless PNG format to ensure the original image quality and hidden data remain intact.

2. Decryption:
   - Retrieve the secret message by providing the correct passcode and the message length.
   - The decryption process decodes the ASCII values to reconstruct the original message.

Requirements:

- Python
- OpenCV (cv2)
-pip install opencv-python

