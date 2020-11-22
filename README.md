#Indoor Navigation

• Trained and deployed an LSTM based Deep Learning convolutional neural network on 1000 videos dataset, to classify doors and stairs in indoors, with less than 0.01% error, using Python, MobileNetv2, TensorFlow, Keras, Tensorboard, CNN, Google Cloud Platform (GCP), sklearn etc.

• Project tutorial link-

http://csweb01.csueastbay.edu/~su5654/CVProject1/

• Group Members: Richa Khagwal, Subhangi Asati, Maithri Chulikana

Google drive link: https://drive.google.com/drive/folders/1pBZbaxnbSvseVVEDrsT8uze0C3-ctWCA?usp=sharing

• Steps involved in actual implementation-

## Step 1: Building and Training model-

#### Tensorboard results-


![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step191.PNG)

![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step192.PNG)

## Step 2: Feature Extraction-

- Sampling the video: We don’t process every frame, we define a frame generator to create certain sequence length as 40 samples and load the dataset & specify output frames.

- Used CNN model Inception v3 for feature extraction.

- Extracting Features using Inception v3-

![alt text](https://github.com/Maithri-CH/Indoor-Navigation/blob/master/images/step24.PNG)

## Step 3: Batch Prediction-

Created Inception v3 Feature Extraction Model, and generated .npy file from video files-

![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step32--.PNG)


![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step34--.PNG)

![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step35--.PNG)

## Step 4: Live Predictions-


![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step48.PNG)

![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step49.PNG)

![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step50.PNG)

![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step51.PNG)

![alt text](https://github.com/Maithri-CH/IndoorNavigation/blob/master/images/step52.PNG)

