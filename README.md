# Scene Understanding for Autonomous Vehicles
Master in Computer Vision - M5 Visual recognition

Juan Felipe Montesinos(jfmontgar@gmail.com)  
Ferran Carrasquer(ferrancarrasquer@gmail.com)  
Yi Xiao(yi.xiao@e-campus.uab.cat)  

## Abstract   
In this 5-week project it will be developed as a Deep Learning based system to recognise objects, obtain their bounding box and segmentation related to the field of ADAS for designing and implementig deep neural networks for scene understanding for autonomous vehicles.



### wights  
the weights of the model can be checked [here](https://drive.google.com/drive/folders/1xRXmhrm1Ng86Y3ANa_N83xyltfwZU_IP?usp=sharing)  

### Code and usage  
All the experiment configuration files are put into code/config foder. There is a file inside code folder named train.py  to run the code.  
You need to fix the paths for datasets in train.py for working on your machine, and then write the commond:
```
python train.py -c config/dataset.py -e expName
```
where dataset.py is the configuration file for this test, and expName is the name of the directory where the results to be saved.


##  Object Detection
### wights  
the weights of the model can be checked [here](https://drive.google.com/drive/folders/1Aw_FuOW_3VCYB5EoUSkCgMnOJGOtmCvN)  

### Code and usage  
All the experiment configuration files are put into code/config foder. There is a file inside code folder named train.py  to run the code.  
You need to fix the paths for datasets in train.py for working on your machine, and then write the commond:
```
python train.py -c config/dataset.py -e expName
```
where dataset.py is the configuration file for this test, and expName is the name of the directory where the results to be saved.


