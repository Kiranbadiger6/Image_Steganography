Image Steganography in C

A C-based Image Steganography project that hides secret text data inside BMP images using the Least Significant Bit (LSB) technique. The project supports both encoding and decoding of hidden information.

🚀 Features
🔒 Encode secret data into BMP images.
🔓 Decode hidden data from stego images.
📁 Supports secret file extension and file size encoding.
🖼️ BMP image processing and capacity checking.
🔑 Magic string verification during decoding.
💾 Binary file handling using C.
🛠️ Technologies & Concepts
Language: C
Image Format: BMP
Technique: LSB Steganography
Concepts: Pointers, Structures, Arrays, Strings, File Handling, Bitwise Operations, Command-Line Arguments.
⚙️ Working
Encoding
BMP Image + Secret File
          ↓
    Check Capacity
          ↓
    Encode LSB Data
          ↓
       Stego Image
Decoding
     Stego Image
          ↓
   Verify Magic String
          ↓
    Extract Hidden Data
          ↓
      Secret File
▶️ Usage
Encode
./steganography -e source.bmp secret.txt stego.bmp
Decode
./steganography -d stego.bmp output
