#ReadMe
Our research estimates the facial attributes age and gender from images which are taken in challenging and wild conditions. This problem is concerned less attention in the field of face recognition. Because of the growth of online social networking websites and social media, 
extracted information from images with a level of accuracy is quite useful in person reidentification. We propose a convolutional neural network based model which predicts age and 
gender of multiple attributes. The model is evaluated on the Adience benchmark. Our main contribution is using a unique dataset where age and gender labeled images acquired by smart 
phones and other devices and uploaded without filtering in the image repositories and correcting the whole dataset on the basis of age and gender attributes. These images are more challenging 
than other face photo benchmark. A CNN model for far view image is used as a based line method in order to compare with ours. Experiments show that our model outperforms some of 
the popular methods.
The dataset we used to train and test our model is Adience dataset. It contains close-view images. Adience dataset contains 19,322 images labeled with their gender and age. Faces are divided into 5 folds. Ages are divided with different group which is 0-2, 4-6,
8-13, 15-20, 25-32, 38-43, 48-53 & 60+ and gender are divided into Male and Female class. Original dataset has 30 age label but we cut the label ‘none’ and blank . And include other age 
label into our 8 age class.It captures variations in pose, light, appearance and more. We use 12,272 of images from dataset for training and 3068 for testing. Images original size is 816 by 
816 and we used those image by resizing into 75 by 75. We train our dataset with fitGenerator.
