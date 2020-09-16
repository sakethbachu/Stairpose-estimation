# Stairpose-estimation

## Description
Pose estimation has been one of the most important tasks for mobile robots. However, there is no robust solution for estimating stair pose. In this project we aim to build a robust end-to-end pipeline to estimate pose of a staircase and hence use it for effective motion planning in mobile robots.

## Note
This repository is constantly being updated.

## Methods
* The major task is to calculate the vanishing points of the stair case, with which the pose of the staircase can be calculated. 
* Currently ResNet based UNETis being used to semantically segment the stair edges which are inturn used to calculate the vanishing points.
* The following pictures show an example input and its mask,

<img src="https://github.com/sakethbachu/Stairpose-estimation/blob/master/img/520.png" width="300" height="300"> &nbsp; &nbsp;<img src="https://github.com/sakethbachu/Stairpose-estimation/blob/master/img/520mask.png" width="300" height="300">

## Requirements
* Fast.ai
* PyTorch
* OpenCv
* Scikit-learn

## Results
<img src="https://github.com/sakethbachu/Stairpose-estimation/blob/master/img/gtruth.png">
