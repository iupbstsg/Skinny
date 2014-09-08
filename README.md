<!-- Ben's lovely logo -->
<img src="https://github.iu.edu/PBS-TSG/Motz-TheSkinny/raw/master/Resources/skinnyLogo.png" style="width: 100%;"/>

# Quick Start

Here is how to run an experiment with the Skinny. Assumes the Skinny is charged and the SD card is [inserted].

1. attach probes to Skinny (either direction works)
  ![](https://github.iu.edu/PBS-TSG/Skinny/raw/gh-pages/images/jacks.png)
2. attach probes to person (use Signa Creme)
  ![](https://github.iu.edu/PBS-TSG/Skinny/raw/gh-pages/images/using1.png)
3. scroll (by turning the knob) to `Record Continuous` or `Record Epoch`, then press the button to choose
4. During recording, the display should indicate a file number such as `1C.CSV` if you're in Continuous mode, or
an epoch number if in Epoch mode. Do something awesome.
  ![](https://github.iu.edu/PBS-TSG/Skinny/raw/gh-pages/images/using2.png)
5. when done, a long press (2 seconds) on the button will exit the recording mode and return you to the menu

---

# User Manual

## Care and Feeding

The Skinny has a battery indicator in the upper-left corner of the display. It is green when fully charged. When it drops to 50% it turns yellow, and below 30% it turns red. When red, recording to the SD card might not work and you might have a bad time.

## Plugging Things

One side of the Skinny has the micro USB and micro SD card ports:

![](https://github.iu.edu/PBS-TSG/Skinny/raw/gh-pages/images/ports.png)

The micro SD card only goes in one way. The gold pads should face up. A tiny spring/latch mechanism holds the card in place. To insert the card, press it in until you hear/feel a slight click. To remove, press again (another slight click) to release the latch, then the card should be free to remove. Don't try to force the card in or out or you will probably have a bad time.

The micro USB charging cable only goes in one way. If you're like me, you will get the orientation wrong at least twice before finally plugging it in correctly. If you get it right every time, try not to brag. Lastly, the micro USB connector is small (like the name implies) and delicate. Charging should therefore take place away from small children or kittens.

## Conserve Battery

To conserve battery life, put the Skinny into "sleep mode". This will turn off the display and tell the [microcontrollers](https://en.wikipedia.org/wiki/Microcontroller) inside to stop using so much power. To wake up the Skinny again, press the button. It takes about 2 seconds for it to resume normal operation after waking.

## Troubleshooting

The main thing to note is that the SD card is only recognized **at wakeup time**. So if you remove the SD card (for example, to copy data to your computer) then the Skinny will forget what it was doing and be unable to find the SD card, *even after you put it back in*, until you first put it to sleep and wake it up again.

If you have other issues don't hesitate to contact [Alex Shroyer](mailto:ashroyer@gmail.com) or visit the Psychological and Brain Sciences Technical Support Group (PBS-TSG), located in PSY 008.

---

# More Information

## Laboratory / Principal Investigator / Faculty
[Ben Motz](http://psych.indiana.edu/faculty/bmotz.php)

## Engineers

* [Alex Shroyer](https://hoosieree.github.io)
* Jeff Sturgeon
* Tony Walker

## Features

* AgCl electrodes (2)
* 1.8" color TFT screen
* micro SD card for data collection
* rechargeable battery (charge through micro USB)

## Revision History

* 1.0.0 - 2013/08/09 - Initial project complete
* 1.0.1 - 2014/06/27 - Begin version 2.0
* 0.2.1 - 2014/06/28 - Prototype hardware assembled
* 0.2.1 - 2014/07/07 - Porting to Teensy 3.1
* 2.0.0 - 2014/09/05 - 2.0 device delivered to students
