# SHM-Edge-Impulse

This study aims to explore structural health monitoring (SHM) systems by leveraging signal processing techniques with low-cost hardware. The primary objective is to develop a cost-effective solution that integrates with a mobile app, providing real-time feedback on structural integrity for residential, commercial, or industrial infrastructure to facilitate proactive maintenance practices and improve infrastructure safety.

Our design uses a microcontroller equipped with analog-to-digital converters, dual processors, and Wi-Fi support, enabling real-time data acquisition and preprocessing through a dedicated real-time operating system. Leveraging the Arduino platform and wireless communication protocols, the hardware allows future scalability by maintaining modularity.

This SHM system incorporates signal processing techniques focusing on the extraction of Fourier coefficients, power spectral density, short-time Fourier transform, wavelet transform, and spectrogram values to distinguish stable and active signals. The study uses simulated environmental disruptions for the purposes of acquiring data and determining the existence of structural abnormalities.

Areas of further research include incorporating a machine learning model to be trained iteratively with experimental data. The iterative nature of data collection ensures continual refinement of the machine learning model during development through the incorporation of additional experimental data and exploring new methodologies. This systematic approach ensures the improvement of the system and continued adaptability.

Please refer to the design document for process and methodology.
