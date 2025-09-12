
# CMOS-Circuit-Design-workshop
CMOS Circuit Design workshop 25.8-3.9.2025


<img width="1191" height="580" alt="image" src="https://github.com/user-attachments/assets/81c972d8-d197-4d79-9f97-9cfbf1eb22f7" />

## Overview

This workshop is designed to provide a deep understanding of CMOS design fundamentals through SPICE simulations. Over five days, participants will explore the behavior of NMOS and CMOS inverters in different operating regions, evaluate switching thresholds, noise margins, and analyze robustness against supply and device variations. Each session includes hands-on SPICE simulations backed by strong theoretical foundations, making it ideal for learners who wish to master transistor-level circuit behavior.

The global semiconductor resurgence – fueled by sovereign CHIPS initiatives, a surging demand for edge‑AI silicon, and an acute shortage of analog‑mixed‑signal talent – has made open, mature‑node platforms like SKY130 the fastest on‑ramp from idea to tape‑out. This ten‑day, cloud based online workshop positions you at the heart of that movement, translating industry‑grade CMOS theory into actionable design insight while leveraging the very PDK that start‑ups, national fabs, and university shuttle programs now rely on for first‑silicon success.

Across 10-days, you will dissect device physics, construct parameter‑swept SPICE decks, and benchmark inverter robustness under real‑world process and voltage variation. Each module pairs concise lectures with guided labs – covering velocity‑saturation, noise‑margin optimisation, dynamic power analysis, and script‑driven verification – so every concept is cemented by plots you generate yourself. Exclusive toolchains, reference designs, and daily design clinics ensure you leave with reusable IP blocks and a repeatable simulation workflow that dovetails directly into open‑source RTL‑to‑GDS flows such as OpenLane and VSDFlow.

Graduates emerge ready to contribute immediately to low‑power IoT nodes, automotive safety ICs, and chiplet‑based heterogenous packages – all markets leaning heavily on 130 nm for cost‑balanced innovation. Whether you aim to upskill a design team, strengthen research credentials, or fast‑track a prototype toward fabrication, this program delivers the simulation mastery and process‑aware mindset demanded by today’s accelerated semiconductor landscape.

------------------------------------------------------------

## NgspiceSky130 - Day 1 - Basics of NMOS Drain current (Id) vs Drain-to-source Voltage (Vds)
------------------------------------------------------------
<details>
<summary>Introduction to Circuit Design and SPICE simulations</summary>
  
### Introduction to Circuit Design and SPICE simulations ###
    
- L1 Why do we need SPICE simulations?

  <

  
- L2 Introduction to basic element in Circuit design – NMOS


<img width="1796" height="843" alt="image" src="https://github.com/user-attachments/assets/4a2b07d5-41fa-4d0f-8ab0-1e1bdc3087cd" />


<img width="1792" height="842" alt="image" src="https://github.com/user-attachments/assets/ae94c9b3-623f-49a1-bf57-3cbc145b2dd8" />


- L3 Strong inversion and threshold voltage

<img width="1792" height="842" alt="image" src="https://github.com/user-attachments/assets/161f760f-5bfe-48a1-90e5-63f95d3bd903" />


<img width="1962" height="751" alt="image" src="https://github.com/user-attachments/assets/e42d18c3-4e4c-4ed4-bc7c-5a69278058dd" />


<img width="1962" height="751" alt="image" src="https://github.com/user-attachments/assets/bb97050c-5569-494c-9e8f-78d3ace27b85" />


<img width="1837" height="843" alt="image" src="https://github.com/user-attachments/assets/04355acb-8a45-4a56-b9b5-b12e9e0c87a3" />


<img width="1701" height="844" alt="image" src="https://github.com/user-attachments/assets/2af88005-3543-4eb4-9897-2590d7876ddd" />

<img width="1710" height="828" alt="image" src="https://github.com/user-attachments/assets/70f222c4-c63b-400e-aa56-241fab6c61e4" />

<img width="1704" height="824" alt="image" src="https://github.com/user-attachments/assets/d6b89001-627d-4c45-bf0f-50bd8a733792" />

<img width="1796" height="844" alt="image" src="https://github.com/user-attachments/assets/6e5e4d55-4706-4c58-a9d3-0bbd0d570e05" />


