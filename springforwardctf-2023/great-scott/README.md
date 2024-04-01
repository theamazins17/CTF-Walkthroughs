# great-scott

## Description
* Decode the coded message in the jpg file!

## Hint
* Use a steghide program

## Solution
* Download the file
* Using steghide in a Kali terminal, enter this command: `steghide extract -sf great-scott.jpg`
* Hit enter once you see `Enter passphrase:` as there is no password to get into the picture. You will see a file called "flag.txt" be extracted from the picture.
* Now type: `cat flag.txt`
* You will see the flag printed out
* Flag: `nicc{It's_All_About_the_Mets!}`
