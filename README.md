# cmsis-dap-report
A study on the propagation of target "step" command from gdb running on the host to the remote target, Mbed LPC1768 (ARM Cortex M3).

This report includes a brief study of the following components, and how "step" command entered at the host is propagated through these down to the target's Debug Registers:
1) The architecture of gdb
2) Remote Serial Protocol
3) Python OCD
4) CMSIS DAP Interface Firmware and 
5) ARM Debug Interface's Serial Wire Debug Protocol. - The Report


Files:
The Step Command_ A Closer Look.pdf	 - The Report
StepCommand_ReportPresentation.pptx  - Report Presentation
mbed_*.tdc                           - Beagle USB 5000 Protocol Analyzer captures of the relevant USB Protocol Transactions.

