# PHM prediction by residual conventional neural network

This is a program for predicting RUL estimation for a high-speed CNC milling machine cutters, you can download data from [https://www.phmsociety.org/competition/phm/10](https://www.phmsociety.org/competition/phm/10) and run it to predict RUL.

# Notice

This project's page is [HERE](https://kidozh.com/projects/keras_detect_tool_wear/), you may find something interesting about our work.

RUL estimation is prediction for engine by the same method, the accuracy is ideal.

This program are under development.

# recent achivement
By using wavelet transformation, loss (MSE) has been down to 9.0.

According to [PHM Error method](https://www.phmsociety.org/competition/phm/10/scoring), our CNN model's error is 393, way more better than [the best score(5500)](https://www.phmsociety.org/competition/phm/10/leaderboard) at 2010 leaderboard.

# visualization

Topology Data Analysis is implemented for visualizing model's weights, t-SNE method for hierarchy feature.

# dependency
+ Tensorflow / Theano / CNTK
+ Keras

# Introduction

A beamer in demonstration_of_work is to demonstrate what we have done in summer holidays. It is writen in Simplified Chinese.

Please feel free to fork it.

# Licence

MIT LICENSE
