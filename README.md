# Vass.AI
Code available in Untitled3.ipynb

Audio-Classification model. Primary hurdle was preprocessing the audio signals to make them suitable for convolutional neural networks. Converted to mel spectograms which maps the signals from the amplitude-frequency domain to the frequency-time domain on a well popular audio processing scale called the mel scale. The model consists of convolutional layers followed by a few linear layers.
Libraries used : 1)Pytorch
                 2)TorchAudio
