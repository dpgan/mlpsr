# mlpsr
Please download the dataset with the follow link:
1. Baidu YunPan
https://pan.baidu.com/s/1pKXesTt Password: 6jif

2. Google Drive


To facilitate related research and well evaluate the proposed method, in [1], we collect and label all the vehicle license plates
from the VeRi dataset released in [16]. VeRi has 776 different vehicles and 9000 records captured by 20 surveillance cameras installed along several roads in an 1.0 km2 area, which guarantees data quality and real-world traffic scenarios. The cameras are installed in arbitrary positions and directions. Each vehicle is captured by at least two cameras in varied viewpoints, lightning conditions, and backgrounds, which guarantees practical urban traffic environment. Then ten volunteers are asked to label all the vehicle plate numbers. We select 746 vehicles and 24, 349 plate images, where each vehicle has at least one license plate image can be recognized by human as groundtruth. Then the groundtruth images are removed. Finally, we randomly select 594 vehicles (19, 524 plate images) as training and other 152 vehicles (4,825 plate images) as testing set. For each vehicle, one LR image is randomly selected as query image. For each vehicle
in training, we generate one groundtruth license plate image with strict rules for training. The dataset is released at https://github.com/dpgan/mlpsr as a benchmark for vehicle license plates SR in this community.

[1] Paper ID: 824. 2017. Beyond Human-level License Plate Superresolution with Progressive Vehicle Search and Domain Priori GAN. In Proceedings of ACM Multimedia conference, Mountain View, CA USA, Oct. 2017 (ACM MM’17), 9 pages.

[2] Xinchen Liu, Wu Liu, Tao Mei, and Huadong Ma. 2016. A Deep Learning-Based Approach to Progressive Vehicle Re-identification for Urban Surveillance. In ECCV. 869–884.
