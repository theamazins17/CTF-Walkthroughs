# surf-n-turf

## Description
Our NICC agents have received these files from high command to help determine a potential base of operations. High command
has encrypted the location of the potential base of operation to prevent the Rogue AI from knowing their movements. The file
containing a voice prompt will help you get into the file telling where the potential base may be.

Note: Once you figure out the location and there are spaces, replace them with underscores. For example: jctf{Name_of_Location}

## Solution Steps
* First listen to the .wav file. As this will give you the password, in a sense.
* You will hear this from the .wav file: `Easy Queen Nan Quuen Tare Charlie Fox Queen Tare King X-Ray George Tare` This is from the [WWII Allied Military Phonetic Alphabet](https://en.wikipedia.org/wiki/Allied_military_phonetic_spelling_alphabets)
* Once you figured this out, this would now become --> `EqnqtcfqTkxgt`
* Throw this string into a Casear Cipher decoder --> `ColoradoRiver`
* Open the .txt file with [AES Crypt](https://www.aescrypt.com/) and input the decoded string as the password
* You will see the the location encoded `MzkuNzU1ObAgTiwgMTA0Ljk5NDKwIFc=`
* Put this string through a base64 decoder and it should translate to `39.7559° N, 104.9942° W`
* Enter these coords into a search engine and that name of the location should be `Coors Field`
* Flag: `jctf{Coors_Field}`
