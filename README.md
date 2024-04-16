# **Windows Subsystem for Linux (WSL)**

WSL lets linux system to run in windows machine. For this tutorial we will focus on Ubuntu linux distribution.
To learn more about WSL please visit- https://learn.microsoft.com/en-us/windows/wsl/about

First let's start by installing Nvidia Drivers, Cuda toolkit and CUDNN in windows before procedding to WSL Ubuntu.


## Download Visual Studio

https://visualstudio.microsoft.com/downloads/

## Download CUDA toolkit

Download the latest CUDA toolkit that's compatable to your device.

[Download CUDA here](https://developer.nvidia.com/cuda-downloads?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_network)

## Check the CUDA verison

Inorder to verify if the CUDA is properly installed


* Open Command Line Windows(CMD) and type
  
![Data](img/nvidia.png)

To check CUDA

```
nvcc -V
```
![Data](img/nvcc.png)

## Run CUDA Toolkit network installer

Make sure to select custom only CUDA runtime option

![Data](img/nvcc.png)
