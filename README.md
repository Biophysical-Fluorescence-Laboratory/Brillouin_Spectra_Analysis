# Brillouin Spectroscopy Analysis

Polynomial frequency calibration and Lorentzian peak fitting 
for VIPA-based Brillouin spectral data.

## Requirements
Python 3.11, numpy, scipy, matplotlib, pandas

## Usage
1. Place CSV files (columns: pixel index, intensity) in the same directory
2. Set parameters in the User Parameters cell of brillouin_analysis.ipynb
3. Run all cells

## Output
- Brillouin shift (GHz) ± uncertainty
- Linewidth (FWHM, GHz)
- Fit R² and SNR
- brillouin_results_final.csv