<img width="1914" height="926" alt="image" src="https://github.com/user-attachments/assets/bf9a9287-dc70-484c-afda-51883b5d8687" />

- L4 Threshold voltage with positive substrate potential

<img width="1826" height="874" alt="image" src="https://github.com/user-attachments/assets/e2225b29-23c5-44ab-b755-1ca8b1f3f0df" />
 
 </details>  

<details>			
<summary>NMOS resistive region and saturation region of operation</summary>

### NMOS resistive region and saturation region of operation

- L1 Resistive region of operation with small drain-source voltage

<img width="1870" height="839" alt="image" src="https://github.com/user-attachments/assets/dd7b9b01-34bf-4b4d-87e4-a09fdd3ecf95" />

  
- L2 Drift current theory

  <img width="1846" height="844" alt="image" src="https://github.com/user-attachments/assets/1084f4e9-1165-4e0b-9911-5ac06fd62210" />

  <img width="1897" height="842" alt="image" src="https://github.com/user-attachments/assets/c3b5b71e-9384-421c-835f-6a3bc39689aa" />

  <img width="1793" height="924" alt="image" src="https://github.com/user-attachments/assets/4a8c0e54-123c-4c55-9798-b72ccb6f872d" />

  



  
- L3 Drain current model for linear region of operation
  
- L4 SPICE conclusion to resistive operation
   
- L5 Pinch-off region condition
    
- L6 Drain current model for saturation region of operation
  
</details>		

<details>		
<summary>Introduction to SPICE</summary>

### Introduction to SPICE
    
- L1 Basic SPICE setup
     
- L2 Circuit description in SPICE syntax
    
- L3 Define technology parameters
     
- **L4 First SPICE simulation**

enter following command to clone repository:

git clone https://github.com/kunalg123/sky130CircuitDesignWorkshop.git
 
 <img width="893" height="218" alt="image" src="https://github.com/user-attachments/assets/3daa0f57-a4b8-4e61-8dab-8fadbf1c1eb8" />

goto "~/sky130CircuitDesignWorkshop/design"

<img width="1068" height="277" alt="image" src="https://github.com/user-attachments/assets/98a0d853-f0ba-4808-b7f7-3db1cea335b0" />

cell definition which wer use in our workshop are in "~/sky130CircuitDesignWorkshop/design/sky130_fd_pr/cells".

nfet_01v8 - NMOS
pfet_01v8 - PMOS

<img width="741" height="142" alt="image" src="https://github.com/user-attachments/assets/6c827099-482c-4f19-a0b1-bb63989c3b00" />

if we go to "nfet_01v8" and do an ls we have all lib files for different corners.

<img width="1250" height="171" alt="image" src="https://github.com/user-attachments/assets/6e6ce39e-adc8-48ac-bd4e-24a4246fa7a8" />

file "sky130_fd_pr__nfet_01v8__tt.pm3.spice" contain different model parameters.

``` spice
* Copyright 2020 The SkyWater PDK Authors
*
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*
*     https://www.apache.org/licenses/LICENSE-2.0
*
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.

* SKY130 Spice File.
* Number of bins: 63
.param
+ sky130_fd_pr__nfet_01v8__toxe_mult = 1.0
+ sky130_fd_pr__nfet_01v8__rshn_mult = 1.0
+ sky130_fd_pr__nfet_01v8__overlap_mult = 0.9642
+ sky130_fd_pr__nfet_01v8__lint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__wint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__dlc_diff = -.61492e-9
+ sky130_fd_pr__nfet_01v8__dwc_diff = 0.0
*
* sky130_fd_pr__nfet_01v8, Bin 000, W = 1.26, L = 0.15
* -----------------------------------
+ sky130_fd_pr__nfet_01v8__voff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__kt1_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_0 = -1.1675e-19
+ sky130_fd_pr__nfet_01v8__pditsd_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_0 = 1.3935e-11
+ sky130_fd_pr__nfet_01v8__vsat_diff_0 = 594.41
+ sky130_fd_pr__nfet_01v8__tvoff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__a0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__b0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__rdsw_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__k2_diff_0 = 0.0031843
+ sky130_fd_pr__nfet_01v8__vth0_diff_0 = -0.024441
+ sky130_fd_pr__nfet_01v8__nfactor_diff_0 = 0.37668
+ sky130_fd_pr__nfet_01v8__u0_diff_0 = -0.0034894
+ sky130_fd_pr__nfet_01v8__eta0_diff_0 = 0.0
........

```

