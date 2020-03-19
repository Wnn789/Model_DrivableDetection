完整代码链接：
链接：https://pan.baidu.com/s/1UAyXrMrfC9JP8kGrEZYIOQ 
提取码：r7b3 



运行步骤：
#1 All datasets will be placed in datasets folder
#2 Model weights files generated during training will be in logs folder
#3 Model implementation files are placed in mrcnn folder
#4 Go to samples/bdd, run below cmd to train the model with coco weights pre-trained
Python3 bdd_train.py train --dataset=../../datasets/bdd --weights=coco

#5 go to samples/bdd, run below cmd to detect the drivable area, and please make sure there is one image at least in datasets/bdd/test folder before running the cmd
Python3 bdd_prediction.py



需要用到的Python库：
numpy
scipy
Pillow
cython
matplotlib
scikit-image
tensorflow>=1.3.0
keras>=2.0.8
opencv-python
h5py
imgaug
IPython[all]