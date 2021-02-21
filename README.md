# Flash CHIP from Archlinux
A script that simplifies the flashing process for the C.H.I.P and PocketC.H.I.P Computer.
It is Designed to run on ArchLinux.

## Instructions
1. Remove the C.H.I.P from its case (in case you have a Pocket C.H.I.P).
2. Connect the FEL and a GND(Ground) pin of the C.H.I.P with a wire or paperclip.
3. Connect the C.H.I.P micro USB port to a USB port of your ArchLinux machine.
4. In the terminal of your ArchLinux machine run the following commands:
5. Make sure that the LEDs beside the micro USB port of the C.H.I.P have turned on
    - ` git clone https://github.com/richardschembri/Flash-CHIP` to clone this repository.
    - `cd` into the location where you stored this repository.
    - run `sudo chmod +x Flash.sh`
    - run `./Flash.sh`
    - Select the image you wish to flash on your CHIP.
    - You might be prompted for your sudo password.
    - The script should run automatically from this point on.

## Further setup on the C.H.I.P
When you boot in the C.H.I.P, in order to be use `apt-get update` make
sure to remove the sources related to NextThing.co in
`/etc/apt/sources.list`

  
## References
* C.H.I.P tools taken from https://archive.org/details/C.h.i.p.FlashCollection
* The script downloads the C.H.I.P images from http://chip.jfpossibilities.com/chip/
