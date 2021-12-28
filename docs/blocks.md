# Blocks

## Arduino Message Setup



This block will give the Arduino the ablity to send and recieve messages.  The stuff under the ----------- is for the virtual circuit.  It's used to tell the virtual circuit that a message is being recieved and what that message is in the loop number that the Arduino is currently executing.

![message setup block](assets/blocks/message-setup.png)


## Arduino Get Message



This block get the message being sent from the computer to the Arduino.

![Arduino Get Message](assets/blocks/arduino-get-message.png)

## Button Setup



This block will tells the Arduino which pin to connect the button to.  The stuff under the ----------- is for the virtual circuit.  It's used to tell the virtual circuit whether the button 
is pressed or not in the loop that the circuit is running.

![button setup block](assets/blocks/button_setup_block.png)

## Color Exact 


The block returns a custom color based on the red, green, and blue numbers you put into the block.

![color exact block](assets/blocks/color-exact.png)

## Color Picker


Returns a custom color based on the color pick in the color picker.

![color picker block](assets/blocks/color-picker.png)

## Compare

The block will compare the blocks on the right and left.  It will use the option in the middle to make the evaulation.  This block will equal true or false.  If the option is set to "=" it will return true if what is on the right and left side is true.  It it's set to "≠" then what is true if what is on the right and left side are not equal.

![compare blocks](assets/blocks/compare-blocks.png)
![compare output](assets/blocks/compare-output.png)

## Get Variable 


A variable is one way you can tell the computer to store something.  The get variable block will get the value that is being stored inside the variable.  

![get variable](assets/blocks/get_variable.png)

## If 

The block is used to make decisions.  If what is connectted to the if block is true then what is inside the do block will be ran.

![if block](assets/blocks/if_block.png)

## Is Button Pressed

This block will return if the button is pressed.

![if block](assets/blocks/is_button_pressed.png)

## Loop

Blocks inside the block will run forever on the actual Arduino.  It will be from top to bottom, and once it reaches the bottom block, it will go back to the top block.  The simulator on the right of the screen will run three times. 

![loop block](assets/blocks/loop.png)

## Loop With


This block is used to repeat something over and over again.  It creates a variable often called "i".  It will start i at the from number and will add or subtract the value stored in i until it gets to the to number.  The best way to understand loops in Electroblocks is to play around with them.

![loop with adding](assets/blocks/loopwith1.png)

![loop block subtracting](assets/blocks/loopwith2.png)


## Led


The LED block controls whether an led is on or off.  The first drop-down decides which [Arduino Pin](/lessons/what-is-an-arduino.html#what-are-pins) the led is connected to.  The second dropdown turns the LED on or off.

![loop block](assets/blocks/led.png)

## RGB Set Color


Sets the color of the RGB LED.

![rgb led set color block](assets/blocks/rgbled-set-color.png)

## RGB LED Setup 

Sets the wires used in the RGB LED.

![rgb led setup block](assets/blocks/rgbled-setup.png)

## Servo

The servo controls the data pin that the servo is connectted to and number of degress that you want to rotate the servo.  The higher the number the more the servo will rotate.

![servo block](assets/blocks/servo.png)


## Wait

The wait block will pause the Arduino.

![loop block](assets/blocks/wait.png)


