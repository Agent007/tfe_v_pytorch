# TensorFlow Eager versus PyTorch
## Quick Benchmark: Linear Regression

With the release candidate of TensorFlow 1.7, TensorFlow Eager (TFE) will soon be ready for widespread use 
(https://github.com/tensorflow/tensorflow/releases).  TFE was likely designed in response to PyTorch's popular and 
user-friendly software development experience.  But, how does TFE's performance compare to PyTorch?  As a quick experiment, 
two Jupyter notebooks included in this repository, based off of a [TFE example](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/contrib/eager/python/examples/notebooks/2_gradients.ipynb),
were run on a desktop machine with the following hardware and software:

* Hardware:
  * NVIDIA Titan X (Pascal)
* Software:
  * Operating System: Ubuntu 16.04.4 LTS (GNU/Linux 4.13.0-37-generic x86_64)
  * NVIDIA driver 390.48
  * CUDA 9.1.85-1
  * cuDNN 7.1.2
  * TensorFlow 1.7.0 **COMPILED FROM SOURCE**
  * PyTorch 0.3.1 **COMPILED FROM SOURCE**
