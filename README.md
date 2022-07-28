# Overview

This project is a modification of the original Repeater example found here: 
https://github.com/m5stack/M5-ProductExampleCodes/blob/master/Core/Atom/AtomEcho/Arduino/Repeater/Repeater.ino

The project goal is to make a small handheld looper that can work with
modular eurorack gear.

 ![Alt text](https://static-cdn.m5stack.com/resource/docs/products/atom/atomecho/atomecho_01.webp "Pinouts")
## Hardware Requirements

- M5 Stacks Atom Echo
- (Optional) Mono Jack Mod (see below)

## Building

- Use the instructions here to set up your M5 Stacks Echo: https://ftdichip.com/drivers/vcp-drivers/
 and the m5-atom platform is needed to be installed: https://docs.m5stack.com/en/quick_start/atom/arduino
- Build using standard Arduino software

## Mono Jack Mod

** WARNING ** This can brick or ruin your ATOM Echo.

- Purchase a Thonkiconn style mono jack, see: https://store.synthrotek.com/thonkiconn_mono_jack or https://www.thonk.co.uk/shop/thonkiconn/ . Note, the diagram for the wiring is simple, but you just need to remember the long leg that sticks off the outside of the jack is the negative polarity.
- The sticker on the side of the side can be removed which is the FCC sticker.
- Once the sticker is off, you can actually easily press a thumb against the area near the sticker, the case will pop off
- With the case off, you should carefully fold it open
- Without breaking the solder on the red and black wires connecting to the speaker, move the case aside
- Add a mono headphone jack to the setup via a black/red wire
- You can optionally detatch the speakers
- Your can piggy back off the existing wires (red and black) to the speaker
- (a) run the two new wires out of the case near the little button
- (b) or make a hole with a drill for wires to pass
- (c) with some ingenuity, you can mount the jack onto the case

That's it.  Try it out.  My design

 ![Alt text](https://user-images.githubusercontent.com/64202/181645510-2b695feb-5f71-4363-99c0-938c2ece8874.png "Soldering The Mono Jack")

 ![Alt text](https://user-images.githubusercontent.com/64202/181645495-c330c4d5-bf88-4c48-992f-f38241647b80.png "Soldering onto the board where the speaker connects")

  ![Alt text](https://user-images.githubusercontent.com/64202/181645495-c330c4d5-bf88-4c48-992f-f38241647b80.png "Closing Up The Case")
  
Troubleshooting:

- If you open the case and mess up: https://forum.m5stack.com/topic/117/easy-way-to-destroy-an-m5-stack
- The speaker might fall out.  It has some tape on it that is adhesive double stick, but just beware that it might fall off
- If you solder, you risk causing the speaker wires to disconnect.  Be prepared to rework.
- The button started acting strangely after adding additional wires into the case because the spacing was messed up between the plastic case button and the button on the board.  I put a piece of cardboard inside to help smash the button properly.  Maybe not a good idea, but be aware the button behavior may change if you change the spacing inside the case.

## Known Issues

- You will experience an audio pop with every microphone activation.  Not clear if this is from an internal click via the button to the mic, or some noise picked up when the mic is activated.  
- A better jack with a hole to loop the wire onto is probably more suitable, feel free to substitute the jack used.