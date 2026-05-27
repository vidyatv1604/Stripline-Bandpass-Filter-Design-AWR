# Stripline-Bandpass-Filter-Design-AWR
Designed and simulated a stripline bandpass filter using AWR Microwave Office, achieving desired center frequency and bandwidth. Performed S-parameter analysis, impedance matching, and generated PCB layout while considering high-frequency effects for RF applications.

##  Overview

This project presents the design and simulation of a **stripline bandpass filter** for RF applications. The filter is designed to achieve a specified center frequency and bandwidth with good selectivity, low insertion loss, and proper impedance matching.


##  Objectives

* Design a stripline-based bandpass filter
* Achieve desired **center frequency and bandwidth**
* Ensure **impedance matching (50 Ω)**
* Analyze **S-parameters (S11, S21)**
* Generate **PCB layout** for fabrication

##  Design Methodology

* Selected appropriate **filter type (Butterworth/Chebyshev)**
* Calculated **coupling coefficients (K)** and **external quality factor (Q)**
* Designed **coupled transmission line sections**
* Optimized dimensions based on substrate properties
* Simulated using **AWR Microwave Office**


##  Substrate Parameters

* Material: **RO4003**
* Dielectric Constant (εr): 3.38
* Thickness: 0.813 mm
* Copper Thickness: 35 µm


##  Simulation & Analysis

* Evaluated **S11 (return loss)** and **S21 (insertion loss)**
* Verified passband performance and bandwidth
* Observed frequency response and selectivity
* Performed basic **impedance matching and stability checks**


##  PCB Layout

* Generated layout directly from AWR schematic
* Maintained controlled impedance transmission lines
* Considered high-frequency effects in layout design


##  Results

* Achieved desired **bandpass response**
* Good **return loss in passband**
* Acceptable **insertion loss**
* Layout suitable for fabrication


##  Tools Used

* AWR Microwave Office
* Microstrip/Stripline models (MLIN, MLEF, etc.)
