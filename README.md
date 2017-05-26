# Mechatronics-Summer-2017
5/26 Homework
Repository for Summer 2017 CCA Course
Connecting the wires between the breadboard and the Arduino was straightforward.
Ensuring that the spacing and sequence of the wires seems to be very important as one adds a greater number of input and output devices.  Sequencing the wires, resistors, input and output devices with enough room and a logical progression so that connections can be tracked visually is important and something to keep in mind as I embark on future experiments.
The code in the Arduino Software is not needed to communicate with this system.  The photo sensor and LED are in a closed loop and the LED reacts to amount of light I provide.
I copied the code from the Arduino tutorial (https://www.arduino.cc/en/Tutorial/AnalogInput) - In running the code, the LED goes from dull to bright, given the input from the light sensor.  I had not connected the light sensor to pin A0 - in doing so, I allowed the light sensor to control the brightness of the LED.
