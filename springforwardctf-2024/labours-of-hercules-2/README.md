# labours-of-hercules-2

## Description
* Note: This Challenge will be locked until they solve "Labours of Hercules 1"
* You have slayed the mighty Nemean Lion and skinned it for your armour. This other image was sent to me but some werid, cryptic message appeared and I can't seem to find it anymore.

## Hint
* This creature lead to Hercules dying later in his life. Hence the picture.

## Solution
* First download the image in Kali.
* Download steghide if you haven't already in the Kali distro.
* Enter this command to extract the flag: `steghide extract -sf hercules`.jpeg There is no password to get into the file.
* Then cat it via `cat flag.txt`
* The file will say: `Wt o vsor wg qih ctt, hkc acfs gvozz hoys whg dzoqs. Kvoh qfsohs sjsbhiozzm zsor hc hvs rsawgs ct Vsfoqizsg?`
* This is a rotation cipher and translate to: `If a head is cut off, two more shall take its place. What create eventually lead to the demise of Heracules?`
    * This creature is the Lernaean_Hydra.
* Flag: `nicc{Lernaean_Hydra}`