# Fast Dynamic Time Warping (DTW)
This project provides a ros package for performing a dynamic time warping between two time series.The code has been adapted from https://github.com/melode11/FastDTW-x

![DTW applied two sinusoidal time series.](/images/DTW_python.svg)  
Blue and red wave are basically the same wave with different time stamp. The DTW shows the corresponding points between two waves.

![DTW applied two sinusoidal time series in the presence of noise](/images/DTW_noise_python.svg)  
In the this demo, some noise has been imposed the the blue wave but the DTW algorithm is still able to find the corresponding points between two waves.
