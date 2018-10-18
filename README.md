# LLCNN
This is the training code for [LLCNN: A convolutional neural network for low-light image enhancement](https://ieeexplore.ieee.org/abstract/document/8305143).   
The code can be used in caffe, which supports SSIM loss. 

## Network Architecture 
We use one convolutional layer to do pre-processing and another convolutional layer to fuse feature maps and generate the output image. Several special-designed convolutional modules are placed between these two convolutional layers.
![image](./img/network.PNG)   
The several special-designed convolutional module is inspired by residual learning. The architecture is shown as follows.   
![image](./img/module.PNG)   

## Citing LLCNN
If you find LLCNN useful in your research, please consider citing:
```
@INPROCEEDINGS{8305143, 
    author={L. Tao and C. Zhu and G. Xiang and Y. Li and H. Jia and X. Xie}, 
	booktitle={2017 IEEE Visual Communications and Image Processing (VCIP)}, 
	title={LLCNN: A convolutional neural network for low-light image enhancement}, 
	year={2017}
```