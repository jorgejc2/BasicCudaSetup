### CUDA Basic Setup


## Introduction

This github is just to ensure that CUDA is properly installed. If this program can compile and run, then CUDA is setup up. This does not necessarily mean thatit is set up for Torch or Tensor. For more information, follow the [link](https://docs.nvidia.com/deeplearning/tensorrt/install-guide/index.html).

## Compiling

To compile and run, use the following commands:

```sh
nvcc vector_add.cu -o vector_add
./vector_add
```

## Testing GPU with Python

To test if the GPU is working correctly with Torch and Tensor, run the following commands:

```sh
python3
>>> import torch
>>> torch.cuda.is_available()
```

Should it fail, use the link above and follow the instructions to set up Tensor. From my experiences, though the instructions are for setting up Tensor, it also sets up Torch. 
