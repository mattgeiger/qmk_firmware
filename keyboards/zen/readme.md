# Zen Keyboard

A split ergo keyboard with a few goals in mind:

- Be as thin as possible. Other split KBs (Let's Split, Nyquist, Iris) are 15.2mm thick. The Zen is only 8.0mm thick.
- Layout designed for gaming. 1.5u pinky keys, ortho alphas, and angled thumb keys. After trying Ortholinear, Atreus62, and Ergodox, this is the best layout for gaming and typing.
- RGB backlighting. 16 WS2812b LEDs shine through the perimeter switches. The SK6812 variant are cheap and easy to solder.
- Price. Using Arduino Pro Micro, SK6812 LEDs, and PCB FR4 for the case, the cost of each half without switches or caps can be reduced to under $20 when purchased at volume.

Keyboard Maintainer: [Legonut](https://github.com/Legonut)  
Hardware Supported: Zen rev1  
Hardware Availability: [RGBKB.net](https://www.rgbkb.net/)

A build guide and more info for this keyboard can be found here: [Zen Build Guide](https://legonut.gitbooks.io/zen-keyboard/content/).

Make example for this keyboard (after setting up your build environment):

    make zen/rev1:default

See [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) then the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information.
