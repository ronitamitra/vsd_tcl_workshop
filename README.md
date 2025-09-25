# TCL for VLSI — Hands‑On Flow Automation (SDC • Yosys • QOR)
A practical, lab‑driven introduction to TCL scripting across the VLSI flow. Automate tool runs, generate clean SDC constraints, integrate with Yosys for synthesis, and produce reproducible, sign‑off‑style QOR reports. 

## DAY 0 : Setup for VSD Labs Using Oracle Virtualbox .
        - Downloaded and installed Oracle VirtualBox on Windows, unzipped the TCL Workshop  VDI file.
        - Created a new Virtual Machine in VirtualBox (Linux → Ubuntu 18.04, 64-bit). 
        - Successfully booted into Ubuntu inside VirtualBox using the VDI.
        - Verified the VM, vdi files , yosys and Opentimer EDA is ready for running VSD TCL Workshop tasks.

## DAY 1 : Introduction TO TCL & VSDSYNTH Toolbox Usage 
    1.  Overview and introduction to overall task for VSD LAB.
	Actual Agenda explained for the overall workshop to execute tclbox, in top-down approach.
    2.  Basic overview for subtask as Part-1
        - Create command "vsdsynth" to pass it to tcl script. 
        - Convert all inputs (.csv) file to format[1] and SDC format,then pass to synthesis tool 'YOSYS'
        - Convert format[1] & SDC constraints generated to format[2] and pass to timing tool 'Opentimer' .
        - Generate output report in form of pre-layout timing report. 

## DAY 2: Variable Creation and Processing Constraints from CSV
   	Tasks involved in format conversion 
        - Create command to pass .csv as input to tclscript through shell script
	   Steps involved : 
        1. Create variables from given input csv contents (.csv files).
        2. Check if directories and files mentioned in csv exists or not.
        3. Read constraint file from .csv and convert it into sdc format. 
        4. Read all the files present in netlist directory 
        5. Create main synthesis script in format[2] (convert format[1] & sdc to format[2]). 
        6. Pass this created tcl script to Yosys synthesis tool to generate netlist. 

## DAY 3: Processing Clock and Input Constraints 
        1. Working on Algorithm to identify matrix from csv and convert to sdc and print number of rows & coloumns.
        2. Writing out clock constraints in sdc file from csv .
	3. Writing algorithm to differentiate bit and bus from verilog files.
        4. Working on Algorithm to generate input constraints in sdc  

## Day 4: Complete Scripting and Yosys synthesis Tool Introduction 
	1. Constraint generation for output ports & conclusion to sdc file.
	2. Yoysys tool Usage introduction for synthesis guide using memory design as example.
	3. Automation of RTL in Yoysys using error handling script in TCL to check  Hierarchies.

## Day 5: Advanced Scripting Techniques and Quality of Results (QoR) Generation 
	1. Synthesis main file scripting and output file editing.
	2. sdc to format[2] conversion for Opetimer tool .
	3. Introduction to 'procs'.
	4. Interpret IO delays and transition constraints.
	5. QoR generation algorithm & script to format output reports from Opentimer. 

## Workshop Session In Details : 
	--> [THEORY_SESSIONS]()
	--> [LAB_SESSIONS](https://github.com/ronitamitra/vsd_tcl_workshop/blob/2ce706f70dfcd4e647f2f2455f5ad06cfd6c02ce/LAB_SESSIONS.md)     
