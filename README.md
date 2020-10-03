# LSTM

--------
## About me
--------
 - graduate IT student interested in :
    - deep learning
    - real time applications 
    - path tracing

--------
## Prerequisites
--------

- Python >= v3.8

--------------------------
## Purpose of this project
--------------------------
Implementing a basic LSTM net for genereting char sequences
 
--------------------
## Algorithmic Analysis
--------------------
- Backpropagation

--------------------
## Running the program
--------------------
Run "python lstm.py train" or "python lstm_cupy.py train" for training

Run "python lstm.py gradcheck" or "python lstm_cupy.py gradcheck" for checking the gradients

Run "python lstm.py sample" or "python lstm_cupy.py sample" for generating sample

Under folder "data/" one can place any kind of .txt file one want to train the net with.
Just make sure it is a .txt!

--------------------
## Built With
--------------------

* [Python](https://www.python.org/)
* [CuPy](https://cupy.dev/)
* [Cuda](https://developer.nvidia.com/cuda-zone)

--------------------
## Results
--------------------


--------------------
## Authors
--------------------

* **Jonas Heinle** - [Kataglyphis](https://github.com/Kataglyphis)

--------------------
## Acknowledgments
--------------------

This work was inspired by previous work on blue noise. Especially to mention:
* [karpathy](https://github.com/karpathy/char-rnn)
