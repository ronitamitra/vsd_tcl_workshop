# TCL for VLSI — Hands‑On Flow Automation (SDC • Yosys • QOR)
A practical, lab‑driven introduction to TCL scripting across the VLSI flow. Automate tool runs, generate clean SDC constraints, integrate with Yosys for synthesis, and produce reproducible, sign‑off‑style QOR reports. 

## DAY 0 : Setup for VSD Labs Using Oracle Virtualbox .
## DAY 1 : Introduction TO TCL & VSDSYNTH Toolbox Usage 
    1.  Overview and introduction to overall task for VSD LAB.
    Actual Agenda explained for the overall workshop to be executed in top - down approach.
    2.   Basic overview for subtask & tool needed 
        - Create command "vsdsynth" to pass it to tcl script. 
        - Convert all inputs (.csv) file to format[1] and SDC format, pass to synthesis tool 'YOSYS'
        - Convert. format[1] & SDC to format[2] and pass to timing tool 'Opentimer' .
        - Generate output report in form of pre-layout timing report. 

## DAY 2: Variable Creation and Processing Constraints from CSV
