Dataset Name: RadioML 2018.01A
Modality: RF Waveform (I/Q Signals)
Source: [https://www.deepsig.io/datasets](https://www.deepsig.io/datasets)
License: Modified MIT-style license (research and academic use only)
Size: ~2.4 GB (compressed)

Description:
RadioML 2018.01A is a synthetic RF waveform dataset designed to help train and evaluate radio signal classifiers. It contains over 2 million examples of I/Q samples representing 11 different modulation types across a range of Signal-to-Noise Ratios (SNRs).

File Format:
- `.npy` (NumPy array) format containing I/Q waveform data.
- Each sample is 128 complex values (256 floats), labeled by modulation type and SNR.

Modulation Types:
- BPSK, QPSK, 8PSK, QAM16, QAM64
- AM-DSB, AM-SSB, FM, GFSK, CPFSK, PAM4

SNR Range:
- From -20 dB to +18 dB in 2 dB increments.

Use Case for Defense:
- Enables training of machine learning models to classify or detect RF communications in noisy or contested environments.
- Relevant for signal intelligence (SIGINT), electronic warfare (EW), or spectrum monitoring.

How to Download:
1. Visit: [https://www.deepsig.io/datasets](https://www.deepsig.io/datasets)
2. Scroll to "RadioML 2018.01A"
3. Click to request access and download (sign-up may be required).
4. Unzip the `.tar.gz` file after download.
5. Use `numpy.load()` in Python to load `.npy` files for processing.

Additional Notes:
- You may need to filter the dataset by SNR range or modulation type depending on your model.
- Consider normalizing or reshaping input data before training.
