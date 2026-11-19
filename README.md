# EXP-5-CHARACTERISTICS-OF-SCR
1. AIM
To study and plot the V-I characteristics of a Silicon Controlled Rectifier (SCR), and to determine its forward breakover voltage and holding current.
2. APPARATUS REQUIRED
S. No.	Component	Specification	Quantity
1	SCR	2P4M	1
2	Resistor	1 kΩ	2
3	Regulated Power Supply	Dual (0–30 V)	1
4	Voltmeter	0–30 V	2
5	Ammeter	0–30 mA	2
6	Breadboard	—	1
7	Connecting wires	—	As required


5. PROCEDURE
1. Make the connections as shown in the circuit diagram.
2. Set R1 and R2 to the mid-position and set the regulated supplies V1 and V2 to minimum.
3. Set the gate current IG to approximately 0.7 mA. Check that the forward breakover voltage is within the available supply range.
4. Slowly vary the anode supply VAK in suitable steps and note VAK and IAK at each step until the SCR conducts. Note the maximum VAK just before the SCR conducts; this is the forward breakover voltage.
5. Finding latching current: Ensure that the SCR is in the conducting state. Start reducing the anode voltage in steps while simultaneously switching OFF the gate supply. The corresponding anode current at the point at which the SCR ceases to remain latched is the latching current IL.
6. Finding holding current: Ensure that the SCR is conducting and switch OFF the gate supply permanently. Slowly reduce VAK and note IAK at each step. The anode current just before it drops to zero is the holding current IH.
7. Reverse the anode supply polarity and vary the reverse voltage in steps. Note the corresponding reverse current values.
8. Plot the forward and reverse characteristics using the tabulated values and determine the SCR forward resistance from the graph.
9. Repeat the procedure for another suitable gate current (for example, IG = 1.2 mA) and verify the characteristics.

6. CIRCUIT DIAGRAM
<img width="1777" height="331" alt="image" src="https://github.com/user-attachments/assets/02339f17-0f42-452f-9e4a-f474439ab217" />

7.GRAPH
<img width="1795" height="412" alt="image" src="https://github.com/user-attachments/assets/f3de7963-82a2-472a-a424-5da32f98b42e" />
			
8. RESULT:
Thus the phase control characterstics of SCR using LT Spice is simulated and verified
The V-I characteristics of the SCR have been studied and plotted.
Forward breakover voltage, VBO = 11.5 V.
Holding voltage, VH = 0.72 V.
Holding current, IH = 12.4 mA.

