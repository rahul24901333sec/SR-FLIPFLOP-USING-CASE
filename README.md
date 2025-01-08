### NAME:RAHUL.R
### REG NO: 24901333

# AIM:

To implement  SR flipflop using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED:

Quartus prime

# THEORY

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/0f710028-ad52-4d3e-9276-8714cf023a25)

 
This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dabfc4f4-87e3-4cbc-9472-f89ee1b5ed30)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dd90d16c-aec5-4290-a586-e2346b1e9eb5)

 
By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/473efad6-d70b-4ca7-aeb7-898bbfca319f)

 
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

# Procedure

1.Launch Quartus on your computer and create a new project: Go to File → New Project Wizard.
Specify the project name, directory, and top-level entity name (e.g., JK_FlipFlop).
Create the JK Flip-Flop Circuit and implement the JK Flip-Flop by writing VHDL/Verilog code. Go to
File → New → Select Verilog File.
Compile the Project Click on Processing → Start Compilation.
Fix any syntax or schematic errors if present.
Simulate the Circuit: Go to Tools → University Program VWF.
Define the inputs for J, K, and CLK in the waveform editor.
Run the simulation and observe the waveforms.
Verify the Results. Compare the simulated results with the truth table for a JK Flip-Flop.

# PROGRAM
![bf982f0b-32d7-49d7-bd3b-cb37aecf4fc1](https://github.com/user-attachments/assets/2dd9ad16-f4be-4a07-92dc-8fb1ed2edee5)



# RTL LOGIC FOR FLIPFLOPS
![8cdd574e-c82f-4897-bd60-b34a7d162917](https://github.com/user-attachments/assets/11e3f0a5-114c-44a8-833e-1206b97e4108)

# TIMING DIGRAMS FOR FLIP FLOPS
![9a68ada4-f722-434e-9d8c-0073c2eb11d1](https://github.com/user-attachments/assets/c810317e-7678-4e7c-accd-11380e0bde9e)

# RESULTS
implemented JK flipflop using verilog and validating their functionality using their functional tables
