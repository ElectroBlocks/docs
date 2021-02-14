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

## Project

<iframe width="535" height="450" src="https://www.youtube.com/embed/VbCbxICXW34?rel=0"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Video

<iframe width="535" height="450" src="https://www.youtube.com/embed/ik1sujnNxWA?rel=0"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## What is RGB?

RGB stands for red, green and blue. The way it works is that you mix red, green, and blue together to create a color. Click on the input to see an example.

<input type="color">

## What is an RGB LED?

![rgb led](../assets/rgbled/rgbled.jpg)

An RGB led is an led that allows you to set its color. You send an electrical signal to each color wire to control the amount of color of each you want. The largest wire is ground.

## Get Part of the text block

![get part from text block](../assets/rgbled/get_parts_from_text_block.png)

This block will take a text block and will return a part of it. In the example above, the block would return blue. If you wanted it to return red, you would change the position to 2.

## Text to number block

![Text to number block](../assets/rgbled/text_to_number_block.png)

This block will change text stored in the computer and convert it into a number. We need this because whenever an Arduino receives a message, it's text.

## Steps

1\. Insert the rgb led into the breadboard. The red wire goes into (9, E). The ground wire goes into (10, E). The green wire goes into (13, E). The blue wire goes into (15, E).

![Step 1](../assets/rgbled/step1.jpg)

2\. Connect a wire from (10, A) to the - of the breadboard.

![Step 2](../assets/rgbled/step2.jpg)

3\. Connect a wire from (15, A) to pin 9 on the Arduino.

![Step 3](../assets/rgbled/step3.jpg)

4\. Connect a wire from (13, A) to pin 10 on the Arduino.

![Step 4](../assets/rgbled/step4.jpg)

5\. Connect a wire from (9, A) to pin 11 on the Arduino.

![Step 5](../assets/rgbled/step5.jpg)

6\. Insert a resistors into (9, B) to (9, D), (13, B) to (13, D), and (15, B) to (15, D) in the breadboard.

![Step 6](../assets/rgbled/step6.jpg)

7\. Connect a wire from - of the breadboard to a GND pin on the Arduino.

![Step 7](../assets/rgbled/step7.jpg)

## Test Coding

<iframe width="535" height="450" src="https://www.youtube.com/embed/tVX-WBp7808?rel=0"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Coding

<iframe width="535" height="450" src="https://www.youtube.com/embed/6Q5QhjK-eGY?rel=0"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
