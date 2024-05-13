gtyghyh# PCB-Design-Application
# Aim


# Software required
Eagle

# Procedure
1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory
The circuit you sent me is a  simple sound reactive LED circuit.It uses the speaker  to pick up ambient sounds and convert them into electrical signals which are then amplified by the transistors, which in turn light up the LEDs.

The speaker works as a microphone in this circuit. Sound waves cause the speaker cone to vibrate. This vibration induces a small voltage across the speaker terminals.
The capacitors (C1 and C2) block the DC voltage from the power supply from entering the circuit, but allows the AC signals from the speaker to pass through.
The 1N4148 diodes act as clippers or voltage limiters. They clip off the negative voltage halves of the AC waveform from the speaker, leaving only the positive voltage portions. This process is called half-wave rectification.
The resistors (1kΩ) limit the current from the speaker to the transistors (Q1-Q5).
The transistors (Q1-Q5) amplify the rectified signal from the speaker. When sound is picked up by the speaker, the transistors are turned on, which allows current to flow through the LEDs, lighting them up. The louder the sound, the brighter the LEDs will glow.

### Working 
The circuit you sent me is a  simple sound reactive LED circuit. Here are the steps on how to build it:

Collect your parts. You will need:

LEDs (any color)
1N4148 diodes (4)
1k resistors (6)
470uF capacitors (2)
Speaker
9V battery
Breadboard
Jumper wires
Connect the positive lead of the battery to the positive rail of the breadboard. Connect the negative lead of the battery to the negative rail of the breadboard.

Connect one of the 470uF capacitors to the positive rail and the other to the negative rail.

Connect the positive leg of the speaker to the positive rail of the breadboard. Connect the negative leg of the speaker to one of the 1k resistors.

Connect the other leg of the 1k resistor to the negative leg of one of the 1N4148 diodes.

Connect the positive leg of the same 1N4148 diode to an LED. Connect the negative leg of the LED to the negative rail of the breadboard.

Repeat steps 4-6 four more times so that you have a total of four LEDs and four 1N4148 diodes connected in the same way.

Now you can adjust the sensitivity of the circuit by changing the value of the resistor connected between the speaker and the positive rail. A lower value resistor will make the circuit more sensitive.


# Circuit Diagram

![WhatsApp Image 2024-05-13 at 11 03 45_c3e34cb1](https://github.com/jyesvanthe/PCB-Design-Application/assets/150319392/ddc8134e-a9e1-4ec1-a7b4-fbdadff3b6bb)


# Output

### Schematic diagram

![WhatsApp Image 2024-05-13 at 10 55 44_f0ebbcbd](https://github.com/jyesvanthe/PCB-Design-Application/assets/150319392/f9353848-62cc-4c75-87f5-20c2a2a326a3)

### Layout diagram
![WhatsApp Image 2024-05-13 at 10 55 53_6bd095d5](https://github.com/jyesvanthe/PCB-Design-Application/assets/150319392/ff5bd3e4-4826-4a34-8f4f-78d521df2d85)

# Result


