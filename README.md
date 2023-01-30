# Self-driving Car Project by Using the NVIDIA Model
In this repository, we are going to try to code a simple self-driving car project. The data that we will used during the project was obtained via the Udacity Self-driving Car Simulator. The main purpose of this project is to predict the correct steering value by using three images that are taken at the same time. We are going to use the NVIDIA model, which is a specific CNN model, to predict steering values.

**Note**: 
* To get the Udacity Self-driving Car Simulator, you can use the following link: https://github.com/udacity/self-driving-car-sim
* To download the data, you can use the following link: https://drive.google.com/file/d/1cbjYNMkUkYVXrcTICBgwuBu1TpYNkG8J/view?usp=share_link

This notebook is separated into two main parts which are preprocessing and model parts. In the preprocessing part, we are going to prepare to the data to feed our model. In the model part, we are going to construct the NVIDIA model with the specific parameters that are published by NVIDIA. The below is a diagram showing what the NVIDIA model basically is.

<p align="center">
<img src="NVIDIA_model_architecture.png" alt="NVIDIA Model Architecture" style="height: 550px; width:400px;"/>

To construct the model by yourself, you can follow the notebook "self-driving_car_project.ipynb". After the trainig process, you can connect your model to the simulator by using the file "drive.py". Also, I recommend you to watch the below video to understand basically how this model works. This video is the comparison of the NVIDIA model (left) and VGG model (right). Both cars in the video are controlled by AI models. For someone who are interested in the original video, here is the link: https://www.youtube.com/watch?v=3O8e9H-RP5k&t=14s&ab_channel=ChrisGundling

https://user-images.githubusercontent.com/85827429/215437788-15a6e68b-167b-4405-9486-42c421a43424.mp4

## REFERENCES
* Bojarski, M., Testa, D. D., Dworakowski, D., Firner, B., Flepp, B., Goyal, P., Jackel, L. D., Monfort, M., Muller, U., Zhang, J., Zhang, X., Zhao, J., &amp; Zieba, K. (2016). End to End Learning for Self-Driving Cars. *NVIDIA Developer*. Retrieved January 30, 2023, from https://developer.nvidia.com/blog/deep-learning-self-driving-cars/.
* Gundling, C. [Chris Gundling]. (2017, January 21). *Udacity self driving car P3 - NVIDIA vs. VGG style on track 2* [Video]. Youtube. https://www.youtube.com/watch?v=3O8e9H-RP5k&t=14s&ab_channel=ChrisGundling
