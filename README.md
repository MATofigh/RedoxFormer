# RedoxFormer Dataset

Run-to-Failure Power Density Dataset for Early-Stage Degradation Detection in Solid Oxide Fuel Cells (SOFCs)

## Overview

This repository contains experimental time-series datasets collected from accelerated nickel redox-cycling degradation tests on laboratory-scale Solid Oxide Fuel Cells (SOFCs).

The dataset was generated for the study:

**Tofigh, M., Hasanabadi, M. F., Nourpour, N. S., Hanifi, A. R., Smith, D. J., & Shahbakhti, M. (2026).**  
*RedoxFormer: A two-stage deep neural diagnosis framework for early-stage degradation in fuel cells via in-situ sensor measurements.*  
Applied Energy, 413, 127782.

The data consist of continuous run-to-failure power density measurements from 10 independent fuel cells sampled at 1 Hz.

---

## Dataset Summary

- System: Solid Oxide Fuel Cells (SOFCs)  
- Degradation mechanism: Nickel redox cycling  
- Number of experiments: 10 fuel cells  
- Sampling frequency: 1 Hz  
- Signal: Power density [W/cm²]  
- Data type: Time series  

---

## File Structure

Each CSV file corresponds to one fuel cell experiment.

MF0504.csv  
MF0505.csv  
MF0507.csv  
MF0508.csv  
MF0509.csv  
MF0515.csv  
MF0601.csv  
MF0603.csv  
MF0607.csv  
MF0613.csv  

Each file contains a continuous time series from the start of operation until the degradation threshold is reached.

---

## Data Format

All files are provided in CSV format with two columns:

**Time(Sec)**  
Elapsed time from the start of the experiment  
Unit: seconds  

**P(W/cm2)**  
Measured power density  
Unit: W/cm²  


---

## Intended Use

This dataset is suitable for research in:

- Fault detection and diagnosis  
- Time-series classification  
- Prognostics and health monitoring  
- Degradation modeling  
- Machine learning and deep learning for energy systems  

---

## Citation

If you use this dataset, please cite:

Tofigh, M., Hasanabadi, M. F., Nourpour, N. S., Hanifi, A. R., Smith, D. J., & Shahbakhti, M. (2026).  
RedoxFormer: A two-stage deep neural diagnosis framework for early-stage degradation in fuel cells via in-situ sensor measurements.  
Applied Energy, 413, 127782.

---

## Contact

Mohamadali Tofigh  
University of Alberta  
Email: tofigh@ualberta.ca
