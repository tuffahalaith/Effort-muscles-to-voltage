# Effort-muscles-to-voltage
The notebook is focussing on generating, processing, and modeling electromyography (EMG) signals, for machine learning purposes.

starts with importing essential libraries, including numpy for numerical operations, matplotlib for plotting, scipy for signal processing, and tensorflow for building neural network models.
The function generate_emg_signal() creates synthetic EMG signals with specified frequencies, amplitudes, and noise levels over a set duration. It helps simulate realistic EMG signals for analysis and modeling.

The preprocess_emg_signal() function filters the generated EMG signal to isolate relevant frequency ranges using a bandpass filter (with a specified low and high cutoff). It is essential to remove noise and focus on the signal components most relevant to EMG data.

![image](https://github.com/user-attachments/assets/142d407a-1e8e-4dd6-8c98-9e20439a1d19)

![image](https://github.com/user-attachments/assets/cd864efc-9ef6-4ee0-ba21-4d9324e70d28)

