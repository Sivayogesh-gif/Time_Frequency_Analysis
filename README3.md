Frequency and Time Analysis – Communication Systems Lab
📌 Project Overview
This project focuses on analyzing signals in both time domain and frequency domain using Python. The objective is to understand fundamental signal representations, bandwidth considerations, and the effects of transmission through filtering using convolution. Additionally, we implement basic information source modeling for analog and digital signals.

🎯 Objectives
Study signals in time and frequency representations.

Visualize signals such as sinc pulses, composite cosine signals, and analyze their frequency spectra.

Use convolution to simulate a transmitter filter applied to different input signals.

Implement FFT (Fast Fourier Transform) for frequency analysis.

📂 Tasks Performed
1. Sinc Pulse Analysis
Generated a sinc pulse:

m(t)=2B⋅sinc(2πBt)
Computed its Fourier Transform to obtain|M(f)| 

Simulated the effect of a transmitter filter:
g(t)=2B2.sinc(2piB2t)

and analyzed output for various B1 and B2 using convolution.

2. Composite Cosine Signal
Generated:
m(t) = Summation of k=1 to 5 of (1/k)cos(2pikf0t), where f0 = 110Hz
Passed through transmitter filter 

g(t) and observed frequency response for different .

3. Information Source Modeling
Implemented a modular Python class (InfSourceID) to generate:

Analog waveforms: sine, rectangular, square, sinc.

Digital signals: bitstreams from text input.

Audio signals: from .wav files.

🛠️ Technologies Used
Language: Python

Libraries: NumPy, Matplotlib, SciPy

Tools: Google Colab / Jupyter Notebook

📊 Key Features
Time-domain plots for analog and digital signals.

Frequency-domain plots using FFT.

Simulation of filtering effects using convolution.

Modular class to generate and analyze analog, digital, and real-world signals.

📎 Deliverables
inf_source.py: Class implementation for Information Source.

Plots: Time-domain and frequency-domain for analog, digital, and audio signals.

Report: Analysis of results with observations.

🚀 How to Run
Clone the repository or download the project files.

Install required Python packages:

bash
Copy
Edit
pip install numpy matplotlib scipy
Run the main script or notebook:

bash
Copy
Edit
python inf_source.py
View time-domain and frequency-domain plots.

📢 Learning Outcomes
Understanding of time and frequency domain representation.

Use of FFT for spectrum analysis.

Impact of bandwidth and filtering on signal characteristics.

Design of modular source blocks for analog/digital signal generation.