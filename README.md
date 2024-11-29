# Audio_Frequency_Analysis
This repository contains Python scripts for analyzing and processing audio signals. The scripts leverage libraries such as SciPy, NumPy, Matplotlib, and a custom-built library GFFT for FFT calculations and frequency organization. Key functionalities include:

Fourier Transform Analysis:

Perform Fourier Transform (FFT) on audio signals to extract magnitude and phase information.
Convert spectral magnitudes to dB scale, ensuring results are normalized and intuitive for analysis.
Rearrange frequency components for better visualization of positive and negative frequencies.
Signal Resampling:

Downsample audio signals while preserving essential frequency components.
Analyze and compare original and resampled signals in both time and frequency domains.
Visualization:

Plot waveforms, spectra, and resampled signals with detailed annotations.
Generate professional-quality visualizations saved as PNG images for reporting or further analysis.
File Handling:

Read audio files in WAV format.
Save processed audio and visualization outputs in specified directories.
The scripts include various plots:

Time-domain waveforms of original and resampled signals.
Frequency-domain spectra in linear and dB scales.
Comparisons between original and resampled spectra.
This project is ideal for educational purposes, audio signal analysis, and processing applications. Ensure to have GFFT properly installed, as it is a critical dependency for FFT calculations.

Dependencies:

SciPy, NumPy, Matplotlib
Custom library: GFFT
Outputs:

Processed audio files
Visualization images
Feel free to use and adapt these scripts for your projects. Contributions are welcome!
