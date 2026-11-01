# SolenoidLab – AI-Based Magnetic Field Visualization & Solenoid Analyzer

EME project (Unit 2 – Q3) by Diksha Sukhadeve, Roll no: 67, TY ENTC B.

🔗 **Live demo:** [https://<username>.github.io/solenoid-magnetic-field-analyzer/](https://github.com/diksha-84/solenoid-magnetic-field-analyzer)
https://solenoid3dmodel.netlify.app/ 

## What it does
- Simulates a finite-length solenoid using the Biot–Savart law
- Inputs: current, number of turns, coil length, coil radius, core material, current direction
- 3D interactive model (rotate/zoom) with current flow and magnetic field flow
- 2D cross-section view with field lines and a hover probe
- Graphs: field along the axis, radial profile
- Comparison table: centre vs end vs ideal solenoid
- Ampère's law verification and live formulas

## Formulas used
- Ideal solenoid: B = μ₀ n I, where n = N/L
- Centre: B = μ₀ N I / √(L² + 4R²)
- End: B = ½ μ₀ n I · L / √(L² + R²)

## How to run
Open `index.html` in any browser (no installation needed).

## Tech
HTML, CSS, JavaScript (Canvas). Built with AI assistance (Claude).
