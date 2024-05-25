<b>Image Encryption Tool</b>

This Python program implements a simple image encryption tool using pixel manipulation techniques. The program can encrypt and decrypt images by performing basic mathematical operations on the pixel values. It is designed to be user-friendly, guiding users through the encryption and decryption processes with clear prompts.

<b>Features</b>

- Image Encryption: Users can encrypt an image by applying a mathematical operation to each pixel value, effectively altering the image.
- Image Decryption: The program can reverse the encryption process to restore the original image.
- User Input: Users can specify the image file and the encryption key.
- File Handling: The program saves the encrypted and decrypted images to specified file paths.

<b>How It Works</b>

1. Encrypt Image: Multiplies each pixel value by a key and then divides by the key plus one to create the encrypted image.
2. Decrypt Image: Reverses the encryption process by multiplying each pixel value by the key plus one and then dividing by the key.

<b>Usage</b>
<ol>
<li>Run the Program: Execute the script to start the Image Encryption program.</li>
<li>Select Action: Choose 'e' for encryption, 'd' for decryption, or 'q' to quit.</li>
<li>Encrypt Image:</li>
  <ul>
    <li>Enter the encryption key.</li>
    <li>Specify the location or URL of the image to be encrypted.</li>
  </ul>
<li>Decrypt Image:</li>
  <ul>
    <li>Enter the decryption key.</li>
    <li>Specify the location of the encrypted image.</li>
  </ul>
<li>View Results: The program saves and indicates the location of the encrypted and decrypted images.</li>
</ol>

This code was developed as part of my internship at The Prodigy Infotech, showcasing a basic approach to image encryption and decryption through pixel manipulation.
