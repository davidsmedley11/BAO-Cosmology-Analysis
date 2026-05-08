# Baryon Acoustic Oscillations (BAO) Technical Analysis
### Dark Energy Survey (DES) Data Pipeline & Statistical Modeling

## Project Overview
This project involves the development of a robust data pipeline to isolate the BAO signal—a "standard ruler" for measuring the expansion history of the universe. By processing raw galaxy survey data, I implemented N-point correlation functions to identify the sound horizon scale across various redshift slices.

## Key Technical Methodologies
*   **Data Engineering:** Utilized `Astropy` for FITS/Table handling and `Healpy` for HEALPix spherical surface mapping.
*   **Signal Isolation:** Implemented `TreeCorr` for N-point correlation functions $\omega(\theta)$ using Landy-Szalay estimators and random catalog generation.
*   **Statistical Modeling:** Performed non-linear least-squares fitting using the `iminuit` optimizer.
*   **Error Analysis:** Calculated uncertainty estimations via Hesse covariance matrices to validate the angular scale of the sound horizon.

## Tools & Libraries
`Python` | `NumPy` | `SciPy` | `Matplotlib` | `Astropy` | `Healpy` | `TreeCorr` | `iminuit`

## Results
The analysis successfully identified an experimental BAO peak, allowing for the critical evaluation of theoretical cosmological predictions against real-world Dark Energy Survey datasets.
