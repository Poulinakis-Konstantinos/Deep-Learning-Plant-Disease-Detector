# Leaf-Disease-ML-detector-
 
   Deep Neural Network Models , based on transfer learning , able to detect diseases on plant's leaf images . The models are trained to classify 38 different classes plant/disease. Models have been converted to Tensorflow Lite equivalent and have been quantized to optimize performance for portable devices (microcomputers,microcontrollers,etc..) .
   
  Models' inference are deployed on a RaspBerry Pi 4B (2gb Ram) equipped with a camera to create 
  a portable disease detection device .   



   I have trained my DL models on Google Colab platform . I design my Networks relying on Transfer Learning using Keras and Tensorflow frameworks. 
  Language of choice is Python.  I am expirementing with two pretrained models, MobileNetV2 and Densenet169.



   My edge inference device is a Raspberry 4B, running on Raspberry Pi OS (Linux distro). I have remotely connected  to the Pi ( check out this [guide](https://github.com/Poulinakis-Konstantinos/Headless-RaspBerry-Pi-4b)
  and written Python scripts for taking snapshots through the camera , loading image on my model , running inference and printing out Prediction/Confidence Level/Elapsed Time.
 
 
   Dataset used : I used this kaggle dataset https://www.kaggle.com/vipoooool/new-plant-diseases-dataset .
   
