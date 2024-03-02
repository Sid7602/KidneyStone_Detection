# KidneyStone_Detection
A medical purpose project which helps in Identifying the Kidney Stone Region in the CT Scanned Images.

This is a Deep Learning based project to Identify the input image as Kidney Stone image or a Normal Kidney image.
The neural network used here is Deep Kroneck Neural Network and implementing 10 fold cross validation to imporve the learning metrics of the model.
The input to the images are prepocessed data and this proprocessing was implemented in three stages as follows:
1. Embossing the images
2. Identifying the Region of Interest using Otsu's Thresholding Method(algorithm)
3. Cropping the identified Region of Interest.

The dataset is divided into two parts Train and Test where in Train there are 625 KidneyStone images and 828 Normal images; and in Test there are 165 Kidney Stone images and 185 Normal images.
The dataset is provided in the respository but for reference the dataset was initially taken from the link given below.
[https://github.com/kencoca/VietNam-Medicinal-Plant](https://github.com/yildirimozal/Kidney_stone_detection/tree/main/Dataset)
