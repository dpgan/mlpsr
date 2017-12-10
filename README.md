# Beyond Human-level License Plate Super-resolution with Progressive Vehicle Search and Domain Priori GAN

We release the vehicle license plates in this paper as a benchmark for vehicle license plates super-resolution in this community.

Please download the dataset with the follow link:
1. Baidu YunPan

If you need the dataset, please send the email to liuwu@live.cn.

If you have any problem to download the dataset, please leave a message in the "Issues", we will reply ASAP.

Introduction

To facilitate related research and well evaluate the proposed method, in [1], we collect and label all the vehicle license plates
from the VeRi dataset released in [16]. VeRi has 776 different vehicles and 9000 records captured by 20 surveillance cameras installed along several roads in an 1.0 km2 area, which guarantees data quality and real-world traffic scenarios. The cameras are installed in arbitrary positions and directions. Each vehicle is captured by at least two cameras in varied viewpoints, lightning conditions, and backgrounds, which guarantees practical urban traffic environment. Then ten volunteers are asked to label all the vehicle plate numbers. We select 746 vehicles and 24, 349 plate images, where each vehicle has at least one license plate image can be recognized by human as groundtruth. Then the groundtruth images are removed. Finally, we randomly select 594 vehicles (19,524 plate images) as training and other 152 vehicles (4,825 plate images) as testing set. For each vehicle, one LR image is randomly selected as query image. For each vehicle in training, we generate one groundtruth license plate image with strict rules for training. The dataset is released at https://github.com/dpgan/mlpsr as a benchmark for vehicle license plates SR in this community.

The train_Dataset folder contains training dataset, including 13,002 images for training.
In all the training images, there are 594 diffetent license plates. The train_Dataset folder consists two subfolders:
     1.The train folder contains the input images of the network.
     2.The label folder contains the groundtruth images. There is a one-to-one correspondence between the groundtruth images and the training images.

The test_Dataset folder contains testing dataset, including two subfolders:
     1.The test folder also contains two subfolders:
        1)The query folder includes 152 images as the plate license queries. 
        2)The source folder includes 5,824 images which are searched by the queries.
     2.The test_result folder contains the output images of the network. There is a one-to-one correspondence between the output images and the images in the test folder.

Note: All image size is 180*60. 


[1] Wu Liu, Xinchen Liu, Huadong Ma, Peng Cheng,2017. Beyond Human-level License Plate Superresolution with Progressive Vehicle Search and Domain Priori GAN. In Proceedings of ACM Multimedia conference, Mountain View, CA USA, Oct. 2017 (ACM MM’17), 9 pages.

[2] Xinchen Liu, Wu Liu, Tao Mei, and Huadong Ma. 2016. A Deep Learning-Based Approach to Progressive Vehicle Re-identification for Urban Surveillance. In ECCV. 869–884.
