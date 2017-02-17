
## Who are you, and what are you peddling...?
We are big believers in, and beneficiaries of: hacker culture, the maker movement, and open source everything.  This is our attempt at giving back by
*  Raising the bar for programmable LED matrix boards.
*  Raising money for [our local non profit hacker/maker space](https://thelab.ms).

What began as a cheeky wearable breathalyzer t-shirt for DEFCON three years ago (it's a good story, completely wholesome) has become a revolutionary RGB LED platform that is functional as a standalone unit or can be integrated into your other projects / products.

{image-1}

After more than 2 years of incremental design and development from an army of wonderful and talented people in the Dallas area, we think we have hit a home run with The TAP.  Big LED, prepare for disruption.  ;)

## Design Goals for The TAP Project
We established some pretty lofty goals for this final design and concept:

*  **Easy to use.**  You shouldn't need to be a programmer to do a LOT with the tap.
*  **Hackable.**  A programmer of any skill level should be able to do a LOT MORE with the tap.
*  **Scalable.**  It needs a modular design, enabling many TAPs to be connected to form larger display sizes with ease.
*  **Low power.** The board has to be able to be powered by a pair of watch batteries for hours.
*  **Bright.**  The board needs to be bright enough to be visible outside on a sunny day.
*  **Quality LEDs.**  The board needs to be bright enough to be visible outside on a sunny day.
*  **Stand alone.** No requirement for an external device like Arduino or Raspberry PI.
*  **Hackable.** Enable and encourage connectivity to external device like Arduino or Raspberry PI.
*  **Open.**  Project hardware design, firmware, and software must be Free and Open Source.*

{another-image-of-multiples}

## Who Needs It and Why?

(Maybe used in the script...) The most obvious use is LED light displays for for eye candy. Another use would be to learn C programming.

(TAP displays can range from a simple mood light that slowly scrolls through a wide range of colors, to scrolling text, or even a 255 x 255 array of TAPs all interconnected creating a massive display covering the side of a building! OK, we have not tried this yet, but in theory it is possible. You can also make a 1x6 array or a 3x3 array or ANY other size array for displaying the information that you want to share with the world.

Totally hackable.

If you have always wanted to learn C programming then TAP is a great way to jump in with both feet.

All aspects of the TAP are open source. This means you will have access to all source code we have created, all source code that came out of our hackathon contest, a free C compiler, the schematics (if you need them) and an online forum consisting of other TAP programmers where you can share ideas and discuss code.


The TAP can be used for many types of displays and for a couple different reasons.

We have now added a USB interface to enhance the ability to connect with to the device from the outside world.

This also allows for quicker program loading as well as powering the device.

One final enhancement is the ability to detect and react to ambient light sources via two photo transistors. This can also be used to program the device using a mobile app with simple flashing lights.


## Features & Specifications


**Each TAP board has:**

```

64 RGB LEDs (192 LEDs)

1 Texas Instruments MSP430 MicroController

2 Serial in \ 2 Serial Out

1 USB Interface (Power, Host Communication, & BSL)

2 Phototransistors (For Outdoor / Indoor Detection and Optical Programming)

4 Expansion Headers (Make TAP arrays!)

2 Push Button Switches (To enable Learn & BSL Modes)

Solder points for optional power source (coin cells)
```


## Manufacturing Plan

We have designed and built several versions of the TAP and each new version was manufactured by our partner factories located in China. All components are sourced in Asia for and ease of acquisition and the lowest possible cost we can get for the quality we demand. In addition to the factory performing a production test. Every aspect of the TAP is closely scrutinized and monitored for quality once received at TheLab.ms.

Our turn around time for 150 beta units ordered over the holidays was about 8 weeks.  We expect to be shipping units within 3-4 months of the campaign close.

Each unit will ship with basic firmware pre-loaded for a postive “out-of-the-box” user experience.

## Risks & Challenges

**Technical**

We don't see much in the way of technical risk.  This design is pretty refined.  We are ensuring the beta boards get in the hands of scores of people for testing and development prior to and during the CrowdSupply campaign.

**Governmental**

We have had prototype boards delayed for a few weeks by customs once.  There is also a slight risk of changes in trade policy that may lead to delays, tarriffs, or issues we cannot foresee or control.

## Frequently Asked Questions

**Q:** Can the tap be connected to Wifi or Bluetooth?

This is for the consumers benefit.  Use a $2 unit to provide connectivity for the entire ARRAY.  You're in control.  Tap That ASCII


**A:** It can be done relatively easily, but requires additional hardware not included.

---
**Q:** Why is there no wifi or bluetooth connectivity on the board?  WTF?! Isn't it 2017!?

**A:** Two reasons.

1. The first was our requirement for running the boards from coin cells.

2. The second (but arguably more important) reason... it's 2017.  We are small team of professional and hobbiest enigineering volunteers without the bandwidth to put into security hardening the device. We don't want to irresponsibly add to the rising sea of IOT botnet zombies.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


{image-of-something-great}

{a-parting-image}

