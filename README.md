# transfer_learning_mobileNet

__step 1__:-importing the MobileNet pretrained model and download the weight of mobileNet.< br/>
![step 1](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/1.JPG) < br/>
__step 2__:-next we are making our layer that will be implmenting on top of the Mobilenet layer.<br/>
![step 2](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/2.JPG) <br/>

__step 3__:-next we are importing the necessary layers  and num_classes here is the category in total,which we are predicting. means how many  different catagory we are predicting here i am predicting two values.< br/>
![step 3](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/3.JPG)< br/>
__step 4__:-next we are doing some image augmentation,generally we do not have the lots of images so by the augmentation we just make new images like by doing zoom,tilt the image etc . a little change in the image for system it is pure new image. here also defining the data location  of training and testing or validation dataset. the location in which your data set is present provide the location here.<br/>
![step 3](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/4.JPG)<br/>

__step 5__:-next we are setting up the epochs , optimizers like RMSprop also saving the model,,in each epochs accuracy is mention the best accuracy will be saved.<br/>

![step 5](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/5.JPG)<br/>

__step 6__:-here we are fitting the model ans also defining the running accuracy between testing and validation/testing dataset.<br/>
![step 6](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/6.JPG)<br/>

__step 7__:-next we are simply checking our model that it is predicting right or not.<br/>
![step 7](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/7.JPG)<br/>
![step 8](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/8.JPG)<br/>
![step 9](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/9.JPG)<br/>
![step 10](https://github.com/sanjaytripathi97/transfer_learning_mobileNet/blob/master/code_image/10.JPG)<br/>
