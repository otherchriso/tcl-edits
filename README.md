# Touring Car Legends mod - bugfixes and edits

This repository contains edits to the Touring Car Legends (aka "TCL") mod for Assetto Corsa. The mod itself can be downloaded via https://thracing.de/touring-car-legends/

![Mini_Cooper_and Hillman Imp battling at Kyalami_1967](https://github.com/user-attachments/assets/643c4bee-f28c-4871-8be5-873618e4d39f)

Many of the corrections here are intended to be applied to an unpacked `data.acd` file for the applicable cars. To do that with Content Manager, first ensure "Developer Mode" is enabled by double-clicking many times on the version number shows on Content Manager's "about" page. With Developer Mode enabled, an "Unpack data" button becomes available for each car in the Content menu. Clicking that will then create a `data` directory for the car; use the directory structure obvious in this repository to know what to edit.

Optionally, the "Pack data" option will create a new `data.acd` file compiled from the contents of the `data` directory. Please note that a `data.acd` file is created using the directory label for the car itself as a key within its encoding, so a `data.acd` file needs to be unpacked from within the same directory name for which it was packed, to prevent corruption.

## Fixes in this repo

### TCL AMG 300 SEL 6.8 'Rote Sau'
* Included the lookup table(s) referenced by tyres.ini for thermal properties and wear. This prevents CSP's extended physics from making it impossible to drive, and also fixes data shown in some GUI apps such as ProTyres.

### TCL Austin Healey 3000 MK II
* Included the lookup table(s) referenced by tyres.ini for thermal properties and wear. This prevents CSP's extended physics from making it impossible to drive, and also fixes data shown in some GUI apps such as ProTyres.

### TCL BMW 2002
* Included the lookup table(s) referenced by tyres.ini for thermal properties and wear. This prevents CSP's extended physics from making it impossible to drive, and also fixes data shown in some GUI apps such as ProTyres.

### TCL Ford Escort
* Included the lookup table(s) referenced by tyres.ini for thermal properties and wear. This prevents CSP's extended physics from making it impossible to drive, and also fixes data shown in some GUI apps such as ProTyres.

### TCL MG-MGA (Race)
* Included the lookup table(s) referenced by tyres.ini for thermal properties and wear. This prevents CSP's extended physics from making it impossible to drive, and also fixes data shown in some GUI apps such as ProTyres.

### TCL Renault Alpine A110
* Included the lookup table(s) referenced by tyres.ini for thermal properties and wear. This prevents CSP's extended physics from making it impossible to drive, and also fixes data shown in some GUI apps such as ProTyres.

## Enhancements in this repo

### TCL AMG 300 SEL 6.8 'Rote Sau'
* Animated wipers (requires CSP)

### TCL Austin Healey 3000 MK II
* Animated wipers (requires CSP)

### TCL BMW 2002
* Animated wipers (requires CSP)

### TCL Datsun 510
* Animated wipers (requires CSP)

### TCL Ford Fairlane
* Animated wipers (requires CSP)

### TCL Hillman Imp
* Animated wipers (requires CSP)

### TCL Jaguar MK2
* Animated wipers (requires CSP)

### TCL Lotus Cortina MkI
* Animated wipers (requires CSP)

### TCL Mazda RX-3 GT
* Animated wipers (requires CSP)

### TCL MG-MGA (Race)
* Animated wipers (requires CSP)

### TCL Porsche 911RS 2.7
* Added headlights, brake lights dashboard gauge lights and enabled hazard flashers when in pitlane. 
    * _Note: these lights.ini changes are imperfect and incomplete and unlikely to be revisited because [JUngle Man's edits](https://www.overtake.gg/threads/touring-car-legends-porsche-911-rs-2-7-lights-fix.272786/), released after I created these, are superior in every way and you should install those._
* Animated wipers (requires CSP)

### TCL Renault Alpine A110
* Animated wipers (requires CSP)

## License

This repo is licensed with GPLv3 but that obviously doesn't apply to any content here which derives from the TCL mod itself, so please keep all that in mind when respecting the copyrights.
