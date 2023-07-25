# Intrusion-Detection-System-Using-CNN-and-Transfer-Learning

## Implementation 
### CNN Models  
* VGG16
* VGG19
* Xception
* Inception
* Resnet
* InceptionResnet

### Ensemble Learning Models
* Bagging
* Probability Averaging
* Concatenation

### Hyperparameter Optimization Methods
* Random Search (RS)
* Bayesian Optimization - Tree Parzen Estimator(BO-TPE)

### Dataset 
1. CAN-intrusion/Car-Hacking dataset, a benchmark network security dataset for intra-vehicle intrusion detection
* Publicly available at: https://ocslab.hksecurity.net/Datasets/CAN-intrusion-dataset  
* Can be processed using the same code

2. CICIDS2017 dataset, a popular network traffic dataset for intrusion detection problems
* Publicly available at: https://www.unb.ca/cic/datasets/ids-2017.html  

For the purpose of displaying the experimental results in Jupyter Notebook, the sampled subset of the CAN-intrusion dataset is used in the sample code. The subsets are in the "[data](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-CNN-and-Transfer-Learning/tree/main/data)" folder.

### Code  
* [1-Data_pre-processing_CAN.ipynb](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-CNN-and-Transfer-Learning/blob/main/1-Data_pre-processing_CAN.ipynb): code for data pre-processing and transformation (tabular data to images).  
* [2-CNN_Model_Development&Hyperparameter Optimization.ipynb](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-CNN-and-Transfer-Learning/blob/main/2-CNN_Model_Development%26Hyperparameter%20Optimization.ipynb): code for the development and CNN models and their hyperparameter optimization.
* [3-Ensemble_Models-CAN.ipynb](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-CNN-and-Transfer-Learning/blob/main/3-Ensemble_Models-CAN.ipynb): code for the construction of three ensemble learning techniques.

Libraries  
* Python 3.5+
* [Keras 2.1.0+](hhttps://keras.io/)  
* [Tensorflow 1.10.0+](https://www.tensorflow.org/install/gpu)
* [OpenCV-python](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)
* [hyperopt](https://github.com/hyperopt/hyperopt) 
