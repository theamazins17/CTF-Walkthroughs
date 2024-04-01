# this-is-not-the-flag-you-are-looking-for

## Description
I received this note with this code. Enclosed with it, it asked for help finding a specific US Navy ship that was linked
to this code. Can you decipher this code to give me the name of this US Navy ship and the type of ship it was with its
associated number?

Example:jctf{USS_Name_Of_Ship_TypeOfShip_Number}

## Solution Steps
* Get the file downloaded.
* You will see this are Semaphore Signals
* There are two ways you can do this:
    * Visit the Semaphore Signals [wiki](https://en.m.wikipedia.org/wiki/File:Semaphore_Signals_A-Z.jpg)
    and manually decode from there  OR
    * You can use this [site](https://www.dcode.fr/semaphore-flag) to decode it as well
* The flags should translate to ```Firepower for Freedom```.
* There are two ships with this motto USS New Jersey BB-62 and USS New Jersey SSN-796. The one that is SSN-796 does not fit these criteria as it is currently being constructed.
  The one that is BB-62 is therefore the right one. 
* Flag: `jctf{USS_New_Jersey_BB_62}`
