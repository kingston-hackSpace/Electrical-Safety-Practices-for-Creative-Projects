# Electrical Safety Practices for Creative Projects

A guide for creatives working with physical computing, electronics, and powered installations.

----
### ELECTRICAL BASICS

**Voltage** : 

Measured in ***volts(V)***. It is the electrical pressure that pushes current through a circuit.

**Current** : 

Measured in ***amperes(A) or milliamperes(mA)***. It is the flow of electrical charge. Higher current = more heat in wires and components.

**Resistance** : 

Measured in ohms (Ω). It is how much a material opposes the flow of current.

**Power** : 

Measured in ***watts(W)***. It is the rate at which electrical energy is used.

----

**Why this matters**

Understanding these three values helps prevent overloads, component failure, and fire risk.

----
### Correct Voltage (Example)

Do not connect a 5 V device directly to a 12 V supply — the excess voltage can damage or destroy it.

Conversely, a 12 V device will not work properly if powered from a 5 V supply — it simply won’t get enough voltage.


----
### Calculating Current Consumption

Before powering any project, you need to know how much energy your devices will draw. This ensures your components, wires, and power supply operate safely.

Instructions:

- List all devices in your project. Note their voltage (V) and current (A).

- All your components should be suitable for the **same Voltage** (explaied above), but may very in current draw.

- Sum the currents(A) for all devices sharing a power supply. Check if your power supply can provide this total current. If not, either choose a higher-rated power supply or split your project across two or more power supplies.

- If you don't know the current draw of some of your components, you can use a multimeter.

- Make sure the wire can safely carry the current. Too thin wires can overheat or melt. [Instructions here] (https://github.com/kingston-hackSpace/About_wires). 

- Check components. Ensure that the equipment you are using (connectors, switches, and terminals) are rated for the current you’ll draw.

- Always use a fuse rated slightly above your current draw.


----
### Safe Use of Extension Leads & Multi-Adaptors

- Most UK extension leads are rated 13 A at 230V. Never exceed the total current rating of the lead

- Avoid lead chains: they can cause overheats. 

- Damaged leads must not be used.
