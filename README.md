
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

  

  
- L2 Introduction to basic element in Circuit design – NMOS





- L3 Strong inversion and threshold voltage



- L4 Threshold voltage with positive substrate potential


### NMOS resistive region and saturation region of operation

- L1 Resistive region of operation with small drain-source voltage



  
- L2 Drift current theory

  



  
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






- **L5 SPICE Lab with sky130 models**


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



- **L6 Labs Sky130 Vt**



###	CMOS voltage transfer characteristics (VTC)

- L1 MOSFET as a switch

- L2 Introduction to standard MOS voltage current parameters

- L3 PMOS/NMOS drain current v/s drain voltage

- L4 Step1 – Convert PMOS gate-source-voltage to Vin

- L5 Step2 & Step3 – Convert PMOS and NMOS drain-source-voltage to vout

- L6 Step4 – Merge PMOS – NMOS load curves and plot VTC


----------------------------------------
## NgspiceSky130 - Day 3 - CMOS Switching threshold and dynamic simulations
----------------------------------------


  
### Voltage transfer characteristics – SPICE simulations

- L1 SPICE deck creation for CMOS inverter

- L2 SPICE simulation for CMOS inverter

- **L3 Labs Sky130 SPICE simulation for CMOS**


### Static behavior evaluation – CMOS inverter robustness – Switching Threshold
	
- L1 Switching Threshold, Vm

- L2 Analytical expression of Vm as a function of (W/L)p and (W/L)n

- L3 Analytical expression of (W/L)p and (W/L)n as a function of Vm

- L4 Static and dynamic simulation of CMOS inverter

- L5 Static and dynamic simulation of CMOS inverter with increased PMOS width

- L6 Applications of CMOS inverter in clock network and STA



-------------------------------
## NgspiceSky130 - Day 4 - CMOS Noise Margin robustness evaluation
-------------------------------


	
### Static behavior evaluation – CMOS inverter robustness – Noise margin	

- L1 Introduction to noise margin

- L2 Noise margin voltage parameters

- L3 Noise margin equation and summary

- L4 Noise margin variation with respect to PMOS width

- **L5 Sky130 Noise margin labs**



----------------------------------
## NgspiceSky130 - Day 5 - CMOS power supply and device variation robustness evaluation
----------------------------------


	
### Static behavior evaluation – CMOS inverter robustness – Power supply variation

- L1 Smart SPICE simulation for power supply variations

- L2 Advantages and disadvantages using low supply voltage

- **L3 Sky130 Supply Variation Labs**

  
### Static behavior evaluation – CMOS inverter robustness – Device variation	

- L1 Sources of variation – Etching process

- L2 Sources of variation – oxide thickness

- L3 Smart SPICE simulation for device variations

- L4 Conclusion

- **L5 Sky130 Device Variation Labs**

  








------------------------------------------------------------
### Acknowledgments

- #### Kunal Ghosh, Director, VSD Corp. Pvt. Ltd.
