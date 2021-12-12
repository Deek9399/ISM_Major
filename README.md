# ISM_Major
# Audio Data Analysis Using Deep Learning

Audio data analysis is about analyzing and understanding audio signals captured by digital devices, with numerous applications in the enterprise, healthcare, productivity, and smart cities.

In this repository we have done audio data analysis and extracted necessary features from a sound/audio file. Also build an Artificial Neural Network(**ANN**) and Convolutional Neural Network(**CNN**) for classifying music genre.

![NN](https://github.com/nageshsinghc4/Audio-Data-Analysis-Using-Deep-Learning/blob/master/images.jpeg)


Pre requisites:

1. **Librosa**: to analyze audio signals in general but geared more towards music. It includes the nuts and bolts to build a MIR(Music information retrieval) system. 

```pip install librosa```


2. **IPython.display.Audio**: Lets you play audio directly in a jupyter notebook.

## Important termanologies:

### Spectrogram
A spectrogram is a visual way of representing the signal strength, or “loudness”, of a signal over time at various frequencies present in a particular waveform.

### Feature extraction from Audio signal
Every audio signal consists of many features. However, we must extract the characteristics that are relevant to the problem we are trying to solve. The process of extracting features to use them for analysis is called feature extraction. Let us study a few of the features in detail.

The spectral features (frequency-based features), which are obtained by converting the time-based signal into the frequency domain using the Fourier Transform, like:

1. Spectral centroid:-
The spectral centroid indicates at which frequency the energy of a spectrum is centered upon or in other words It indicates where the ” center of mass” for a sound is located. This is like a weighted mean:
![NN](https://miro.medium.com/max/355/1*DkT47WzLrjigT_KVhDoMuQ.png)
where S(k) is the spectral magnitude at frequency bin k, f(k) is the frequency at bin k.

2. Spectral Rolloff:-
It is a measure of the shape of the signal. It represents the frequency at which high frequencies decline to 0. To obtain it, we have to calculate the fraction of bins in the power spectrum where 85% of its power is at lower frequencies.

3. Spectral Bandwidth:-
The spectral bandwidth is defined as the width of the band of light at one-half the peak maximum (or full width at half maximum [FWHM]) and is represented by the two vertical red lines and λSB on the wavelength axis.

4. Zero-Crossing Rate:-
A very simple way for measuring the smoothness of a signal is to calculate the number of zero-crossing within a segment of that signal. A voice signal oscillates slowly — for example, a 100 Hz signal will cross zero 100 per second — whereas an unvoiced fricative can have 3000 zero crossings per second.

![NN](https://miro.medium.com/max/887/1*E_XSqizmLNksjknrD8oV2w.png)

5. Mel-Frequency Cepstral Coefficients(MFCCs):-
The Mel frequency cepstral coefficients (MFCCs) of a signal are a small set of features (usually about 10–20) which concisely describe the overall shape of a spectral envelope. It models the characteristics of the human voice.

6. Chroma feature:-
A chroma feature or vector is typically a 12-element feature vector indicating how much energy of each pitch class, {C, C#, D, D#, E, …, B}, is present in the signal. In short, It provides a robust way to describe a similarity measure between music pieces.


Please consider reading these articles to understand Audio data analysis and its step by step implementation [here](https://www.theaidream.com/post/audio-data-analysis-using-deep-learning-with-python-part-1) and [here](https://www.theaidream.com/post/audio-data-analysis-using-deep-learning-with-python-part-2).

