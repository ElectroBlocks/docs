# Blink

<iframe width="535" height="450" src="https://www.youtube.com/embed/ql9KSAkS9kc?rel=0"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## What you will learn

How to write and basic program to control leds and how to uplaod that code to the Arduino.

## Bill of Materials

![kit](../assets/blink/kit.jpg)

- 1 x [Arduino with cable](lessons/what-is-an-arduino/)
- 1 x [Breadboard](/addons#breadboard)
- 2 x [Leds](/addons#led)
- 2 x [Resistors](/addons#resistor) (100 - 400 ohms)
- 5 x wires

## Blocks

- [Loop](/blocks#loop)
- [Led](/blocks#led)
- [Wait](/blocks#wait)

## Wiring Diagram

![wiring diagram](../assets/blink/wiring-diagram.png)

## Steps First LED

1\. Have the front of the Arduino face towards 1 of the breadboard.

![step1](../assets/blink/wiring-first-led/step1.png)

2\. Connect a wire from - of the breadboard to a GND pin on the Arduino.

![step2](../assets/blink/wiring-first-led/step2.jpg)

3\. Connect a wire from (28, A) to the - of the breadboard.

![step3](../assets/blink/wiring-first-led/step3.jpg)

4\. Insert the led's short (-) wire into (28, E) and the led's long (+) wire into (29,E).

![step4](../assets/blink/wiring-first-led/step4.jpg)

5\. Connect a resistor from (29, D) to (31, D).

![step5](../assets/blink/wiring-first-led/step5.jpg)

6\. Connect a wire from (31, A) to pin 7 on the Arduino.

![step6](../assets/blink/wiring-first-led/step6.jpg)

7\. Connect the Arduino into the computer.

![step7](../assets/blink/wiring-first-led/step7.jpg)

## Steps Second LED

1\. Connect a wire from (40, A) to the - of the breadboard.

![step1](../assets/blink/wiring-second-led/step1.jpg)

2\. Insert the led's short (-) wire into (40, E) and the led's long (+) wire into (41,E).

![step2](../assets/blink/wiring-second-led/step2.jpg)

3\. Connect a resistor from wiring (41, D) to (43, D).

![step2](../assets/blink/wiring-second-led/step3.jpg)

4\. Connect a wire from (43, A) to pin 4 on the Arduino.

![step2](../assets/blink/wiring-second-led/step4.jpg)

## Review

- What is an led?
- What is the first block that gets executed in the loop block?
- What does the delay block do?
- What is a breadboard?
