# Scene Understanding for Autonomous Vehicles
Master in Computer Vision - M5 Visual recognition

## Group 06
Name: Group 06 (Tricky Team)  
Juan Felipe Montesinos(jfmontgar@gmail.com)  
Ferran Carrasquer(ferrancarrasquer@gmail.com)  
Yi Xiao(yi.xiao@e-campus.uab.cat)  

## Abstract   
In this 5-week project it will be developed as a Deep Learning based system to recognise objects, obtain their bounding box and segmentation related to the field of ADAS for designing and implementig deep neural networks for scene understanding for autonomous vehicles.


## Report & Slides
1. A detailed report about the work done can be found [here](https://www.overleaf.com/14201045nbngtjzxgtrc#/54851966/)
2. A Google Slides presentation can be found [here](https://docs.google.com/presentation/d/1o2RH6WHfbfyuQad9ZDE3kQ5-N749o_uBFhq0lSWSTsE/edit?usp=sharing)


## Week 1: summary of two papers about VGG and SqueezeNet
1. paper reading: check the file named Paper_Summary
   
   
## Week 2: Object Recognition
### wights  
the weights of the model can be checked [here](https://drive.google.com/drive/folders/1xRXmhrm1Ng86Y3ANa_N83xyltfwZU_IP?usp=sharing)  

### Code and usage  
All the experiment configuration files are put into code/config foder. There is a file inside code folder named train.py  to run the code.  
You need to fix the paths for datasets in train.py for working on your machine, and then write the commond:
```
python train.py -c config/dataset.py -e expName
```
where dataset.py is the configuration file for this test, and expName is the name of the directory where the results to be saved.

### Completeness of tasks
Below is the check list of our completeness of task. All the results of the tasks are shown in the [report](https://www.overleaf.com/read/bcqybcqytyvj)  
- [x] (a) Run the provided code  
          - Analysis the dataset  
          - Accuracy of train and test set  
          - Evaluate different techniques in the configuration file such as: crop vs. resize; division std normalization; ImageNet normalization
          - Transfer learning to Belgium traffic signs dataset 
          - Understand the code  
- [x] (b) Train the VGG16 network on a different dataset(KITTI)  
          - Trained from scratch 
- [x] (c) Implete a new network     
          - (c.1) we impleted ResNet network on TT100K and KITTI datasets 
- [x] (d) Boost the performance of the network  
          - Changing learning rate and data augmentation
- [x] (e) Report


## Week 3: Object Detection
### wights  
the weights of the model can be checked [here](https://drive.google.com/drive/folders/1Aw_FuOW_3VCYB5EoUSkCgMnOJGOtmCvN)  

### Code and usage  
All the experiment configuration files are put into code/config foder. There is a file inside code folder named train.py  to run the code.  
You need to fix the paths for datasets in train.py for working on your machine, and then write the commond:
```
python train.py -c config/dataset.py -e expName
```
where dataset.py is the configuration file for this test, and expName is the name of the directory where the results to be saved.

### Completeness of tasks
Below is the check list of our completeness of task. All the results of the tasks are shown in the [report](https://www.overleaf.com/read/bcqybcqytyvj)  
- [x] (a) Run the provided code  
          - Analysis the dataset  
          - Calculate the f-score and FPS on train, val and test sets.
- [x] (b) Read two papers   
          - You Only Look at Once (YOLO)
          - T.B.D
- [x] (c) Implement a new network     
          - T.B.D
- [x] (d) Train the networks on a different dataset  
          - T.B.D
- [x] (e) Boost the performance of our network
          - T.B.D
- [x] (f) Repot

