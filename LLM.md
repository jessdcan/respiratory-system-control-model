# ELEN3014 Project 2024 – Human Lung Respiratory Mechanics

## Overview
The project models the relationship between lung volume and pressure using the **Inductor-Resistor-Capacitor (IRC) respiratory mechanics model**. It focuses on applying modelling, signal analysis, and control theory to human physiological systems. Work must be done **individually**.

## Tasks
1. Derive the transfer function relating lung compliance (volume) to air pressure. Identify suitable values for I (inertance), R (resistance), and C (compliance).
2. Create two 15-second input signals:  
   - Normal breathing  
   - Breathing during exercise
3. Generate output time-series signals for both cases.
4. Analyse the frequency spectra of input and output signals (normal vs. exercise).
5. Compare results to typical physiological behaviour.
6. Extend the model to simulate **Asthma** effects by adjusting parameters → new model P2(s).
7. Implement a **feedback control system** (negative feedback with gains K and F) to correct P2(s) toward normal breathing.
8. Derive closed-loop transfer function T(s).
9. Tune controllers K and F, generate corrected outputs, and compare P(s), P2(s), and T(s).
10. Plot and analyse Bode plots of P(s), P2(s), and T(s).

## Assessment Criteria
- System and signal modelling (block diagrams, equations, circuits).
- Application of mathematical tools (DEs, Laplace/Fourier, DSP).
- Analysis of parameter changes on system behaviour.
- Evaluation of feedback control impact.
- Report quality and formatting.

## Report Requirements
- Max 5 pages (A4), no appendices.  
- Typed, single-column, font size 12, 1.5 spacing, ≥2 cm margins.  
- Matlab code submitted separately as zipped file.  
- ≤20% web-based references (journals/conference papers excluded).  
- Due: **29 September 2025, 12h00 (via Ulwazi)**.  

### Report Structure
1. **Introduction** – background, problem, solution, purpose, guide.  
2. **Modelling** – P(s), input signals, P2(s), T(s), link to reality.  
3. **Time-series Analysis** – outputs of P(s), P2(s), T(s), comparisons.  
4. **Frequency Analysis** – FFTs, spectra, Bode plots.  
5. **Critical Analysis** – asthma effects, feedback control pros/cons, real-world implementation.  
6. **Summary & Conclusion**.  

### Title Page
- Title (must mention Part 1)  
- Course code  
- Student name & number  
- Date of submission  
- Abstract  
