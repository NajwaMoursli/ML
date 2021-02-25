# Machine Learning Project

# Collaborators : Najwa MOURSLI Laurent DANG-VU

# Project

We studied the dataset UC2017 Static and Dynamic Hand Gestures: (https://zenodo.org/record/1319659#.X3OVgNgitQJ)

Il s’agit d’un jeu de données de reconnaissances de gestes à partir de mesures prises
par un gant de réalité virtuelle.
Composed of two dataset :

- **SG - 24 Static Gesture**
- **DG - 10 Dynamic Gesture** 

Complete Description of the baselines in this article :(https://www.researchgate.net/publication/330429917_Online_Recognition_of_Incomplete_Gesture_Data_to_Interface_Collaborative_Robots)


For reasons of simplicity, we will initially limit ourselves to the Static Gesture subdataset. 
***A multi-class classification task** will be carried out with the aim of identifying the gesture made by the user.
There are several users, which poses a problem of the variability of actions from one user to another.
This dataset was developed as part of the thesis Segmentation and recognition of gestures for
human-robot cognitive interaction by **Miguel Simao http://www.theses.fr/2018ENAM0048 and the code
https://github.com/MiguelSimao/UC2017_Classification**


<img src="https://user-images.githubusercontent.com/49198711/109167223-d1d5d000-777d-11eb-8480-5dfe3c5aa36a.png" width="60%"></img> 

# Softwares, Library and Langage use
- Google Collaboratory: (https://colab.research.google.com/notebooks/intro.ipynb)
- Python : (https://www.python.org/)

1. **For Machine and Deep Learning Tools**
- Tensorflow : (https://www.tensorflow.org/?hl=fr)
- Keras : (https://keras.io/)
- Sckit-learn : (https://scikit-learn.org/stable/)

2. **Process and Visualiation of dataset**
- Pandas : https://pandas.pydata.org/
- Matplotlib : https://matplotlib.org/stable/index.html

# Models used for Croos Validation
- Perceptron Multi-layers
- Decision Tree
- Random Forest
- SVM
- KNN
- Our own RNN with 3 hidden layers

# Data Analysis

**PCA interclasses **
<img src="https://user-images.githubusercontent.com/49198711/109169037-b4096a80-777f-11eb-8d3a-e93ed0260f4e.png" width="90%"></img>

**PCA gestures**
<img src="https://user-images.githubusercontent.com/49198711/109169036-b370d400-777f-11eb-987b-d7f0938ec0a6.png" width="90%"></img> 

# ML Results
**RNN with 3 Hiden layers performanes**
 <img src="https://user-images.githubusercontent.com/49198711/109169062-b8ce1e80-777f-11eb-9e10-2adfd7167cfc.png" width="90%"></img> 
 
 **Perceptron performances**
 <img src="https://user-images.githubusercontent.com/49198711/109169065-b966b500-777f-11eb-8b6b-2d821942e0c4.png" width="90%"></img> 
