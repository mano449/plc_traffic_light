PLC-Based Traffic Light Automation System
A PLC Ladder Logic traffic light automation project created and tested in LogixPro PLC Simulator.
Features
Red–Yellow–Green sequential traffic signal operation
START/STOP control
TON timer-based sequencing
Latching/unlatching logic
Simulated PLC outputs for traffic lights
I/O Mapping
Address	Symbol	Function
I:1/0	STOP	Stop control
I:1/1	START	Start control
O:2/0	RED	Red light
O:2/2	YELLOW	Yellow light
O:2/1	GREEN	Green light
Timers
T4:0 — Red Timer
T4:1 — Yellow Timer
T4:2 — Green Timer
Software
LogixPro PLC Simulator
Project File
`Traffic_Light_Automation.lad`
