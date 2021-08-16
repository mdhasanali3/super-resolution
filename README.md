# super-resolution (face image)

Face super resolution based on ESRGAN 

##overview

I've used the esrgan technique to transform a low-quality image into a high-quality image.

You must train the model and provide input in the form of a low-resolution image; 

the trained model will return a high-resolution image.


## Results

INPUT & AFTER-SR 

![result](results/result.png)



### Train


1. clone this project

2. Run python gen_lr_imgs.py to get the face imgs with low resolution and pool qualities

3. Set the dir in train.py

* hr_path: The path list of imgs with high resolution.

* lr_path: The path of imgs with low resolution.

4. Run python train.py

