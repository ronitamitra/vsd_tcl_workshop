# TCL for VLSI — Hands‑On Flow Automation (SDC • Yosys • QOR)
A practical, lab‑driven introduction to TCL scripting across the VLSI flow. Automate tool runs, generate clean SDC constraints, integrate with Yosys for synthesis, and produce reproducible, sign‑off‑style QOR reports. 

## DAY 0 : Setup for VSD Labs Using Oracle Virtualbox .
        - Downloaded and installed Oracle VirtualBox on Windows, unzipped the TCL Workshop  VDI file.
        - Created a new Virtual Machine in VirtualBox (Linux → Ubuntu 18.04, 64-bit). 
        - Successfully booted into Ubuntu inside VirtualBox using the VDI.
        - Verified the VM is ready for running VSD TCL Workshop tasks.

## DAY 1 : Introduction TO TCL & VSDSYNTH Toolbox Usage 
    1.  Overview and introduction to overall task for VSD LAB.
    Actual Agenda explained for the overall workshop to be executed in top - down approach.
    2.   Basic overview for subtask & tool needed 
        - Create command "vsdsynth" to pass it to tcl script. 
        - Convert all inputs (.csv) file to format[1] and SDC format, pass to synthesis tool 'YOSYS'
        - Convert. format[1] & SDC to format[2] and pass to timing tool 'Opentimer' .
        - Generate output report in form of pre-layout timing report. 

## DAY 2: Variable Creation and Processing Constraints from CSV
    Various tasks involved in format conversion 
        -Create command to pass .csv as input to tclscript through shell script
        Steps involved : 
        1. Create variables from input csv contents.
        2. Check if directories and files mentioned in csv exists or not.
        3. Read constraint file from .csv and convert it into sdc format. 
        4. Read all files in netlist directory 
        5. Create main synthesis script in format[2]. 
        6. Pass this tcl script created by user using Yosys synthesis tool. 

## DAY 3: Processing Clock and Input Constraints 
        1. Working on Algorithm to identify coloumn for clock constrains.
        2. Writing clock constraints & clock slew constraint  in sdc file.
        3. Task for diffrentiating  bits & bus. 
	4. Input constraint generation .

## Day 4: Complete Scripting and Yosys synthesis Introduction 
	1. Full script donwload and conclusion .
	2. Yoysys tool for synthesis guide and steps.
	3. Hierarchy check and error handling script for yosys.

## Day 5: Advanced Scripting Techniques and Quality of Results Generation 
	1. Synthesis main file scripting and output file editing.
	2. Introduction to 'procs'.
	3. Interpret IO delays and transition contains.    
