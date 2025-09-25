# LAB SESSIONS

## Day 1: Introduction to TCL and VSDSYNTH Toolbox
        1. Input Design file in csv format (openMSP430\_design\_details.csv)
 ![image](figures/day0/day_0_csv)
	2. Yoysys tool installed
 ![image](figures/day0/yosys_day0.png)
	3. vsdsynth working directory from vdi.
 ![image](figures/day0/day_0_directory.png)
	4. Opentimer Tool installed
 ![image](figures/day0/opentimer_day0.png)
 
### VSD TOOLBOX
        1. Create a shellscript vsdsynth as a command
  ![image](figures/day0/vsdtoolbox_day0.png)
	2. Create variables from input csv file into tcl script
  ![image](figures/day0/day_1_vsdsynth_0.1.png)
	3. Run ./vsdsynth in command line.
  ![image](figures/day0/day_1_vsdsynth_0.1_2.png)
	4. Script Check if the created variables path ,files, directories exist or not.
  ![image](figures/day0/day_1_vsdsynth_0.png)
	5. Run the script to verify 
  ![image](figures/day0/day_1_vsdsynth_1.png)
	6. Script for - If the input file (csv) is incorrect or not provided 
  ![image](figures/day0/day_1_vsdsynth_2.1.png)
	7. Run the script & verify. 
  ![image](figures/day0/day_1_vsdsynth_2.png)


## DAY 2: VARIABLE CREATION AND PROCESSING CONSTRAINTS FROM CSV 
  1. Script to check if input paths are correct or not 
  ![image](figures/day2/day_2_img_1.png)
  2. Print all the paths mentioned in the input csv. 
  ![image](figures/day2/day_2_img2.png)
  ![image](figures/day2/day2_img_3.png)
  3. Remove output directory to check if scripts points out missing directory.
  ![image](figures/day2/day_2_image_4.png)

### Demo for computing row numbers 
  1. Script for calculating number of rows and coloums in constraint csv file
  ![image](figures/day2/day_2_img_5.png)
  2. csv file for constraints 
  ![image](figures/day2/day_2_img_6.png)
  3. Number of rows and coloumns for clock constraints
  ![image](figures/day2/day_2_img_7.png)

## DAY 3: PROCESSING CLOCK AND INPUT CONSTRAINTS 
  1. Processing clock constraints coloumn wise matrix
  ![image](figures/day3/day_3_img_1.png)
  2. Dumping clock sdc constraint till matrix counts
  ![image](figures/day3/day_3_img_2.pngi)
  3. Running tcl to dump .sdc constraints for clocks
  ![image](figures/day3/day_3_img_3.png)
  ![image](figures/day3/day_3_img_4.png)
  4. 
  ![image](figures/day3/day_3_img_5.png)
  ![image](figures/day3/day_3_img_6.png)
  ![image](figures/day3/day_3_img_7.png)
  ![image](figures/day3/day_3_img_8.png)
  ![image](figures/day3/day_3_img_9.png)
  ![image](figures/day3/day_3_img_10.png)
  ![image](figures/day3/day_3_img_11.png)

 





  
