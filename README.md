
# Project Submission

## Environment Information
This project was developed and executed in Google Colab, where most necessary libraries are pre-installed. Therefore, no additional installations are required to run the notebooks.

## Libraries Used
The following libraries were used for solving each problem, all of which are pre-installed in Colab:

### Problem 3: Spatial Variation
**Objective**: Compute how PUF responses vary with location on FPGA 1 and visualize the spatial distribution of frequencies using a heat map.
- `pandas`: For reading and manipulating the data from `fpga1.csv`.
- `numpy`: For numerical operations such as averaging frequency measurements.
- `seaborn`: For creating a 2D heat map of the spatial distribution of frequencies over the FPGA.
- `matplotlib.pyplot`: For additional plotting and visualization.

### Problem 4: Uniqueness
**Objective**: Compute uniqueness for a PUF constructed from ROs across all 193 FPGAs and calculate Hamming distances between PUF responses.
- `pandas`: For reading data from multiple CSV files within `fullFreqData.zip` and for data manipulation.
- `numpy`: For numerical operations such as averaging frequency measurements and computing PUF responses.
- `zipfile`: To read and extract files from `fullFreqData.zip`.
- `itertools.combinations`: To generate combinations of PUF responses for uniqueness calculation.

### Problem 5: Reliability
**Objective**: Compute reliability for PUFs constructed from ROs on one FPGA, based on 100 frequency measurements.
- `pandas`: For reading and manipulating data from `fpga1.csv`.

### Problem 6: Uniformity
**Objective**: Compute uniformity for PUFs constructed from ROs across all 193 FPGAs and compare uniformity based on row and column pairings.
- `pandas`: For reading data from multiple CSV files and for data manipulation.
- `numpy`: For numerical operations such as averaging frequency measurements and computing PUF responses.
- `zipfile`: To read and extract files from `fullFreqData.zip`.

## Instructions for Running
1. Open the `.ipynb` files in Google Colab or any Jupyter notebook environment.
2. Ensure all cells are executed in sequence to reproduce the results and analysis.