file "sky130_fd_pr__nfet_01v8__tt.corner.spice" contein different L andW parameters

``` spice
* Copyright 2020 The SkyWater PDK Authors
*
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*
*     https://www.apache.org/licenses/LICENSE-2.0
*
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.

* SKY130 Spice File.
* Number of bins: 63
.param
+ sky130_fd_pr__nfet_01v8__toxe_mult = 1.0
+ sky130_fd_pr__nfet_01v8__rshn_mult = 1.0
+ sky130_fd_pr__nfet_01v8__overlap_mult = 0.9642
+ sky130_fd_pr__nfet_01v8__lint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__wint_diff = 0.0
+ sky130_fd_pr__nfet_01v8__dlc_diff = -.61492e-9
+ sky130_fd_pr__nfet_01v8__dwc_diff = 0.0
*
* sky130_fd_pr__nfet_01v8, Bin 000, W = 1.26, L = 0.15
* -----------------------------------
+ sky130_fd_pr__nfet_01v8__voff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__kt1_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_0 = -1.1675e-19
+ sky130_fd_pr__nfet_01v8__pditsd_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_0 = 1.3935e-11
+ sky130_fd_pr__nfet_01v8__vsat_diff_0 = 594.41
+ sky130_fd_pr__nfet_01v8__tvoff_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__a0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__b0_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__rdsw_diff_0 = 0.0
+ sky130_fd_pr__nfet_01v8__k2_diff_0 = 0.0031843
+ sky130_fd_pr__nfet_01v8__vth0_diff_0 = -0.024441
+ sky130_fd_pr__nfet_01v8__nfactor_diff_0 = 0.37668
+ sky130_fd_pr__nfet_01v8__u0_diff_0 = -0.0034894
+ sky130_fd_pr__nfet_01v8__eta0_diff_0 = 0.0

* sky130_fd_pr__nfet_01v8, Bin 001, W = 1.68, L = 0.15
* -----------------------------------
+ sky130_fd_pr__nfet_01v8__eta0_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__b1_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__voff_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__kt1_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_1 = -1.6979e-19
+ sky130_fd_pr__nfet_01v8__pditsd_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_1 = 1.0381e-11
+ sky130_fd_pr__nfet_01v8__vsat_diff_1 = 249.83
+ sky130_fd_pr__nfet_01v8__tvoff_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__a0_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__b0_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__rdsw_diff_1 = 0.0
+ sky130_fd_pr__nfet_01v8__k2_diff_1 = 0.0047171
+ sky130_fd_pr__nfet_01v8__vth0_diff_1 = 0.0064909
+ sky130_fd_pr__nfet_01v8__nfactor_diff_1 = 0.31936
+ sky130_fd_pr__nfet_01v8__u0_diff_1 = -0.002698
*
* sky130_fd_pr__nfet_01v8, Bin 002, W = 1.0, L = 1.0
* ---------------------------------
+ sky130_fd_pr__nfet_01v8__nfactor_diff_2 = 1.11
+ sky130_fd_pr__nfet_01v8__u0_diff_2 = -9.2293e-5
+ sky130_fd_pr__nfet_01v8__vth0_diff_2 = 0.0065633
+ sky130_fd_pr__nfet_01v8__eta0_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__b1_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__voff_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__ub_diff_2 = 1.6548e-19
+ sky130_fd_pr__nfet_01v8__kt1_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__pditsd_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__ua_diff_2 = 4.5462e-13
+ sky130_fd_pr__nfet_01v8__vsat_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__tvoff_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__ags_diff_2 = -0.052872
+ sky130_fd_pr__nfet_01v8__a0_diff_2 = 0.23412
+ sky130_fd_pr__nfet_01v8__b0_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__pclm_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__pdits_diff_2 = 0.0
+ sky130_fd_pr__nfet_01v8__keta_diff_2 = 0.0
*
.......

```
in design folder i created a spice file with L=0.25 and W=0.65 and run spice simulation.

run:
ngspice day1_nfet_idvds_L025_W065.spice

