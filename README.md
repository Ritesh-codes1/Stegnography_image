**Secure Data Hiding in Images Using Steganography**

**Introduction**

This project implements a secure data hiding technique using steganography to embed encrypted information within images. Only authorized users with the correct password can decrypt and extract the hidden data. The system ensures data confidentiality while maintaining image quality.

**Features**

Password-Protected Decryption – Ensures only authorized users can access the hidden data.

LSB-Based Steganography with Encryption – Double-layer security using Least Significant Bit (LSB) embedding.

Minimal Image Distortion – Optimized encoding to prevent noticeable changes.

Multi-Format Support – Works with PNG, JPEG, BMP images.

Automated File Handling – Efficient reading, writing, and retrieval using Python’s OS module.

**Technologies Used**

Python – Core programming language.

OpenCV – Image processing and manipulation.

NumPy – Efficient handling of image matrices.

OS Module – File operations and management.

File Handling – Read, write, and extract hidden data securely.

**Installation**

  Clone the repository:

https://github.com/Ritesh-codes1/Stegnography_image.git

  Install dependencies:

pip install opencv-python numpy

**Usage**

  Hide Data in Image:

Run the script and provide an image, text file, and password.

python hide.py

  Extract Hidden Data:

Use the correct password to retrieve the data.

python extract.py

**Future Scope**

Advanced Encryption – Stronger security algorithms.

AI-Based Steganography – Improve resistance against detection.

Real-Time Applications – Web and mobile support.

Multi-Media Support – Expand to video/audio steganography.

Cloud Integration – Secure cloud-based hidden data storage.

**Contributing**

Contributions are welcome! Feel free to open issues or submit pull requests.

**License**

This project is licensed under the MIT License. See the LICENSE file for details.
