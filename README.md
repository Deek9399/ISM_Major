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

1. Spectral centroid
The spectral centroid indicates at which frequency the energy of a spectrum is centered upon or in other words It indicates where the ” center of mass” for a sound is located. This is like a weighted mean:
![NN](https://miro.medium.com/max/355/1*DkT47WzLrjigT_KVhDoMuQ.png)
2. Spectral Rolloff
3. Spectral Bandwidth
4. Zero-Crossing Rate
5. Mel-Frequency Cepstral Coefficients(MFCCs)
6. Chroma feature

Please consider reading these articles to understand Audio data analysis and its step by step implementation [here](https://www.theaidream.com/post/audio-data-analysis-using-deep-learning-with-python-part-1) and [here](https://www.theaidream.com/post/audio-data-analysis-using-deep-learning-with-python-part-2).

