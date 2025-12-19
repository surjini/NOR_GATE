# NOR_GATE
## REG NUM : 25015534
## NAME : R.Surjini
## EXPERIMENT 2.b Design CMOS NOR gate and perform Transient and Operating Point (OP) analysis.

## Aim:To design CMOS NOR gate and performTransient and Operating Point (OP) analysis.

## Tools Used: 
Virtuoso Schematic Editor is used for the design and analysis. 

## Theory: 
A 2-input CMOS NOR gate uses PMOS transistors in series and NMOS transistors in parallel.
	When either input is high, at least one NMOS conducts → output LOW.
	When both inputs are low, both PMOS conduct → output HIGH.
Thus, output Y=(A+B) ‾.
## Procedure:
	Create new library attached to gpdk045.
	Create cell view CMOS_NOR.
	Place components:
	2 × PMOS (series connection)
	2 × NMOS (parallel connection)
	Inputs (VinA, VinB), ground, VDD, and output node.
	Connect as per NOR schematic.

## For schematic:
A.TRANSISTOR DIAGRAM :

<img width="331" height="423" alt="image" src="https://github.com/user-attachments/assets/267821e6-0c5e-4916-8936-0ba14f29f2c6" />

FIG - TRANSISTOR DIAGRAM 

B. IN CADENCE 
  Pick the components NMOS, PMOS, ground, VDD and voltage source. 
	Connect the wire as per the schematic diagram. 

<img width="979" height="540" alt="image" src="https://github.com/user-attachments/assets/889a74f7-1cb4-4add-a8f8-1201e7ef5beb" />

FIG - NOR SCHEMATIC DIAGRAM 

C.SYMBOL DIAGRAM 

<img width="979" height="632" alt="image" src="https://github.com/user-attachments/assets/0eacbb66-40a7-4645-b999-0c32e0428d2f" />

FIG - NOR SYMBOL DIAGRAM 

## Transient Analysis and OP: 
a)	In the Analysis section, select transient. 
b)	In the stop time type 600n and click OK. 
c)	In the transient Analysis section, turn on Save transient Operating Point.  
d)	Check the enable button and then click Apply. 
                Click OK in the Choosing Analyses Form. 
                Click OK in the Choosing Analyses Form. 
## Execute Outputs: 
To be plotted – Select on Schematic in the simulation window.  
Follow the prompt at the bottom of the schematic window, Click on output net Vout, input net Vin of the Inverter.  
Execute Simulation: 
Net list and Run in the simulation window to start the Simulation.  
When simulation finishes, the transient automatically will be popped up along file. 


## Waveforms: 
![WhatsApp Image 2025-12-19 at 8 55 34 AM](https://github.com/user-attachments/assets/8affcc8d-b79b-410b-b6dc-d324fb97bd77)


## RESULT:
Design and Transient analysis of CMOS NOR gate successfully verified.

