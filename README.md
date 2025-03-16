# Nigma_COSA
COSA is a C based *Cross Operating System API* in user space made for raw usage and performance yet staying simple, while being free as in both speech and beer(Libre and Gratis, use it with freedom and without charge).

## Overview
The goal with COSA is to give a raw path of control towards the Kernel and available Drivers no matter what OS environment it may be on, thru simplistic functions while said functions does not add unnecessary bloat(Every function builds upon each other, even internally).

This allows applications to complete their purpose without having to worry about the burden and asterisks that comes with every OS, like How/Where and What Drivers/Packages are available..

COSA is ***NOT*** cross *Platform*(For now), it does not Download/Install needed Packages nor is it a OS/Driver on it's own. It can be thought of a boilerplate system where it only compiles used functionality, it only *abstracts* what is already provided for the user space.