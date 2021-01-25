# Messages

## Objective

To also learn about receiving messages from the Arduino.

This lesson requires that you build the circuit in the [blink lesson](blink.md).

## Kit

![kit](assets/blink/kit.jpg)

## Bill of Materials

- 1 x Arduino with cable
- 1 x Breadboard
- 2 x leds
- 2 x resistors (100 - 300 ohms)
- 2 x led wires

## Message Setup Block

![message setup](assets/messages/message_setup.png)

This is a library block that is require for the Arduino to send and recieve messages. Notice the stuff below the "---------------". This where you will tell the virtual Arduino what messages it suppose to recieve. The loop drop down is used to tell it what to receive during which loop cycle. This allows us to test a lot of situations without having an Arduino present.

## If Block

![if block](assets/messages/if_block.png)

If blocks are used to make decisions. If what is connected to the if part of the block is true then blocks in the do section will run.

## Comparison Block

![comparison block](assets/messages/comparison_block.png)

The comparison block is used to compare two values. If it's set to "=" it will check return true if both blocks connectted to it have the same value.

## Coding it up
