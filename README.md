# Overview

This project is a modification of the original Repeater example found here: 
https://github.com/m5stack/M5-ProductExampleCodes/blob/master/Core/Atom/AtomEcho/Arduino/Repeater/Repeater.ino

The project goal is to make a small handheld looper that can work with
modular eurorack gear.

 ![Alt text](https://static-cdn.m5stack.com/resource/docs/products/atom/atomecho/atomecho_01.webp "Pinouts")
## Hardware Requirements

- M5 Stacks Atom Echo
- (Optional) Stereo Jack Mod (see below)

## Building

- Use the instructions here to set up your M5 Stacks Echo: https://ftdichip.com/drivers/vcp-drivers/
 and the m5-atom platform is needed to be installed: https://docs.m5stack.com/en/quick_start/atom/arduino
- Build using standard Arduino software

## Stereo Jack Mod

- The sticker on the side of the side can be removed which is the FCC sticker.
- Once the sticker is off, you can actually easily press a thumb against the area near the sticker, the case will pop off
- With the case off, you should carefully fold it open
- Without breaking the solder on the red and black wires connecting to the speaker, move the case aside
- Add a mono headphone jack to the setup via a black/red wire
- You can optionally detatch the speakers
- Your can piggy back off the existing wires
- (a) run the two new wires out of the case near the little button
- (b) or make a hole with a drill for wires to pass
- (c) with some ingenuity, you can mount the jack onto the case

That's it.  Try it out.

Troubleshooting:

- If you open the case and mess up: https://forum.m5stack.com/topic/117/easy-way-to-destroy-an-m5-stack

