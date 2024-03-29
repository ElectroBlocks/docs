# RGB LED Light Strip

This lesson page will serve for as the reference for all lessons related the FAST Leds.  It contains how to wire them and what to do.

## What you will learn

- How to do cool led light patterns
- Advanced loops
- How to create random colors
- How to wire up and rgb led light strip

## Bill of Materials

![kit](../assets/fastleds/kit.jpeg)

- 1 x [Arduino with cable](../what-is-an-arduino/)
- 1 x [RGB LED Light Strip](../../addons#rgb-light-strip)
- 3 x wires

## Blocks

- [FastLED Setup](../../blocks#fastled-setup)
- [FastLED Change Color](../../blocks#fastled-set-color)
- [Loop with](../../blocks/#loop-with)
- [Get Variable](../../blocks/#get-variable)
- [Wait](../../blocks#wait)
- [Color Picker](../../blocks#color-picker)

## Wiring Diagram

![wiring diagram](../assets/fastleds/wiring-diagram.png)

## Coding Videos


### Intro

<video controls >
<source src="https://firebasestorage.googleapis.com/v0/b/inapp-tutorial.appspot.com/o/electroblocks-org%2F3coW8djkjz0fYOPCH4Ib%2Fstep_oREt6y5nMDMdzzJksZ7s.mp4?alt=media&token=56680f2b-2323-4596-9e89-80ca20931f08">
</video>


### Alternating Patterns

<video controls >
<source src="https://firebasestorage.googleapis.com/v0/b/inapp-tutorial.appspot.com/o/mgMqiXuPbEdHtr6UoPVbQozFQwD2%2F9eDJTXJfo6a7jfjMSspI%2Fstep_TNOk5AnANvB1769T0z2x.mp4?alt=media&token=777df31f-be1d-4436-ac6c-09fbeec772ea">
</video>

### Snake

<video controls >
<source src="https://firebasestorage.googleapis.com/v0/b/inapp-tutorial.appspot.com/o/mgMqiXuPbEdHtr6UoPVbQozFQwD2%2FQD76ElYnxSULlwfHkzGR%2Fstep_KllgmeONWJl9LG0WuhT5.mp4?alt=media&token=3d690256-0576-429d-a766-5c7a9b70dea5">
</video>

## Steps

1\. Look at RGB LED light strip.  Notice the arrows.  The direction that the arrows point is how the LEDS are numbered. 

![step 1](../assets/fastleds/step1.jpeg)

This is how it looks like if each LED were a number:

1 -> 2 -> 3 -> 4

Also notice the labels Din, GND, 5v+.

- Din -> Mean data in.  This wire controls the data in the rgb led. It will go to an analog pin.
- GND -> Ground
- 5v+ -> 5 volts

2\. Connect a wire from GND of the LED Light Strip to GND of the Arduino.  Consult you LED Light Strip for GND.

![step 2](../assets/fastleds/step2.jpeg)

3\. Connect a wire from 5v+ of the LED Light Strip to Vin of the Arduino.  Consult you LED Light Strip for 5v+.  Vin will supply the max power and will give better performance from my experience.

![step 3](../assets/fastleds/step3.jpeg)

4\. Connect a wire from Din of the LED Light Strip to A0 of the Arduino.

![step 4](../assets/fastleds/step4.jpeg)

