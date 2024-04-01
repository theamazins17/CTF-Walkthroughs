# i-have-become-death - medium

## Description
* Oh boy... Things are becoming hectic and it is stressing me out. My computer seems to be haunted as it prevents me from starting up my computer. Thankfully, after multiple resets - it stopped. I checked the logs and it is in these weird folders named after COD maps. Can you discover which file, with its extension, and the time, keep as is, it was executed?
* Flag Format: NICC{nameOfFile.extension_00:00}

## Solution Steps
* Must download and unzip the file
* Users must search through the text files to find a suspicious file of a known DoS attack.
* The file is under the `nuketown2025` folder and the name of the file is `MicrosoftUpdateTaskForkBomb`.
* The user must then find the name of the file(at the bottom of the page) and the time, as is, it was uploaded(in the middle of the page).
* Flag: `NICC{bomb.py_14:55}`
