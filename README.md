# LLCNN
This is the training code for [LLCNN: A convolutional neural network for low-light image enhancement](https://ieeexplore.ieee.org/abstract/document/8305143).   
The code can be used in caffe, which supports SSIM loss. 

## Network Architecture 
Inspired by residual learning, we design a special convolutional module to process images.
![image](./img/module.PNG)
![image](./img/network.PNG)

## Citing LLCNN
If you find LLCNN useful in your research, please consider citing:
```
@INPROCEEDINGS{8305143, 
    author={L. Tao and C. Zhu and G. Xiang and Y. Li and H. Jia and X. Xie}, 
	booktitle={2017 IEEE Visual Communications and Image Processing (VCIP)}, 
	title={LLCNN: A convolutional neural network for low-light image enhancement}, 
	year={2017}
```