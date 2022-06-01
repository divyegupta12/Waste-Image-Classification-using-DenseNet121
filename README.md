# Waste-Image-Classification-using-DenseNet121
Implemented the DenseNet121 CNN model, using Tensorflow and keras frameworks, which gave the best accuracy for classifying waste images according to the results of our survey.

##INTRODUCTION 
India, the world's second-most densely populated country, continues to face obstacles to its progress in terms of garbage management. It is estimated that India's urban cities produce 10 million tonnes of trash per year. Manual labor and typical industrial sorting procedures are incapable of fulfilling the international community's requirements. This sorting process can be automated by the use of technologies like IOT devices and Deep learning. An automatic classification robot based on effective image recognition could help reduce huge labors of recycling tasks. In this paper we survey and analyze in detail, the state-of-the-art methods in use for waste image classification. The results derived from all the algorithms are compared with each other along with a discussion on the future scope and challenges occurring. We also implement the DenseNet121 CNN model, using Tensorflow and keras frameworks, which gave the best accuracy according to the results of our survey.

##DATASET
We used the TrashNet dataset which consisted of over 2400 images of waste labeled across 5 classes: cardboard, glass, metal, plastic, paper. The pictures were taken
by mobile phone camera using sunlight and/or room lighting. Photographed objects were placed on a white background or filled the whole view (cardboard). All images have a size of 512x384px. The devices used were Apple iPhone 7 Plus, Apple iPhone 5S, and Apple iPhone SE. This dataset has been used in majority of studies related to waste classification.

##RESULTS 
The model achieved a training accuracy of 91% after going over 20 epochs with batch sizes of 15 images each. The model gave an accuracy of 94.8% and a weighted average f1 score of 0.95 on the test dataset showing that the model was not overfitted on the training dataset. The confusion matrix and other results obtained are shown in the figures below.
![image](https://user-images.githubusercontent.com/64646670/171390040-8d34c7bd-71e3-42ae-896f-30f39331f333.png)
![image](https://user-images.githubusercontent.com/64646670/171390178-a3c78b49-371d-46d4-9962-fb969476eadb.png)
