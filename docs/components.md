# Component Glossary

## Arduino


The Arduino is a small computer that runs your program and controls all connected components.

![Arduino](./assets/components/arduino.png)


### Pins

Pins are pieces of metal are connected to an electrical component.

![Arduino](./assets/components/arduino-pins.png)


### Types of Pins (Important)

Input pins listen for information from sensors or buttons

Output pins send instructions to lights, motors, or displays

Power pins supply electricity and do not send information

- Digital Pins (0–13):
   - Can be input (buttons, sensors) or output (LEDs, buzzers)
- Analog Pins (A0–A5):
  - Used as input to read changing values like light or temperature
- 5V / 3.3V: Power
- GND: Ground (return path for electricity)

## Breadboard

A breadboard lets you build circuits without soldering.

![Arduino](./assets/components/breadboard.png)

### Holes

Holes are connected internally in rows and columns

Side rails are commonly used for power and ground

## Jumper Wires

Used to connect components together.

![jumperwire](./assets/components/jumperwire.png)

### Types

- Male to Male: Arduino to breadboard
- Male to Female: Arduino to sensor
- Female to Female: Sensor to sensor

## Bluetooth Module

Allows wireless communication with a phone or computer.

![bluetooth](./assets/components/bluetooth_front.png)


### Pins

![bluetooth](./assets/components/bluetooth_back.png)

- TX (Output): Sends data from the module
- RX (Input): Receives data from Arduino
- VCC: Power
- GND: Ground

## Digital Display (TM1637)

Shows numbers such as timers or counters.

![digitaldisplay front](./assets/components/digitaldisplay_front.png)

### Pins

![digitaldisplay back](./assets/components/digitaldisplay_back.png)

- CLK (Input): Clock signal from Arduino
- DIO (Input): Data from Arduino
- VCC: Power
- GND: Ground

## RGB LED Light Strip (FastLED)

A strip of LEDs where each light can show a different color.

![rgb light strip](./assets/components/rainbow.jpg)


### Pins

![rgb light strip](./assets/components/rgb_light_strip_pins.png)


- DATA (Input) (Green): Color instructions from Arduino
- 5V (Red): Power
- GND (White or Black): Ground

## LCD Screen (I2C)

Displays text using only two data wires.

![lcd pins](./assets/components/lcd_front.gif)

### Pins

![lcd pins](./assets/components/lcd_back.jpg)

- SDA (Input): Data from Arduino
- SCL (Input): Clock from Arduino
- VCC: Power
- GND: Ground

## LED

A single light.  (Light Emitting Diode).  It only allows electricity to flow in one direction.

![led](./assets/components/led.jpg)

### Pins

- The long pin or wire connected to the LED.  Used to turn the led on.
- GND (Ground) The short wire connected to the pin.

## LED Matrix (MAX7219)

A grid of LEDs used to draw.

![led matrix](./assets/components/ledmatrix_front.png)

### Pins

- DIN (Input): Data from Arduino
- CLK (Input): Clock
- CS (Input): Chip select
- VCC: Power
- GND: Ground

## Motor (L298 Driver)

Controls DC motors safely.

![l298](./assets/components/motor.png)

### Pins

![l298](./assets/components/l298N.png)

- IN1 / IN2 (Input): Direction control
- ENA (Input): Speed control
- Motor Outputs: Connect to motor
- Power / GND: Motor power

## Passive Buzzer

Makes sound when controlled by Arduino.

![l298](./assets/components/passive_buzzer_pin.png)

### Pins

- Signal (Input): Sound control (Find the + icon circled in red)
- GND: Ground

## RGB LED

A single LED that can display many colors.

![rgb led](./assets/components/rgb_led.jpg)

### Pins

- R (Input): Red control
- G (Input): Green control
- B (Input): Blue control
- Common: Power or Ground

## Servo Motor

Moves to a specific angle.

![servo](./assets/components/servo.png)

### Pins

![servo](./assets/components/servo_wire.png)

- Signal (Input): Angle control (Orange or Yellow)
- Power: (Red)
- GND: (Brown)

## Stepper Motor

Moves in precise steps.

![stepper motor](./assets/components/stepper.png)


### Pins

- Multiple input pins connect to a driver
- Driver connects to Arduino output pins
- Separate power for the motor

## Analog Sensor (General)

Returns a range of values, not just on or off.

![stepper motor](./assets/components/analog_gas_sensor.png)

### Pins

- Signal (Output): Sends value to Arduino
- VCC: Power
- GND: Ground

## Photo Resistor (Light Sensor)

Detects how bright the environment is.

### Pins

- Two legs used with a resistor
- Output goes to an analog input

## Potentiometer

### Pins

- Middle (Output): Value to Arduino
- Side Pins: Power and Ground

## Push Button

Detects when it is pressed.

### Pins

- One pin goes to ground
- The other goes to a pin on the arduino.

## Touch Sensor

Detects when touched.

### Pins

- Signal (Output): Touch detected
- VCC: Power
- GND: Ground

## IR Motion Sensor

Detects movement.

### Pins

- OUT (Output): Motion detected
- VCC: Power
- GND: Ground

## IR Remote Receiver

### Pins

- Signal (Output): Button data
- VCC: Power
- GND: Ground

## Joystick

Used for directional control.

### Pins

- AX (Output): Left / Right
- AY (Output): Up / Down
- SW (Output): Button press
- VCC: Power
- GND: Ground

## Ultrasonic Sensor

Measures distance using sound.

### Pins

- Trig (Input): Arduino sends sound
- Echo (Output): Distance signal
- VCC: Power
- GND: Ground

## RFID (RDM630)

Reads RFID cards or key fobs.

### Pins

- TX (Output): Tag number
- VCC: Power
- GND: Ground

## Temperature Sensor (DHT)

Measures temperature and humidity.

### Pins

- Data (Output): Sensor readings
- VCC: Power
- GND: Ground

## Thermistor (Standard)

Measures temperature using resistance.

### Pins

- Two legs used in a voltage divider
- Output read by an analog input