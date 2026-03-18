# Electron-to-Ion Speed Ratio for Current Sheet Analysis

**Electron-to-ion bulk speed ratio (Ve/Vi) as a diagnostic parameter for detecting strong electron-dominated current sheets in the solar wind**

Based on:  
*Electron-to-ion Bulk Speed Ratio as a Parameter Reflecting the Occurrence of Strong Electron-dominated Current Sheets in the Solar Wind*

---

## Short Description

Pipeline for computing electron-to-ion bulk speed ratio (Ve/Vi) and identifying electron-dominated current sheets in solar wind data.

---

## Overview

This repository implements a data-driven approach to analyze **electron-to-ion bulk speed ratio (Ve/Vi)** as a key parameter for identifying **strong electron-dominated current sheets (CSs)** in the solar wind.

This approach focuses on **kinetic plasma properties**, enabling:

- Detection of electron-scale structures  
- Identification of electron-dominated current sheets  
- Analysis of turbulence and intermittency  

---

## Scientific Motivation

Traditional current sheet detection relies on magnetic field discontinuities and may miss electron-dominated structures.

The **Ve/Vi ratio** provides:

- Sensitivity to kinetic-scale processes  
- Identification of electron-driven dynamics  
- Insight into energy dissipation and heating  

---

## What this repository does

- Loads solar wind datasets  
- Computes Ve, Vi, and Ve/Vi  
- Detects electron-dominated current sheets  
- Provides outputs for analysis and ML pipelines  

---

## Method

Key parameter:

R = Ve / Vi

Interpretation:

- R ≈ 1 → coupled plasma  
- R > 1 → electron-dominated dynamics  
- High R spikes → candidate current sheets  

---

## Use Cases

- Electron-scale current sheet detection  
- Turbulence analysis  
- Plasma physics research  
- Feature engineering for ML  

---

## Reference

Electron-to-ion Bulk Speed Ratio as a Parameter Reflecting the Occurrence of Strong Electron-dominated Current Sheets in the Solar Wind

---

## Author

Timofei Treves
