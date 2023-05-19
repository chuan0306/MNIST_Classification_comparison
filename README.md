# MNIST_Classification_comparison

MNIST dataset classification with different architecture
  - comparison with 3-layer of CNN network/3-layer NN network
  - comparison w/ and w/o Batch Normalization layer
  - comparison with different depth of CNN network

____________________________________________________________________________________________________________________
|                        |  w/o Batch Normalization layer  | w/ Batch Normalization layer  | 2-layer CNN | 4-layer |
|------------------------|---------------------------------|-------------------------------| ------------|---------|
|   training accuracy    |             0.9963              |            0.9963             |0.9973|0.9959|
|     training loss      |             0.0120              |            0.0118             |0.0078|0.0128|
|   validation accuracy  |             0.9902              |            0.9932             |0.9912|0.0463|
|     validation loss    |             0.0524              |            0.0343             |0.9933|0.0288|
