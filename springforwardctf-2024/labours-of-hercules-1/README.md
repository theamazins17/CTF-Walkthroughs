# labours-of-hercules-1

## Description
* I was sent this picture of the mighty Greek hero Hercules. However, something seems odd about it and I can't put my finger on it. Oh...I almost forgot this catchpharse was sent with the picture: n3m3anl10n.

## Hint
* Make sure to spell out the number of the format you are choosing

## Solution
* First download the image in Kali.
* Download steghide if you haven't already in the Kali distro.
* Enter this command to extract the flag: `steghide extract -sf hercules.jpg`
* Enter the password listed from the prompt: `n3m3anl10n`.
* Then cat it via `cat flag.txt`
* The text file will ask you, How long in days or months it took Hercules to slay the creature?
    * The creature is the Nemean Lion and it took: 1 month or 30 days
* Spell out the number of the format of your choosing
* Flag: `nicc{Thirty_Days}` or `nicc{One_Month}`