``` cmd
vsduser@vsduser:~/sky130CircuitDesignWorkshop/design$ ngspice day1_nfet_idvds_L025_W065.spice
******
** ngspice-44+ : Circuit level simulation program
** Compiled with KLU Direct Linear Solver
** The U. C. Berkeley CAD Group
** Copyright 1985-1994, Regents of the University of California.
** Copyright 2001-2024, The ngspice team.
** Please get your ngspice manual from https://ngspice.sourceforge.io/docs.html
** Please file your bug-reports at http://ngspice.sourceforge.net/bugrep.html
** Creation Date: Thu Jul 17 12:48:03 UTC 2025
******

Note: No compatibility mode selected!


Circuit: *model description

Doing analysis at TEMP = 27.000000 and TNOM = 27.000000

Using SPARSE 1.3 as Direct Linear Solver
 Reference value :  1.70000e+00
No. of Data Rows : 190

No. of Data Rows : 1
Here are the vectors currently active:

Title: *model description
Name: op1 (Operating Point)
Date: Tue Sep  2 20:31:35  2025

    in                  : voltage, real, 1 long
    m.xm1.msky130_fd_pr__nfet_01v8#body: voltage, real, 1 long
    m.xm1.msky130_fd_pr__nfet_01v8#dbody: voltage, real, 1 long
    m.xm1.msky130_fd_pr__nfet_01v8#sbody: voltage, real, 1 long
    n1                  : voltage, real, 1 long
    vdd                 : voltage, real, 1 long [default scale]
    vdd#branch          : current, real, 1 long
    vin#branch          : current, real, 1 long
ngspice 22 -> 
ngspice 23 -> 


```

<img width="936" height="749" alt="image" src="https://github.com/user-attachments/assets/2cafd8c1-1f55-40d2-9b7c-69e1e4b2951b" />


now plot vdd over vin

``` cmd

.......
    vdd                 : voltage, real, 1 long [default scale]
    vdd#branch          : current, real, 1 long
    vin#branch          : current, real, 1 long
ngspice 20 -> plot -vdd#branch
ngspice 21 -> 


```

will bring up this graph

<img width="1605" height="822" alt="image" src="https://github.com/user-attachments/assets/ffb7650b-cf0f-4a91-9498-c2585a2a86f3" />


check lenght at 1,6V curve with Vin of 1,2V

<img width="1325" height="924" alt="image" src="https://github.com/user-attachments/assets/2c11b9ae-36bb-4299-a77b-f76e69e84f52" />

where y0 is 0.000177018 = 177 microns

``` cmd

ngspice 21 -> 
x0 = 1.2, y0 = 0.000177018

```

<img width="392" height="219" alt="image" src="https://github.com/user-attachments/assets/ce9c7be5-916c-413a-b464-a692129883b8" />








- **L5 SPICE Lab with sky130 models**

spice simulation with L=2 and W=5, file "day1_nfet_idvds_L2_W5.spice"

to run spice simulation enter "ngspice day1_nfet_idvds_L2_W5.spice"

<img width="892" height="734" alt="image" src="https://github.com/user-attachments/assets/85f386af-c5e9-40ae-9f5b-71ec6aea21fb" />


and plot Id over Vdd


<img width="1826" height="961" alt="image" src="https://github.com/user-attachments/assets/11ce6a49-584f-4fcd-9eea-dad766299e51" />


	
 	cutoff region


<img width="1833" height="967" alt="image" src="https://github.com/user-attachments/assets/92cab910-2929-40a2-9068-b3b21d498e4d" />


at 1.3V we have 279 u

``` cmd

ngspice 24 -> 
x0 = 1.3, y0 = 0.000279104



```


<img width="659" height="252" alt="image" src="https://github.com/user-attachments/assets/a39491e0-80e3-4762-9d05-e98ff13009f4" />




    
 </details> 

------------------------------------------------------------

## NgspiceSky130 - Day 2 - Velocity saturation and basics of CMOS inverter VTC	
------------------------------------------------------------

<details>
<summary>SPICE simulation for lower nodes and velocity saturation effect</summary>
  
###	SPICE simulation for lower nodes and velocity saturation effect	

- L1 SPICE simulation for lower nodes

- L2 Drain current vs gate voltage for long and short channel device

