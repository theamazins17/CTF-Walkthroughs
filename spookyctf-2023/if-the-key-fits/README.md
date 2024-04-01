# if-the-key-fits

## Description
* I am trying to escape this 64-story horror house and the only way to escape is by finding the flag in this text file! Can you help me crack into the file and get the flag? The only hint I get is this random phrase: MWwwdjM1eW1tM3RyMWNrM3Q1ISEh

## Solution Steps
* You must first get the phrase at the end and decode it from base64 --> which should translate to ```1l0v35ymm3tr1ck3t5!!!```
* You must then download [AES Crypt here](https://www.aescrypt.com/). Here you will be able to decrypt the file.
* Once AES Crypt is downloaded, the file must be downloaded(obviously). Right-click the text file and click the option ```Open with AES Crypt```.
* Enter the password decoded from base64 when prompted and the file will decrypt, showing the flag.
* Flag: `NICC{1-4m-k3yn0ugh!}`
