# Image-Classification-on-CIFAR-10-using-CNN
Image Classification on CIFAR-10 using basic CNN and modified CNN

Image Classification has changed and accelerated technical breakthroughs in a variety of industries, including automobiles, healthcare, manufacturing, and more.

The goal is to use the CIFAR-10 dataset to train a Convolutional Neural Network and use it to predict or classify a given image. The CIFAR-10 dataset has 60000 images separated into ten classes, each with 6000 images. Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, and Truck are the classes. There are five training batches and one test batch in the dataset. The test batch consists of 1000 images chosen at random from each class. 

> Basic CNN Image Classification Model

<img width="557" alt="image" src="https://user-images.githubusercontent.com/101949683/184738521-830f4c74-3adc-411f-9e10-98061587855c.png">


> Modified CNN Image Classification Model

<img width="559" alt="image" src="https://user-images.githubusercontent.com/101949683/184738975-402b74a0-aeb6-4e91-a48b-035dd3b16010.png">

> Image prediction

<img width="293" alt="image" src="https://user-images.githubusercontent.com/101949683/184739167-74c2b413-7184-424b-b8e0-3082f725c382.png">

> Key Findings

1.	For the Basic Implementation of the CNN model for Image Classification:
a.	After 10 epochs, the loss on training data is 0.7341, and classification accuracy on training data is 74.5%
b.	The loss on validation data is 0.9757 and the classification accuracy on validation data is 66.53%
2.	For the Modified Implementation of the CNN model for Image Classification:
a.	After 30 epochs, the loss on training data is 0.4811, and classification accuracy on training data is 82.94%
b.	The loss on validation data is 0.5666 and the classification accuracy on validation data is 80.72%
3.	To test both the models, they were provided with an input image of an Aeroplane. Both were able to predict the label correctly as shown in the results.

> Conclusion

Although both models correctly predicted the input image, the modified model has a higher score and is more reliable, as evidenced by the classification accuracy scores of both models. This could be improved even more by tweaking the CNN. This tweaking may include adding more convolutional layers, modifying hyperparameters, adding dense layers, etc. With the CIFAR-10 dataset, existing models such as ViT-H/14, CaiT-M-36 U224, CvT-W24, and many others have already achieved 99 percent or higher accuracy

> Copyright 2022 Rishil Darne

