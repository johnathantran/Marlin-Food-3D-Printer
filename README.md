# Food 3D Printer
Modified Arduino 3D printer firmware for creating customizable shapes through food paste extrusion. Our printer operates much the same way a regular 3D printer does, except that it does not use heated elements. It is also in reality closer to a "2.5D" printer, as it does not have a Z-axis, but rather builds in the Z-direction by layering food paste. Our team used mashed potatoes as the food paste, but this build should work with most foods with a paste-like consistency (such as frosting, pancake batter, creams, etc). 

The firmware used by our printer is Marlin: https://github.com/MarlinFirmware/Marlin

We also use Pronterface to run our g-code: https://www.pronterface.com/

The project uses an Arduino Mega to run the program. See full wiring diagram below:
![Wiring Diagram](https://github.com/johnathantran/Marlin-Food-3D-Printer/blob/master/wiring_diagram.png)

#*To get started:*
1. Build the physical structure of your 3D food printer.

2. Wire the Arduino and electronics according to the wiring diagram above.

3. Clone this repo and extract the files from the Marlin-1.1.x-Reconfigured.zip file.

4. Upload the Configuration.h file to your Arduino Mega.

5. Configure the Configuration.h file to your 3D printer's settings, using Pronterface to test your changes.

Please refer to the Assembly Instructions for a detailed guide on how to set up the physical build, wire the electronics, and program the Arduino.

# Project Description

Food 3D printing is an exciting new application of additive manufacturing that has the potential to improve many aspects of food production and consumption. In fact, 3D printing is predicted to be the next major disruptive technology for the food industry in the next decade (Karlgaard, 2011). However, there are many challenges that must be overcome before widespread adoption, including increasing the availability of printable food materials, achieving a cost reduction, and easing use for a layman consumer. Despite these challenges, the current development of food 3D printers looks promising as we see more and more competitive entries in the market.

We propose designing and building our own food 3D printer that is more affordable to the average citizen and buildable by a DIY enthusiast with access to basic tools. In this proposal we will provide an overview of the functionality of a 3D printer, discuss the advantages, limitations, and challenges facing current food 3D printers, present our findings from customer interviews, explain our engineering requirements, and present a problem statement summarizing the goals and constraints facing our design team.

# Final Food 3D Printer
![Final Food 3D Printer](https://github.com/johnathantran/Marlin-Food-3D-Printer/blob/master/final_printer.jpg)

# Belt and Pulley Gantry System

![Belt and Pulley Gantry System](https://github.com/johnathantran/Marlin-Food-3D-Printer/blob/master/belt_system.png)

# Syringe Extrusion Mechanism

![Syringe Extrusion System](https://github.com/johnathantran/Marlin-Food-3D-Printer/blob/master/extrusion_mechanism.png)

