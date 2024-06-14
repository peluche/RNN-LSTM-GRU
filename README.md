# RNN / LSTM / GRU
Compare the accuracies and saliency maps between different models

## MNIST
| Model         | Accuracy |
|---------------|----------|
| MLP           | 0.961    |
| CNN           | 0.988    |
| RNN by rows   | 0.964    |
| GRU by rows   | 0.982    |
| LSTM by rows  | 0.987    |
| LSTM by tiles | 0.966    |

![mnist-1](imgs/mnist-1.png)
![mnist-2](imgs/mnist-2.png)
![mnist-9](imgs/mnist-9.png)

## Fashion MNIST
| Model         | Accuracy |
|---------------|----------|
| MLP           | 0.883    |
| CNN           | 0.881    |
| RNN by rows   | 0.850    |
| GRU by rows   | 0.881    |
| LSTM by rows  | 0.869    |
| LSTM by tiles | 0.857    |

![fmnist-shirt](imgs/fmnist-shirt.png)
![fmnist-shoe](imgs/fmnist-shoe.png)

## Cute Tiling Visualization
![tiling](imgs/tiling.gif)