- L3 Velocity saturation at lower and higher electric fields

- L4 Velocity saturation drain current model

- **L5 Labs Sky130 Id-Vgs**

doing simulation with sweeping Vdd and Vin

```spice
Model Description
.param temp=27


*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt


*Netlist Description



XM1 Vdd n1 0 0 sky130_fd_pr__nfet_01v8 w=0.39 l=0.15

R1 n1 in 55

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op
.dc Vdd 0 1.8 0.1 Vin 0 1.8 0.2

.control

run
display
setplot dc1
.endc

.end

```

running ngspice and plot curve:

<img width="1654" height="833" alt="image" src="https://github.com/user-attachments/assets/58908838-dc5e-4855-932e-a9d1c20210d0" />


for lower values of Vgs ist showing "qudratic" behavior", for higher values of Vgs ist showing "linar" behavior!

<img width="768" height="993" alt="image" src="https://github.com/user-attachments/assets/39da3d71-4bc8-4f57-90fb-df2e5d01b1df" />

x0 = 1.80056, y0 = 0.000197836

at 1,8V max Id is at 197.8 u

next we keep Vdd constant at 1.8V and sweeping Vin

``` spice

Model Description
.param temp=27


*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt


*Netlist Description

XM1 Vdd n1 0 0 sky130_fd_pr__nfet_01v8 w=0.39 l=0.15

R1 n1 in 55

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op
.dc Vin 0 1.8 0.1 

.control

run
display
setplot dc1
.endc

.end


```

simulation show one plot


<img width="1859" height="846" alt="image" src="https://github.com/user-attachments/assets/3d8fb0b5-da9a-4109-a235-2f44e10d1bbd" />

curve is showing "linear" behavior


- **L6 Labs Sky130 Vt**

calculate Vt  for Id vs Vgs

start simulation with "ngspice day2_nfet_idvgs_L015_W039.spice"


plot vdd#branch, put a tangent on linear part until x-axis,it get around 0.77V as Vt


<img width="1403" height="877" alt="image" src="https://github.com/user-attachments/assets/90e66454-4110-49e5-8958-b1ff059d2b17" />

  
</details>

<details>
<summary>CMOS voltage transfer characteristics (VTC)</summary>

###	CMOS voltage transfer characteristics (VTC)

- L1 MOSFET as a switch

- L2 Introduction to standard MOS voltage current parameters

- L3 PMOS/NMOS drain current v/s drain voltage

- L4 Step1 – Convert PMOS gate-source-voltage to Vin

- L5 Step2 & Step3 – Convert PMOS and NMOS drain-source-voltage to vout

- L6 Step4 – Merge PMOS – NMOS load curves and plot VTC

</details>

----------------------------------------
## NgspiceSky130 - Day 3 - CMOS Switching threshold and dynamic simulations
----------------------------------------

<details>
<summary>Voltage transfer characteristics – SPICE simulations</summary>
  
### Voltage transfer characteristics – SPICE simulations

- L1 SPICE deck creation for CMOS inverter

- L2 SPICE simulation for CMOS inverter

- **L3 Labs Sky130 SPICE simulation for CMOS**

plot Vtc characteristic of a CMOS inverter

do simulation and find out switching voltage.

run "ngspice day3_inv_vtc_Wp084_Wn036.spice"

