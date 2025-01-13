# Puara

Puara is a framework for building and deploying embedded systems, especially in the realm of Augmented and Digital music instruments (AMIs/DMIS), new media installations, and New Interfaces for Music Expression (NIME).

*Puara* means "to tie" or "connect" in [Old Tupi](https://en.wikipedia.org/wiki/Tupi_language). It is currently developed at the [Société des Arts Technologiques (SAT)](https://sat.qc.ca/en/innovation/) and the the [Input Devices and Music Interaction Laboratory (IDMIL)](http://www-new.idmil.org/).

## Organisation
The repositories in the puara framework can be rougly separated into 3 categories: Core libraries, Utilities, and AMI/DMI Projects.
- Core libraries:
    - [puara-gestures](https://github.com/Puara/puara-gestures): a library implementing IMU gestures for embedded systems.
        - `puara-gestures` uses the [3rdparty](https://github.com/Puara/3rdparty) repository as a submodule to contains its external dependencies.
        - `puara-gestures/exampleProjects` is a directory containing examples project that can be helpful in getting started with `puara-gestures`.
    - [puara-module](https://github.com/Puara/puara-module): a library for connecting music controllers to the Puara framework via [Open Sound Control (OSC)](https://opensoundcontrol.stanford.edu/) messages.
        - [puara module templates](https://github.com/Puara/puara-module-templates) is a repository that contains example template projects that can be used to get started with the various use cases of the Puara Module library.
- Utilities:
    - [puara-controller](https://github.com/Puara/puara-controller): a utility program that can convert game controller data into [OSC](https://opensoundcontrol.stanford.edu/) messages.
    - [puara-serial-manager](https://github.com/Puara/puara-serial-manager): a command line tool to interface with Puara-based instruments.
- AMI/DMI projects:
    - [Guitar AMI MPU](https://github.com/Puara/GuitarAMI_MPU): This Media Processing Unit (MPU) is a full media system based on the Raspbery Pi platform and supporting all Puara features.
    - [Guitar AMI Module](https://github.com/Puara/GuitarAMI): an Augmented Musical Instrument (AMI) using an acoustic guitar.
    - [T-Stick](https://github.com/Puara/T-Stick): A popular Digital Musical Instrument (DMI), in development since 2006.
    - [M5StickC](https://shop.m5stack.com/products/m5stickc-plus-esp32-pico-mini-iot-development-kit)-based instruments/repos:
        - [AMIwrist](https://github.com/Puara/AMIwrist): a controller for AMIs.
            - [Freeze](https://github.com/Puara/Freeze): a piece for the AMIwrist.
        - [Probatio](https://github.com/Puara/Probatio): firmware for the M5StickC.

## Performances
Some performances using the Puara Framework can be seen on YouTube:

- [Insomnia Rain (Derek Cooper](https://youtu.be/Ho9kRBwjyEQ) at the [live@CIRMMT 20th Anniversary Video Series](https://www.cirmmt.org/en/events/live-cirmmt/video-series)
- [The Turing Test (Alex Burtzos)](https://youtu.be/pFRPbD7EmvQ) at the [live@CIRMMT 20th Anniversary Video Series](https://www.cirmmt.org/en/events/live-cirmmt/video-series)
- [Freeze! for augmented drumkit (AMIWrist-Puara)](https://youtu.be/4jlAkBIFVPU)
- [Trouveur (Víctor Báez) - GuitarAMI version](https://youtu.be/lEWevEhnPPg)
- [Unexpected (Martin Daigle and Marie Lévêque)](https://www.youtube.com/watch?v=WiXPAaQClEk&authuser=0) at [Banff Centre's Evolution: Classical program](https://www.banffcentre.ca/fr/events/evolution/classical/ellsworth-allegra-daigle-leveque)
