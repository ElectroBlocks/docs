# Lesson 2 - Blink

## Objective

How to write and basic program to control leds and how to uplaod that code to the Arduino.

## Kit

![kit](assets/blink/kit.jpg)

## Bill of Materials

- 1 x Arduino with cable
- 1 x Breadboard
- 2 x leds
- 2 x resistors (100 - 200 ohms)
- 2 x led wires

## Project

<video controls>
  <source src="../assets/blink/final-project.mp4" type="video/mp4">
</video>

## Components

### Led

The led stands for light emitting diode. The important thing to note are the wires connected to it. The long wire is positive and the short wire is negative. When you pass electricity through it, it will emit light.

![Led](assets/blink/led.jpg)

### Resistor

The resistor is used to decrease the amount of electrons flowing through the wire. The strength of the resistor is marked by the colored bands. You can use the [calculator](https://www.allaboutcircuits.com/tools/resistor-color-code-calculator/) to learn more.

![Resistor](assets/blink/resistor.jpg)

### Bre adboard

The breadboard is used to create / prototype electronic projects without gluing the wires together with metal. It does this by allowing wires to share electricity that are plugged into it. See the picture below. The green lines represent how which pins share electricity. In the middle of the board pins connectted up and down share electricity. On the side of the board pins are connected side to side.

![Resistor](assets/blink/breadboard.jpg)

## Code

There are two main blocks of code you need to know about when programming the Arduino. The setup block and the loop block. The loop block will run over and over again. The setup block will only run once. The way it works the blocks at the top of the loop or setup block will execute first.

![example code](/assets/blink/code_view.png)

The example above the send message block would run first then the wait block.

### Loop Block

Notice the loop block has (runs x times) in it. That is how many times it will run on the virtual circuit. In the actual Arduino it runs forever.

## Steps

### Wiring the first led

I don't follow the circuit picture exactly. You can if you want. Just remember the principles of the breadboard.

1\. Connect the long end of the led into hole (25, E) and the short into (28, E).

![step 1](assets/blink/wiring-first-led/step1.jpg)

2\. Connect a jumper wire from (28, A) to the ground - line of the breadboard.

![step 2](assets/blink/wiring-first-led/step2.jpg)

3\. Connect a resistor from (25, D) to (25, B).

![step 3](assets/blink/wiring-first-led/step3.jpg)

4\. Connect a jumper wire from from ground of the breadboard to ground (gnd) of the Arduino.

![step 4](assets/blink/wiring-first-led/step4.jpg)

5\. Connect a jumper wire from (25, a) to pin 7 on the Arduino.

![step 5](assets/blink/wiring-first-led/step5.jpg)

### Setting up chrome

1\. Go to chrome://flags in your chrome browser

![chrome flags](assets/blink/setting-up-chrome/chrome-flags.png)

2\. In the search bar type in 'Experimental Web Platform features'

![search ](assets/blink/setting-up-chrome/search.png)

3\. Enable the feature and click the relaunch button at the bottom of your screen.

![relaunch chrome ](assets/blink/setting-up-chrome/relaunch.png)

### Uploading the code

1\. Go to [electroblocks.org](https://electroblocks.org)

2\. Drag and led block into the loop block. Set it use pin 7.

<video controls>
  <source src="../assets/blink/uploading-code/step2.mp4" type="video/mp4">
</video>

3\. Upload the code the Arduino.

<video controls>
  <source src="../assets/blink/uploading-code/step3.mp4" type="video/mp4">
</video>

### Coding Blink

Note code is execute from top to bottom meaning that the blocks at the top of the loop will run before the bottom ones run.

<video controls>
  <source src="../assets/blink/coding-blink.mp4" type="video/mp4">
</video>

<video controls>
  <source src="../assets/blink/led-blink.mp4" type="video/mp4">
</video>

### Wiring the second led

1\. Connect the long end of the led into hole (17, E) and the short into (20, E).

![step 1](assets/blink/wiring-second-led/step1.jpg)

2\. Connect a jumper wire from (20, A) to the ground - line of the breadboard.

![step 2](assets/blink/wiring-second-led/step2.jpg)

3\. Connect a resistor from (17, D) to (17, B).

![step 3](assets/blink/wiring-second-led/step3.jpg)

4\. Connect a jumper wire from (20, a) to pin 5 on the Arduino.

![step 4](assets/blink/wiring-first-led/step4.jpg)

## Challenge make both leds blink at the same time.

<video controls>
  <source src="../assets/blink/double-blink.mp4" type="video/mp4">
</video>

## Challenge make leds in an alternate pattern

<video controls>
  <source src="../assets/blink/final-project.mp4" type="video/mp4">
</video>

## Review

- What is an led?
- What is the first block that gets executed?
- What does the delay block do?
- Why build
