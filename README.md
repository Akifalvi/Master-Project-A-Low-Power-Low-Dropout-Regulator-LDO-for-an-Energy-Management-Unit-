# Master-Project-A-Low-Power-Low-Dropout-Regulator-LDO-for-an-Energy-Management-Unit-
The storage energy is an important parameter for autonomously operating electronic implants. Ideally, sufficient energy has to be provided to power the implant between two recharging cycles. Supercapacitors are used as energy sources in wireless medical implants as they can store energy for a longer time, are available in smaller sizes, and can be recharged in shorter times. An energy management unit consisting of 4 supercapacitors for an electronic osteosynthesis implant is developed at the Institute for Integrated Circuits (IIC) at the Hamburg University of Technology. The supercapacitors have a capacitance of 11mF and 3.3V maximum voltage. Initially, the supercapacitors are in parallel connection and can not be discharged below 1.8V which results in the remaining stored energy on the capacitors being lost for the application. Switching the connection from parallel to series between the supercapacitors results in reducing the minimum discharge voltage and increasing the available energy. The energy management unit consists of an inductive energy transmission, a PMOS transmission gate, a switch matrix where the connection
between the supercapacitor changes from parallel to series, a digital control unit that controls the topology switch of the supercapacitors, a comparator that compares the supercapacitor voltage coming through a voltage divider with a voltage reference, a timer and a counter that is used to activate the comparator. There are two LDO (low dropout) regulators in the energy management unit. The output from the switch matrix is converted to a stable 1.8V voltage by the main LDO regulator and is sent to the implant. The output from the switch matrix goes to another low-power LDO regulator that powers different circuitry of the energy management unit. The project work focuses on building this low-power low dropout regulator for the energy management unit. As the energy management unit has to operate continuously, the low-power LDO regulator has to be active continuously. Thus a lower power consumption is necessary for the regulator so that the energy management unit does not consume more energy than it supplies by discharging the capacitors to a lower voltage. The LDO regulator is designed in Cadence design environment using X-Fab 180nm XH018 technology. The regulator is designed using a two-stage operational amplifier as an error amplifier, a PMOS transistor as the pass device, and a series of diode-connected PMOS transistors as the feedback network. For the frequency compensation, an internal compensation scheme with a miller capacitor and a zero nulling resistor is followed. Finally, the results show that the LDO regulator exhibits a stable 1.8V output voltage and has a dropout voltage of 145mV . The regulator achieves a very low quiescent current in the range of micro-amperes.
