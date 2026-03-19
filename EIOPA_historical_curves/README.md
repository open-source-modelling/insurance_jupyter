# EIOPA Risk-Free Rate Curve Extraction

A Python implementation for extracting and processing historical EIOPA Risk-Free Rate (RFR) curves. The goal of this project is to demonstrate a straightforward method for extracting this data without relying on expensive external data feeds.

## Data Requirements

The implementation relies on two primary CSV files extracted from EIOPA's monthly publications:

 - all_Qb.csv: Contains observed maturities (MObs​) and the calibrated vector (Qb).
 - all_params.csv: Contains the calibration parameters α (convergence speed) and UFR (Ultimate Forward Rate).

## Getting Started

To run the notebook,ensure your directory contains the Jupyter Notebook and the two required .csv files. Then run the provided Jupyter notebook.

Note: For the scripts used to unzip EIOPA submissions and extract calibration vectors from Excel, contact gregor@osmodelling.com.

