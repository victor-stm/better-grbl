![GitHub Logo](https://github.com/gnea/gnea-Media/blob/master/Grbl%20Logo/Grbl%20Logo%20250px.png?raw=true)
better ;)
***
Original GRBL firmware gnea/grbl [bfb67f0](https://github.com/gnea/grbl/tree/bfb67f0c7963fe3ce4aaf8a97f9009ea5a8db36e) with merged backlash from shooter64738/rgbl [ef1c7aa13](https://github.com/shooter64738/grbl-mega/tree/ef1c7aa133d311e5682ece448e15063e2463fa7f) and some tips from [beshio/milling](https://github.com/beshio/milling)  

***
Original readme should be there: [gnea/grbl](https://github.com/gnea/grbl/)
***

### Build & flash

Build with Arduino IDE is recommended. Don`t know why, but Xloader fails to upload firmare more than ~30750. Arduino's avrdude can uploade with a few hudreds bytes more, and it is critical for this build.

Original build [instruction is here](https://github.com/gnea/grbl/wiki/Compiling-Grbl#if-you-are-using-arduino-ide-2x).

### Extra features:

- Backlash compensation ($140, $141, $142 - positive offset for X, Y, Z)
