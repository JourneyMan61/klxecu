# klxecu

Speeduino based ECM for the fuel injected KLX 250 and 300. *theoretically* compatible with the speeduino NO2C firmware options. It has only one fuel and ignition channel, but adds a few extra features, namely:

- control of the check engine/temperature warning lights on the dashboard
- control of the secondary throttle plate in the intake (handled by a separate ATTiny processor- this isn't "fast idle" like what's supported natively by speeduino)
- control of the bike's safety switches (also handled by the ATTiny), will pull the mega's reset pin low if you fall over, or try to put the bike in gear when the kickstand is down, etc.
- auxiliary "self diag" pin connected to the speeduino processor

This project borrows from the following:

- [NO2C Speeduino - https://github.com/turboedge/SpeedyBoards](https://github.com/turboedge/SpeedyBoards) for parts of the board design
- [Speeduino Hardware - https://github.com/speeduino/Hardware](https://github.com/speeduino/Hardware) for the VR conditioner
- [Speeduino Firmware - https://github.com/noisymime/speeduino](https://github.com/noisymime/speeduino) for the ECM firmware
