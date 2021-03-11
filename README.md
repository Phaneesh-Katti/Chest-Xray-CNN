# Chest-Xray-CNN
Developing a simple CNN 

Developing a CNN based on the Chest X-ray dataset from kaggle(www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
  (A simple exaple of Data_augmentation to deal with Overfitting: Usage of rescaling, zooming, width_shifting to create more data)

The model takes images from the above mentioned dataset and it not only detects if the patient has pneomonia, but also is capable of classfying it into bacterial or viral pneumonia

Model details:
Usage of simple filter layers and pooling technique in feature extraction 

    (3 feature extraction layers + 2 pooling layers)
    
    

This data is passed into a simple ANN:
  
    with 2 dense hidden layers with 32 and 64 neurons
    adam optimizer, sparse categorical cross entropy loss function
 


Accuracy graph (overfitted):

![image](https://user-images.githubusercontent.com/78157559/110809435-e1d7ce80-82aa-11eb-9830-aafa70674b2c.png)

Final Accuracy graph:

![image](https://user-images.githubusercontent.com/78157559/110809615-1186d680-82ab-11eb-8bfd-68626ff1050d.png)
