# EXP6 : Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2024-11-16 at 17 28 59_a2f2449e](https://github.com/user-attachments/assets/60af8e91-8c76-4997-8771-0a71ce9c867a)

Area report:
![WhatsApp Image 2024-11-16 at 17 28 59_7cb05c54](https://github.com/user-attachments/assets/d892df04-cba4-4f98-a81c-0a0cba6f66ad)

Power Report:
![WhatsApp Image 2024-11-16 at 17 28 59_80d2fbc3](https://github.com/user-attachments/assets/12010aa3-c648-4178-9c09-aa575f41c48e)

Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
