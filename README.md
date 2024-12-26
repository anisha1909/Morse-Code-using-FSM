# Morse Code using FSM


Objective: 
The project aimed to design and simulate a Morse Code generator using Verilog, demonstrating the use of FSM to convert text input into Morse Code signals.

Project Description:  
The Morse Code generator is implemented as a digital design project using a Finite State Machine (FSM) in Verilog. The design accepts alphanumeric text input, processes it, and outputs the corresponding Morse Code as a sequence of timed dots (short signals) and dashes (long signals). The system includes distinct states for encoding, timing, and spacing to ensure accurate representation of Morse Code.

Key features of the design include:  
Input Handling: The text input is provided as ASCII characters, which are mapped to their respective Morse Code representations using a lookup table. 

FSM Implementation:The FSM consists of multiple states, including idle, encode, dot/dash generation, inter-character spacing, and inter-word spacing.

Timing Control:The design incorporates timing logic to maintain proper durations for dots, dashes, and spaces based on standard Morse Code timings.  

Simulation: The project was thoroughly tested using simulation tools like ModelSim or Vivado Simulator to verify functional correctness and timing accuracy. 

Output Representation: The Morse Code output is represented as a binary signal that toggles for dots and dashes, with appropriate gaps for inter-character and inter-word spacing.

Key Outcomes: 
 Demonstrated the ability to design and implement a digital system using FSM in Verilog.  
 Successfully simulated the project to verify its correctness and timing adherence to Morse Code standards.  
 Gained expertise in hardware description languages and digital logic simulation tools.

Tools Used: 
  Simulation software: ModelSim 

