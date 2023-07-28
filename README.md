# Audio-classification-with-transfer-learning

This project was developed to analyze heart sounds and identify the normal versus abnormal hear sounds. The main task of this project was to develop a prediction tool that can classify the heart beat as either normal or abnormal. Inspired from the prior works on heart sound classification, we developed a system that uses a set of features extracted from heart sounds to train a random forest classifier.







#MFCCs-FEATURES

MFCCs are widely used in SVD (singing voice detection) and were first introduced by Davis and Mermelstein in 1980. The use of MFCCs has proven to be a powerful tool in music and voice recognition, and sound recognition in general. (link: https://encyclopedia.pub/entry/18717)

The MFCCs are calculated as follows:
1. Division of the speech signals into frames, usually by applying a windowing function at fixed intervals;
2. Computing the coefficients of the discrete Fourier transform on each segment of windowed signal to convert the time domain into the frequency domain;
3. Taking the logarithm of the amplitude spectrum;
4. Smoothing the spectrum and emphasizing perceptually meaningful frequencies ;
5. Taking the discrete cosine transform (DCT) of the list of mel log powers;
6. Generating cepstrum.
