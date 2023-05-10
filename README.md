# nvidia driver
### find the correct driver version
```
nvidia-detector
```

### install the driver from output of nvidia-detector command
```
sudo apt install nvidia-driver-xxx
```

### check if installation is done correctly
```
nvidia-smi
```
this should output the specs of the gpu. If no devices found -> wrong driver

# cuda
### find the correct cuda version
1. https://en.wikipedia.org/wiki/CUDA
2. Find compute capability based on GPU model
3. Find Cuda version based on compute capability
### find compute capability using command line 
```
nvidia-smi --query-gpu=compute_cap --format=csv
```

# cuDNN
### install guide
https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html

### verify installation using code in link
https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html#verify