``` ngspice
vsduser@vsduser:~/sky130CircuitDesignWorkshop/design$ ngspice day3_inv_vtc_Wp084_Wn036.spice
******
** ngspice-44+ : Circuit level simulation program
** Compiled with KLU Direct Linear Solver
** The U. C. Berkeley CAD Group
** Copyright 1985-1994, Regents of the University of California.
** Copyright 2001-2024, The ngspice team.
** Please get your ngspice manual from https://ngspice.sourceforge.io/docs.html
** Please file your bug-reports at http://ngspice.sourceforge.net/bugrep.html
** Creation Date: Thu Jul 17 12:48:03 UTC 2025
******

Note: No compatibility mode selected!


Circuit: *model description

Doing analysis at TEMP = 27.000000 and TNOM = 27.000000

Using SPARSE 1.3 as Direct Linear Solver
 Reference value :  1.48000e+00
No. of Data Rows : 181

No. of Data Rows : 1
Here are the vectors currently active:

Title: *model description
Name: dc1 (DC transfer characteristic)
Date: Tue Sep  2 22:11:57  2025

    in                  : voltage, real, 181 long
    m.xm1.msky130_fd_pr__pfet_01v8#body: voltage, real, 181 long
    m.xm1.msky130_fd_pr__pfet_01v8#dbody: voltage, real, 181 long
    m.xm1.msky130_fd_pr__pfet_01v8#sbody: voltage, real, 181 long
    m.xm2.msky130_fd_pr__nfet_01v8#body: voltage, real, 181 long
    m.xm2.msky130_fd_pr__nfet_01v8#dbody: voltage, real, 181 long
    m.xm2.msky130_fd_pr__nfet_01v8#sbody: voltage, real, 181 long
    out                 : voltage, real, 181 long
    v-sweep             : voltage, real, 181 long [default scale]
    vdd                 : voltage, real, 181 long
    vdd#branch          : current, real, 181 long
    vin#branch          : current, real, 181 long
ngspice 31 -> 

```

do the plot.

ngspice -> plot out vsin

<img width="1204" height="834" alt="image" src="https://github.com/user-attachments/assets/69b20395-6943-4ec8-ad14-147b81813489" />

We are looking for switching threshold!

Vtc ist around 0.876 V

next we do transient analysis calculation rise and fall delay:

spice file that we use "day3_inv_tran_Wp084_Wn036.spice"

```spice
*Model Description
.param temp=27


*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt


*Netlist Description


XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=0.84 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.36 l=0.15


Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 PULSE(0V 1.8V 0 0.1ns 0.1ns 2ns 4ns)

*simulation commands

.tran 1n 10n

.control
run
.endc

.end

```
let run spice simulation:

<img width="1000" height="841" alt="image" src="https://github.com/user-attachments/assets/fd8258a5-dd55-429f-8dc6-b6901efb1e6a" />

now we "plot out vs time in"

<img width="1272" height="930" alt="image" src="https://github.com/user-attachments/assets/cac13a60-0337-4bb9-a9c5-d739df073423" />

we calculate raise an fall delay of inverter.It will be arounf 0.9V.

we zoom in and click on red and blue curve at 0.9V

we get following points:

``` spice

ngspice 34 -> 
x0 = 2.48314e-09, y0 = 0.899474

x0 = 2.15058e-09, y0 = 0.898947


```


<img width="1318" height="885" alt="image" src="https://github.com/user-attachments/assets/8e0947fd-873c-47e0-89ef-13e6c7cbdffb" />

calculation of risedelay:

2.483 - 2.151 = 0.332 ps

lets do same for fall delay:

<img width="1316" height="920" alt="image" src="https://github.com/user-attachments/assets/aa101201-9f34-43c2-a2db-927f50272b53" />


``` spice

ngspice 34 -> 
x0 = 4.33469e-09, y0 = 0.899545

x0 = 4.05102e-09, y0 = 0.899091

```

falldelay: 
4.334 - 4.051 = 0.283 ns


thats the way to calculate rise & fall delay in transient analyisis.

</details>

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Switching Threshold</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Switching Threshold
	
- L1 Switching Threshold, Vm

- L2 Analytical expression of Vm as a function of (W/L)p and (W/L)n

- L3 Analytical expression of (W/L)p and (W/L)n as a function of Vm

- L4 Static and dynamic simulation of CMOS inverter

- L5 Static and dynamic simulation of CMOS inverter with increased PMOS width

- L6 Applications of CMOS inverter in clock network and STA

</details>

-------------------------------
## NgspiceSky130 - Day 4 - CMOS Noise Margin robustness evaluation
-------------------------------

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Noise margin</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Noise margin	

- L1 Introduction to noise margin

- L2 Noise margin voltage parameters

- L3 Noise margin equation and summary

- L4 Noise margin variation with respect to PMOS width

- **L5 Sky130 Noise margin labs**

we plot noise margin:

we use spice file "day4_inv_noisemargin_wp1_wn036.spice"

``` spice

*Model Description
.param temp=27


*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt


*Netlist Description


XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=1 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.36 l=0.15


Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op

.dc Vin 0 1.8 0.01

.control
run
setplot dc1
display
.endc

.end

```

