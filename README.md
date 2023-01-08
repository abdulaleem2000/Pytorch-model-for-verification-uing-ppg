# Pytorch-model-for-verification-uing-ppg
In this project we trained Pytorch resnet model using our data set for biometric verification using ppg signals. 
At 1st we create csv file containing name of video and their subfolders. Then we created custom dataset using of our videos and provide the dataset to model for training and calculate acuracy of model. Open this file on google colab and run each cell one by one.
# Flask Appliation
Then we create flask app containing resnet model and integrate it with our flutter application. To run flask application you need to create account of ngrok. After creating account use you authtoken and paste it in your code as following

!ngrok authtoken 'write your authtoken here'
