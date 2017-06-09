# Holmes bot (Char RNN)

This project implements a minimal Recurrent Neural Network (LSTM) in Tensorflow. The network trains and samples on a character level, in this case from all the Sherlock Holmes novels.

The checkpoints trained on a GTX 1080 for 100 epochs can be found [here](). The loss in the end was ___

Here is something it generated after training for 100 epochs:
>yo
>yo
>yo

## Requirements

Python 3.6
Tensorflow 1.0 (GPU version recommended for training)
Numpy, Pickle

## Usage

To test the trained network, download [this checkpoints folder]() and keep it in the same folder as the code and run:
```
python test.py
```

To train the network use:
```
python train.py
```

To train it on your own dataset link it in *line 45 of train.py*

*khatam*
