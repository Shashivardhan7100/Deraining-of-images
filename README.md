# DGNL-Net

# Single-Image Rain Removal Based on Depth-Guided Non-Local Features

***

Please find the code of the conference version at [https://github.com/xw-hu/DAF-Net](https://github.com/xw-hu/DAF-Net).      

***

# RainCityscapes Dataset

Our RainCityscapes dataset is available for download at the [Cityscapes website](https://www.cityscapes-dataset.com/downloads/).

## Citations

@article{hu2021single,                    
&nbsp;&nbsp;&nbsp;&nbsp;   title={Single-Image Real-Time Rain Removal Based on Depth-Guided Non-Local Features},                
&nbsp;&nbsp;&nbsp;&nbsp;   author={Hu, Xiaowei and Zhu, Lei and Wang, Tianyu and Fu, Chi-Wing and Heng, Pheng-Ann},               
&nbsp;&nbsp;&nbsp;&nbsp;   journal={IEEE Transactions on Image Processing},              
&nbsp;&nbsp;&nbsp;&nbsp;   volume={30},                
&nbsp;&nbsp;&nbsp;&nbsp;   pages={1759--1770},            
&nbsp;&nbsp;&nbsp;&nbsp;   year={2021},              
&nbsp;&nbsp;&nbsp;&nbsp;   publisher={IEEE}              
}

@InProceedings{Hu_2019_CVPR,      
&nbsp;&nbsp;&nbsp;&nbsp;  author = {Hu, Xiaowei and Fu, Chi-Wing and Zhu, Lei and Heng, Pheng-Ann},      
&nbsp;&nbsp;&nbsp;&nbsp;  title = {Depth-Attentional Features for Single-Image Rain Removal},      
&nbsp;&nbsp;&nbsp;&nbsp;  booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},      
&nbsp;&nbsp;&nbsp;&nbsp;  pages={8022--8031},      
&nbsp;&nbsp;&nbsp;&nbsp;  year = {2019}      
}

## Prerequisites
* Python 3.5
* PyTorch 1.0
        
## Installation

Clone this repository:          
   ```shell
   git clone https://github.com/xw-hu/DGNL-Net.git
   ```

## Test   
1. Test the DGNL-Net :
   ```shell
   python3 infer.py    
   ```

## Train

2. Train the DGNL-Net model:
   ```shell
   python3 train.py    
   ```


## Evaluation

Please find the evaluation code at [https://github.com/xw-hu/DAF-Net](https://github.com/xw-hu/DAF-Net).                                 

