# VAD-Deep
Voice Activity Detection (VAD) system with Deep Learning

## How it works
The system uses a deep neural network (Multi Layer Perceptron) implemented with Pytorch which classify the frames of an audio sample as 'speech' or 'non speech'. The model reach 90% of accuracy with audio samples equally distributed between speech and no-speech.

## Discussion
I did this project for an internship interview. You can ask for the code if you are curious.

It was my first approach to voice activity detection with deep learning and it was really fun.
Here are some things I would do to improve the project after some reflexion and my machine learning classes :

* Computing of the precision, recall and AUC of the model
* Use of the context of the frames to improve classification
* Test more complex neural network models (LSTM)

