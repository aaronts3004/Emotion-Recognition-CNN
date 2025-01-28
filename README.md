# Emotion-Recognition-CNN
Correctly recognizing other people's emotions solely based on their facial expressions has been proven to be a task that is often surprisingly difficult for us humans. 
For example, we often mistake a surprised face with a scared expression. 
This led me to the idea of training a classifier on a fer (facial expression recognition) dataset, to see if machines could do it better. 
I compare 3 models: a classic 4-layer cnn, a 4-layer resnet, and the pre-trained resnet-18 model from pytorch. 
The dataset contains facial expression images which are labeled with 7 emotions (angry, disgust, fear, happy, neutral, sad, surprise).
The training accuracy hits a plateau at ~60%. This is probably due to the small size of the dataset, and because it is slightly imbalanced towards the 'happy' class label. 


