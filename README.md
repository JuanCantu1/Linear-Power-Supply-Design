# Linear-Power-Supply-Design

# Introduction
The project was done at he University of Texas Rio Grande Valley as part of EECE 3225, Electrical Engineering Lab 1, by Juan Cantu and Kaysi Gutierrez. 

# Abstract
In this lab, we were to design a simple, unregulated AC-to-DC power supply. This involved designing a regulator circuit to form a regulated power supply. The parts of a regulated
power supply are a transformer, rectifier, filter, and regulator. The output voltage of the circuit is
dependent on the input AC voltage and the load current, as this can lead to fluctuations in the
output voltage. This is the issue that the regulator circuit addresses. It is added to maintain a
constant output voltage regardless of changes in the input voltage and load current. In this lab,
we designed an unregulated power supply and analyzed the effects of the regulator circuit.
Different load resistors were used to simulate a load and their impacts on the regulator circuit
and output voltage were analyzed. The load was measured using a multimeter to evaluate the DC
voltage output. An oscilloscope was used to monitor the AC Coupling through the peak-to-peak
ripple.

# Edquipment List
- Function Generator
- Oscilloscope
- Multimeter
- Power Transformer
- 4 Power Diodes
- Electrolytic Capacitors
- Resistors for Regulator Circuit
- Power Resistors for Load

An AC power supply is needed. A wall outlet was used, which typically supplies 250V AC.

# Part 1: Calculations
We used a full-wave bridge. The following calculations were made using data from Lab 5 and
the equations that apply to the full-wave bridge.

![1](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/c4b83b9f-45b5-4d2b-8e0c-a184cb679be9)

![2](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/26152b5d-0059-4f9e-8359-ffdacf6a4166)

![3](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/ecf05a67-1f69-4e6e-bb7b-865802b51be6)

# In the Lab

Schematic:

![4](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/a9a7b8ef-2d5d-4144-b79f-8c43e0291799)

Our group was instructed to build a circuit that outputted 9V at 0.8A. This meant that Vreg,out
needed to be 9V. We checked the rectifier diodes on the multimeter, as well as the capacitor on
the ohmmeter, to verify their values.

We then measured the DC voltage and peak-to-peak ripple before and after the regulator under
no load, 33% load, and 100% load.

![5](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/63d7b3e3-5ccb-4ca9-8576-aad4701ed3a8)

We used resistors summing to 33.65 ohms measured for the 33% load. We used resistors
measuring 11.53 ohms for the 100% load

![6](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/d7f9032a-0086-43dc-807f-350c8b9c089a)

![7](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/f2ee48fe-f5ee-4b1d-a589-5ec8733dba01)

![8](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/81896b73-ffaa-4a8d-872b-4837e558b143)

![9](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/d6a28a87-5652-4359-9227-5f0f567e68db)

![10](https://github.com/JuanCantu1/Linear-Power-Supply-Design/assets/109363196/81b460d0-cbdd-49a4-bad6-cf900e6cca02)

# Conclsuion
The data recorded from measuring an unregulated power supply and its response to a
regulator reveals several important observations. As the load on the power supply increases, the
resistance decreases, leading to an increase in voltage due to the inverse relationship between
resistance and voltage. The load regulation before the regulator is 18.43%, which improves
significantly to 1.56% after the regulator is applied. Additionally, the peak-to-peak voltage ripple
is substantially reduced to values under 1V after the regulator is introduced, as compared to the
values recorded before the regulator. Furthermore, when a variac is used to test the effect of input
voltage changes on the output, the regulator shows line regulation of 1.40%, which is
significantly better than the 18.94% line regulation observed before the regulator was installed.
These results suggest that the regulator effectively suppresses ripple voltage, and it is capable of
regulating the power supply's output regardless of the input voltage or the size of the load.
