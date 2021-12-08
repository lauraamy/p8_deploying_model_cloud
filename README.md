# p8_deploying_model_cloud

# Overview

An AgriTech start-up, called "Fruits!", seeks to offer innovative solutions for harvesting fruits. The start-up would first like to make itself known by providing the general public with a mobile application that would allow users to take a picture of a fruit and obtain information on this fruit.

The goal of this project is to build a first version of the necessary Big Data architecture for the development of the mobile application.

There are two main objectives. In a Big Data environment on AWS:

•	develop a first data processing chain which will include preprocessing and a dimension reduction step

•	set up the data processing and storage bricks that will be used when scaling up in terms of data volume


# Materials

This project was carried out using Pyspark and the AWS cloud to benefit from a Big Data architecture (EC2, S3, IAM).
Based on an EC2 Ubuntu Server 18.04, 64-bit / t2.large / 8 GiB RAM / EBS Storage 8 GiB. 


# The data
Data set consisting of fruit images, available on Kaggle: https://www.kaggle.com/moltean/fruits

Total number of labeled images (one fruit or vegetable per image): 90,483
Train set size: 67,692 images
Test set size: 22,688 images

Number of classes: 131 different species (fruits and vegetables)

Image size: 100 x100 pixels
