# hello-world-in-tensorflow-binary-to-decimal
hands-on tensorflow hello world program with python

obviously this is not RNN,
aimed for this repo was not an impliment the Recurunt nuaral network instad this script is about hello word program of tensorflow, so we will prepare data set of binary and corasponding decimal value therefore its become supervise learning. then we train dataset using tensorflow library and save model after training, further we pulled up saved model and test it using binary data.


## Installation

 -> NumPy -3.13.1
  '''
  sudo pip3 install numpy
  '''
 -> tensorflow -1.2.1
  for installing tensorflow :-https://www.tensorflow.org/install/

## Usage
clone repo:- git clone https://github.com/parthvadhadiya/hello-world-in-tensorflow-binary-to-decimal/
run :- python3 training_RNN.py 
  it will generate dataset using create_dataset.py and train RNN with that dataset.
run :- python3 usemodel.py for getting predicated decimal value of givan binary
