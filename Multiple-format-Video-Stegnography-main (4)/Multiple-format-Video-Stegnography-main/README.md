# Multiple-format-Video-Stegnography Using AES and RSA Algorithm
This Is a Video Steganography project contains multiple format

## This project is modified and many upadates has been done in this project

# Tested On :
 
- Ubuntu 

## Features
 
- Encrypt and Encode Text In Video.
- Encrypt and Encode Video In Video.
- Encrypt and Encode Audio In Video.
- Encrypt and Encode Images In Video.
- Encrypt and Encode Text document In Video.
- Encrypt and Encode all format of data together too In Video.
- Decode and Decrypt all these format  From Video.
- Choose AES-256 or RSA Encryption.
- Apply RSA Encryption For AES key.
- Choose Any Frame Number.
- Encrypt Frame Numbers With AES or RSA.
- Save Encrypted Frame Numbers Inside Another Image like Image.png , The Encryoted Image Will Be Stored As Image-enc.png .

## Cracking Keys ?

### AES-256 Breaking :  
- Takes 27,337,893 trillion trillion trillion trillion years to bruteforce key using single computer.
- Takes 13,689 trillion trillion trillion trillion years to bruteforce key using all computers in the world.
### RSA-5000 Breaking :
- 2^1024 / (5.000.000 * 16 * 60 * 60 * 24 * 365) Years to compute the key using brute force, which is about 10^292 years to break RSA-1024.
- We use RSA-5000,I leave it to your imagination on long it takes to break RSA.
## Installation

1 ) Clone project with git

2 ) Go to the directory & install requirements 
```bash
pip install -r requirements.txt
```
a) Install this for  Audio
```
pip install SpeechRecognition
```
b) Install Simple Colors Lib for Colors purpose used in the terminal.
```
pip install simple-colors
```
d) Install  gTTs Lib for Voice .
```
pip install gTTs
```
3 ) Install FFmpeg </br>
   [Changes depending on the operating system you are using.](https://ffmpeg.org/download.html) </br>
   For Linux & WSL use :
```bash
sudo apt install ffmpeg -y
```
4 ) Create RSA keys.
```bash
python3 rsagen.py
```


## Usage/Examples
1 ) Encryption & Encoding
```bash
python3 encode.py <video-to-encode-with-extension>
```
  Example: 
  ```
  python3 encode.py srutest.mp4
  ```

2 ) Decoding & Decryption
```bash
python3 decode.py <video-to-decode-with-extension>
```
  Example: 
  ```
  python3 decode.py video.mov
  ```


![Screenshot from 2023-03-24 20-41-45](https://user-images.githubusercontent.com/114608491/227566643-65f36922-38fb-40ea-88a5-035803f8c062.png)

## ScreenShots![Screenshot from 2023-03-24 20-42-46](https://user-images.githubusercontent.com/114608491/227566659-f094a231-7a16-4e09-9b49-adf8e2881f24.png)![Screenshot from 2023-03-24 20-42-52](https://user-images.githubusercontent.com/114608491/227566667-f205b7a3-fc5c-41d5-b089-6650781d6991.png)


![Screenshot from 2023-03-24 20-42-22](https://user-images.githubusercontent.com/114608491/227566652-f766bcb4-1106-469c-b402-22cb79465005.png)


## Important Note

1. Make sure that if you want to run the project in GUI mode then you have to place the files in encode and decode folder files in the root directories
