# DSP Lab 2 — Z-Transform, System Stability & Digital Filters

MATLAB solutions for **Digital Signal Processing (DSP) Lab 2**, covering pole-zero analysis, system stability, Z-transforms, partial fraction expansion, difference equations, and basic FIR/IIR filtering.

## Requirements
* **MATLAB** (tested on R2020b or newer)
* **Signal Processing Toolbox** (`zplane`, `zp2sos`, `freqz`, `residuez`, `filtic`)
* **Control System Toolbox** (`tf`, `pzmap`)
* **Symbolic Math Toolbox** (`syms`, `ztrans`)

## Contents (`dsp_lab2.m`)

| Section | Topic | Key MATLAB Functions |
| :--- | :--- | :--- |
| **Question 1** | Transfer function construction from zeros & poles, Second-Order Sections (SOS), and BIBO stability check | `poly`, `tf`, `zp2sos`, `zplane` |
| **Question 2** | Pole-zero cancellation at $z = 1$, impulse response $h[n]$, and frequency response $H(e^{j\omega})$ | `conv`, `pzmap`, `filter`, `freqz` |
| **Question 3** | Symbolic unilateral Z-transforms for $u[n]$, $2^n u[n]$, and $n u[n]$ | `syms`, `ztrans` |
| **Question 4** | Partial fraction expansion in negative powers of $z$ ($z^{-1}$) | `residuez` |
| **Question 5** | 4th-order IIR step response ($x[n] = 5u[n]$): relaxed vs. non-zero initial conditions | `roots`, `filtic`, `filter` |
| **Question 6** | Difference equations, unit-delay comparison, first-difference high-pass filter, and 5-point moving average low-pass filter | `filter`, `stem` |

## How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/dsp-lab-2.git
   cd dsp-lab-2
