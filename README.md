### Programming Project
* [Intro to Python Project - Classifying Pet Images:](https://github.com/udacity/AIPND-revision/tree/master/intropyproject-classify-pet-images "Classifying Pet Images Project") Determine which CNN architecture model works best at classifying images of dogs and their breeds.


## Questions to Answer regarding Uploaded Image Classification:

1.	Did the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed? If not, report the differences in the classifications.

     ####  Yes, all the three model architectures classified the dog to be of the same breed.  

2.	 Did each of the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed of dog as that model architecture classified Dog_02.jpg? If not, report the differences in the classifications.

     ####  Yes, all the three model architectures classified the breed of Dog_01.jpg and Dog_02.jpg as same.  
 
3.	Did the three model architectures correctly classify Animal_Name_01.jpg and Object_Name_01.jpg to not be dogs? If not, report the misclassifications.
     ####  No, AlexNet classified Animal_Name_o1.jpg as a dog (ibizan hound, ibizan podenco)
 
4.	Based upon your answers for questions 1. - 3. above, select the model architecture that you feel did the best at classifying the four uploaded images. Describe why you selected that model architecture as the best on uploaded image classification.
     ####  Based on the above three questions, VGG and ResNet reported the correct classifications. But based on elapsed time VGG is better of the both. 
Final Results:
In this project, we had 2 main objectives:
1.	Identifying which pet images are of dogs and which pet images aren't of dogs
2.	Classifying the breeds of dogs, for the images that are of dogs
     ####  The above objectives are met with the program is run and the results are tabulated below. 
 
[logo]: ./intropyproject-classify-pet-images/img.png

![logo]


## Dependencies

Each directory has a `requirements.txt` describing the minimal dependencies required to run the notebooks in that directory.

### pip

To install these dependencies with pip, you can issue `pip3 install -r requirements.txt`.