run simulation:

<img width="1016" height="879" alt="image" src="https://github.com/user-attachments/assets/9e03e2b7-e16d-478c-b3c2-b9a3339d3a1c" />

now "plot out vs in"in ngspice

<img width="1204" height="834" alt="image" src="https://github.com/user-attachments/assets/1513c007-65ad-4fe3-b896-c4f6ae027403" />

ngspice 36 -> plot out vs in
ngspice 37 -> 

<img width="1476" height="911" alt="image" src="https://github.com/user-attachments/assets/b9b55f38-1dcb-4e5f-8188-2526db5aa198" />

x0 = 0.777333, y0 = 1.6975

x0 = 0.977333, y0 = 0.1075




for noisemargin high we have to calculate 

1.697 - 0.977 = 0,72V

noisemargin low will be:

0.777 - 0.1075 = 0.6695 V


</details>

----------------------------------
## NgspiceSky130 - Day 5 - CMOS power supply and device variation robustness evaluation
----------------------------------

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Power supply variation</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Power supply variation

- L1 Smart SPICE simulation for power supply variations

- L2 Advantages and disadvantages using low supply voltage

- **L3 Sky130 Supply Variation Labs**

  now we calculate supply variation with spice file "day5_inv_supplyvariation_Wp1_Wn036.spice"

``` spice

Model Description
.param temp=27


*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt


*Netlist Description


XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=1 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.36 l=0.15


Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 1.8V

.control

let powersupply = 1.8
alter Vdd = powersupply
        let voltagesupplyvariation = 0
        dowhile voltagesupplyvariation < 6
        dc Vin 0 1.8 0.01
        let powersupply = powersupply - 0.2
        alter Vdd = powersupply
        let voltagesupplyvariation = voltagesupplyvariation + 1
      end
 
plot dc1.out vs in dc2.out vs in dc3.out vs in dc4.out vs in dc5.out vs in dc6.out vs in xlabel "input voltage(V)" ylabel "output voltage(V)" title "Inveter dc characteristics as a function of supply voltage"

.endc

.end

```


run spice simulation

<img width="1368" height="988" alt="image" src="https://github.com/user-attachments/assets/b323a335-eb4f-44ad-b8aa-733793c647e7" />

plot:

Vdc curve for different volatges

<img width="1777" height="992" alt="image" src="https://github.com/user-attachments/assets/4096d866-8899-4851-ae17-55301eea577e" />

lets calculate gain for 1.8V curve

values are 

``` spice

ngspice 37 -> 
x0 = 0.780208, y0 = 1.69149

x0 = 0.980208, y0 = 0.112766

```

<img width="751" height="173" alt="image" src="https://github.com/user-attachments/assets/f91243fa-f9a3-4d91-887a-c4787a64d466" />


</details>

<details>
<summary>Static behavior evaluation – CMOS inverter robustness – Device variation</summary>
	
### Static behavior evaluation – CMOS inverter robustness – Device variation	

- L1 Sources of variation – Etching process

- L2 Sources of variation – oxide thickness

- L3 Smart SPICE simulation for device variations

- L4 Conclusion

- **L5 Sky130 Device Variation Labs**

  devicevariation is final lab:

  spice file we use is "day5_inv_devicevariation_wp7_wn042.spice"

``` spice

*Model Description
.param temp=27


*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt


*Netlist Description


XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=7 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.42 l=0.15


Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op

.dc Vin 0 1.8 0.01

.control
run
setplot dc1
display
.endc

.end


```

run sumulation:

<img width="1120" height="882" alt="image" src="https://github.com/user-attachments/assets/a570d2ea-20f7-4945-8bfc-a3428f7444a9" />


plot out vs in

<img width="1195" height="985" alt="image" src="https://github.com/user-attachments/assets/2f20e11e-34ec-4680-91c8-0474558aa932" />

find switching threshold value

<img width="1168" height="1005" alt="image" src="https://github.com/user-attachments/assets/02219237-fd17-497f-813f-c128325d9cd8" />

x/y value will be: 

x0 = 0.987945, y0 = 0.990417

Switching threshold is around 80mV






</details>

------------------------------------------------------------
### Acknowledgments

- #### Kunal Ghosh, Director, VSD Corp. Pvt. Ltd.
