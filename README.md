# WSB-Worlds-Smallest-Board
A single switch PCB that adds per-key RGB support but provides zero cable routing.

"WSB", or "world's smallest board", is intended to slip into the space between a hotswap socket and a keyswitch.

It provides absolutely zero cable routing and no place to mount a diode.

However, it has solder pads for mounting an SK68 mini-e RGB LED, which means you can upgrade your existing handwired build to an RGB keyboard without changing any wiring - as long as your build already had hotswap sockets. The extremely small footprint of the "world's smallest board" means most people shouldn't even need to measure or check spacing, except for the height of the RGB LED itself.

The WSB was created for the Dactyl Chimera, which may seem strange because the Dactyl Chimera can already accommodate large single-switch PCBs like the [Amoeba](https://github.com/mtl/keyboard-pcbs) and the [MxLEDBitPCB](https://swanmatch.github.io/MxLEDBitPCB/) (hint: these are both great alternatives!) However, I wanted to create something that could work with basically any keyboard and would be a great introduction to KiCAD, which I know nothing about.

WSB will also include a PCB adapter for socketing a Pro Micro and giving it screw holes. Attempting to 3D print a microcontroller tray has been a real challenge.
