# RGB LED

## Objective

To learn how to control an RGB LED with an Arduino and a computer.

## Kit

![kit](../assets/rgbled/kit.jpg)

## Bill of Materials

- Arduino Uno x 1
- RGB LED x 1
- Jump Wires x 5
- breadboard x 1
- resistors (300 to 1000 ohms) x 3

## What is RGB

RGB stands for red, green and blue. The way it works is that you mix red, green, and blue together to create a color. Click on the input to see an example.

<input type="color">

## What is RGB LED

![rgb led](../assets/rgbled/rgbled.jpg)

An rgb led is an led that has 4 wires. One for red, green, and blue, and the other for ground. You send an electrical signal to each color wire to control the amount of each you want. The largest wire is ground.

## Get Part of the text block

![get part from text block](../assets/rgbled/get_parts_from_text_block.png)

This block will take text block and will return a part of it. In the example above the block would return blue. If you wanted it to return red you would change the position to 2.

## Text to number block

![Text to number block](../assets/rgbled/text_to_number_block.png)

This block will change text stored in the computer and convert it into a number. We need this because whenever an Arduino recieves a message it's text.

## Steps

1\. Insert the rgb led into the breadboard. The red wire goes into (42, E). The ground wire goes into (39, E). The green wire goes into (37, E). The blue wire goes into (35, E).

![Step 1](../assets/rgbled/step1.jpg)

2\. Connect a jumper wire into - of the breadboard to gnd pin of the Arduino.

![Step 2](../assets/rgbled/step2.jpg)

3\. Connect a resistor into (42, D) and (42, B) of the breadboard.

![Step 3](../assets/rgbled/step3.jpg)

4\. Connect a jumper wire into (42, A) and the other end into pin 6 of the Arduino.

![Step 4](../assets/rgbled/step4.jpg)

5\. Connect a jumper wire into (39, A) and the other end into - of the breadboard.

![Step 5](../assets/rgbled/step5.jpg)

6\. Connect a resistor into (37, D) and (37, B) of the breadboard.

![Step 6](../assets/rgbled/step6.jpg)

7\. Connect a jumper wire into (37, A) and the other end into pin 5 of the Arduino.

![Step 7](../assets/rgbled/step7.jpg)

8\. Connect a resistor into (35, D) and (35, B) of the breadboard.

![Step 8](../assets/rgbled/step8.jpg)

9\. Connect a jumper wire into (35, A) and the other end into pin 3 of the Arduino.

![Step 9](../assets/rgbled/step9.jpg)

## Testing Wire

<video controls>
  <source src="https://storage.googleapis.com/electroblocks-lessons/rgbled/test-code.mp4" type="video/mp4">
</video>

## Coding

<video controls>
  <source src="https://storage.googleapis.com/electroblocks-lessons/rgbled/rgbled-coding.mp4" type="video/mp4">
</video>
