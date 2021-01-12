# Leaf-Disease-ML-detector-
 ** Project is Under Development **
 
   Deep Neural Network Models , based on transfer learning , able to detect diseases on plant's leaf images . 
  The inference of the networks will be deployed on a RaspBerry Pi 4B (2gb Ram) equipped with a camera to create 
  a portable disease detection device .   

   I have trained my DL models on Google Colab platform . I design my Networks relying on Transfer Learning using Keras and Tensorflow frameworks. 
  Language of choice is Python. 

   My inference device is Raspberry 4B running on Raspberry Pi OS (Linux distro). I have remotely connected ( check out my other  repo-guide) to the Pi
  and written Python scripts for taking snapshots through the camera , loading image on my model , running inference and providing
  Decision-Confidence level-Elapsed Time .  
 
 
 
   Dataset used : I primarily used this kaggle dataset https://www.kaggle.com/vipoooool/new-plant-diseases-dataset and subsequently merged it with another 
   dataset for weed vs plant detection .
   
 I have written scripts for :
 
        dataset preparation
        
        model compiling 
        
        model training 
        
        model saving-loading
        
        model automated testing on images I have picked . 
        
 All based on official site manuals.
