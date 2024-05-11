# LFP Data Analysis Project

## Introduction
Welcome to the LFP Data Analysis project! This project involves analyzing Local Field Potential (LFP) data collected from an experiment with a rat. The data consists of 120 trials recorded from 3 different brain regions. Each trial contains 6000 samples, with a sample rate of 2000 Hz, resulting in 3 seconds of data per trial. The data includes both the recorded neural activity (channelData) and information about trial timing (digitalByte).

## Overview
This project includes the following steps:

1. **Data Loading and Exploration**:
   - Load the LFP data file.
   - Print the size of the digitalByte vector and channelData matrix.
   - Plot the digitalByte vector to visualize trial timing.

2. **Preprocessing Techniques**:
   - Apply preprocessing techniques such as filtering, artifact removal, and baseline correction to the LFP data.

3. **Power Spectral Density (PSD) Analysis**:
   - Compute the PSD of Event-Related Potentials (ERPs) for each brain region.
   - Compare the PSD results to Event-Related Spectral Perturbations (ERSPs) to understand frequency dynamics.
   
4. **Weighted Phase Lag Index (WPLI) Calculation**:
   - Calculate the WPLI to analyze the phase synchronization between different brain regions.

## Usage
To use this project:

1. **Data Preparation**:
   - Ensure the LFP data file (LFP_data.mat) is available in the project directory.

2. **Running the Code**:
   - Run the Python scripts corresponding to each step in the analysis process.

## Dependencies
This project requires Python 3.x and the following libraries:
- numpy
- scipy
- matplotlib
- mne (for EEG/MEG data analysis)
- mayavi (for 3D plotting)

You can install these dependencies using pip:
```
pip install numpy scipy matplotlib mne mayavi
```

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request.


## Contact
For any questions or feedback, feel free to reach out to [adel.mov1382@gmail.com].
