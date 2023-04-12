# CompViz-Keras
Computer vision tasks with keras and Tensorflow


This repo contains diverse computer vision tasks with Keras and Tensorflow.

##  Tasks
 - ### Image Classification :
   Where the goal is to assign one or more labels to an image.
  It may be either single-label classification (an image can only be in one category, excluding the others), or multi-label classification (tagging all categories
  that an image belongs to).
  
  
 - ### Image Segmentation : 
    Where the goal is to “segment” or “partition” an image into
    different areas, with each area usually representing a category.
    
 - ### Object Detection :
     Where the goal is to draw rectangles (called bounding boxes)
   around objects of interest in an image, and associate each rectangle with a class.
   A self-driving car could use an object-detection model to monitor cars, pedestri-
   ans, and signs in view of its cameras, for instance.

## Notebooks

 - [Transfer Learning on the cats_vs_dogs dataset with VGG16 architechture from keras](https://github.com/Overlrd/CompViz-Keras/blob/main/Image-Classification/Transfer_Learning_cats_vs_dogs_VGG16.ipynb)
 
 
   An exploratory walktrought of Computer Vision with pretrained models on the Ctas vs Dog Dataset
   
 - [Image segmentation on the Oxford Pets Dataset](https://github.com/Overlrd/CompViz-Keras/blob/main/Image-Segmentation/Oxford-Pets-Dataset_image_segmentation.ipynb)
 
 
   An exploratory walktrought of Image Segmentation with complex Convolutional models on the oxford pets dataset 
   
<div style = 'display-items:center; display:felex;  margin:60px ;'>
 <img src='https://github.com/Overlrd/CompViz-Keras/blob/main/Image-Segmentation/cat.png' width = 300px  />
 <img src='https://github.com/Overlrd/CompViz-Keras/blob/main/Image-Segmentation/cat_mask.png' width = 300px  style="float: right;" />
</div>

<sub>Original Image and Segmented result </sub>
   
 - [Image classification on the oxford_flowers102 dataset](https://github.com/Overlrd/CompViz-Keras/blob/main/Image-Classification/Oxford_flowers102-Keras.ipynb)
   
   Image classification on the oxford_flowers102 dataset with mobinetV2 model
   
<div style = 'display-items:center; display:felex;  margin:60px ;'>
 <img src='https://user-images.githubusercontent.com/90383672/231526291-e525e431-b713-4e98-b90b-06f14cf32780.png' />
 <img src='https://user-images.githubusercontent.com/90383672/231527065-09e85fd6-9cd2-4042-aeb9-6468f6ea5022.png' />

</div>


<br/>

References : 
 - [Deep Learning With Python - Robert Chollet](https://fr.coursera.org/learn/introduction-tensorflow)
 - [Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning](https://fr.coursera.org/learn/introduction-tensorflow) - Coursera
