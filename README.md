## this project is using the car pictures in cifar10 dataset to build DCGAN and WGAN for generating car pictures.
email: lingyi.s@outlook.com

tensorflow 1.15
python 3.6

you can change the class # in dataSet.py to get different data from cifar10 dataset.

for dataSet.py, it is for getting the training data, save as TFRecords.

# for wgan.py, it is the WGAN model.

Total data number 	5000

Batch size	64

Noise size	128

Iterations	35000

Learning rate	0.00005



# for dcgan.py, it is the DCGAN model.

Total data number 	5000

Batch size	64

Noise size	128

Iterations	10000

Learning rate	0.0002


TFR foder is the training data.

best_10_images_for_all is the foder of the best 10 images generated either by WGAN or DCGAN.

dcgan_best_pic and wgan_best_pic are the foders for seperate the images for DCGAN and WGAN. There are 10 images for each model.

# visulize the training data from cifar10
![image1](https://github.com/SidSong01/DeepLearningProjects/blob/master/GANs/pictures/carcifardata.png)

# the loss curve of WGAN
![image2](https://github.com/SidSong01/DeepLearningProjects/blob/master/GANs/pictures/loss_wgan.png)

# the loss curce of DCGAN 
![image3](https://github.com/SidSong01/DeepLearningProjects/blob/master/GANs/pictures/loss_dcgan.png)

# the last 10 car images generated by DCGAN
![image4](https://github.com/SidSong01/DeepLearningProjects/blob/master/GANs/pictures/dcgan_last.png)

# the last 10 car images generated by the WGAN
![image5](https://github.com/SidSong01/DeepLearningProjects/blob/master/GANs/pictures/wgan_last.png)

