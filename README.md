# Remote Debugging ARM Cortex Target:

A case study on the propagation of target "step" command from gdb running on the host PC to the remote target, Mbed LPC1768 (ARM Cortex M3).

This report includes a brief study of the following components: 

1) The architecture and internals of gdb

2) Remote Serial Protocol

3) Python OCD

4) CMSIS DAP Interface Firmware and 

5) ARM Debug Interface's Serial Wire Debug Protocol. 

It also analyzes how "step" command entered at the host is propagated down to the target's Debug Registers, through these components, and analyzes the call stack in each case. 

Files:

The Step Command_ A Closer Look.pdf	 - The Report

StepCommand_ReportPresentation.pptx  - Report Presentation

mbed_*.tdc                           - Beagle USB 5000 Protocol Analyzer captures of the relevant USB Protocol Transactions.

![alt text](https://github.com/kripa-v/How-It-Works--Remote-Debugging-ARM-Target/edit/master/cmsis.jpg?raw=true)
