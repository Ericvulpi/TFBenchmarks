# TFBenchmarks
Tensorflow use cases of varying complexity to benchmark hardware, hyperparameters and optimizers

## Targets
Provide callable or executable scripts of standard functions and neural nets example with the following caracteristics
#### Parameters (all with default value provided)
- Hardware : CPU / GPU
- Convergence criteria : max iterations / max time / target precision, with a failsafe
- Hyperparameters : batch size, dropout, 


#####exemple of code :
Machine: `6-core Intel Core i7-5930K CPU @ 3.50GHz` + `NVIDIA Titan X` + `Ubuntu 14.04 x86_64`

#####exemple of gras :
**Caffe (native)**

#####exemple of link :
**[AlexNet (One Weird Trick paper)](https://code.google.com/p/cuda-convnet2/source/browse/layers/layers-imagenet-1gpu.cfg)** - Input 128x3x224x224

#####exemple of table :
| Library         | Class                                                                                                                | Time (ms)  | forward (ms) | backward (ms) |
| --:| --:| --:| --:| --:|
| 1  | 2  | 3 | 4 | 5 |
