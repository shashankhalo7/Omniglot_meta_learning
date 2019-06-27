# Omniglot - One Shot Learning using Meta Learning(Learning to learn)
### Author : Shashank Pathak😎😎😎<br>
Implementing One Shot Learning using Meta Learning on Omniglot Dataset

### Resources:
If you are new to Meta Learning and Few shot Learning you may find the following resources quite helpful:<br>
#### Blogs:
1) Great Medium Post on One Shot Learning by  **Harshall Lamba.** [Link](https://towardsdatascience.com/one-shot-learning-with-siamese-networks-using-keras-17f34e75bb3d) <br>
2) From zero to research — An introduction to Meta-learning by  **Thomas Wolf** [Link](https://medium.com/huggingface/from-zero-to-research-an-introduction-to-meta-learning-8e16e677f78a) <br>
3) Meta-Learning: Learning to Learn Fast by **Lilian Weng** [Link](https://lilianweng.github.io/lil-log/2018/11/30/meta-learning.html)

#### Videos and Conferences:
1) Automatic Machine Learning at NeurIPS 2018 by **Frank Hutter** and **Joaquin Vanschoren** [Link](https://www.youtube.com/watch?v=0eBR8a4MQ30&t=597s)
2) **Siraj Raval's** Introductory video on Meta Learning [Link](https://www.youtube.com/watch?v=2z0ofe2lpz4)
3) Meta-Learning and One-Shot Learning [Link](https://www.youtube.com/watch?v=KUWywwvQv8E)<br>
4) **Ilya Sutskever's** talk on OpenAI Meta-Learning and Self-Play at MIT Artificial Intelligence (AI) Podcast [Link](https://www.youtube.com/watch?v=9EN_HoEk3KY&t=222s)<br>

#### Dataset
The dataset used in this project is the Omniglot Dataset which is handwritten character dataset which contains 50 alphabets. It is split into a background set of 30 alphabets and an evaluation set of 20 alphabets. It contains 1623 different handwritten characters from 50 different alphabets.Each character has been drawn by 20 different person so for every character of these 50 alphabet we have 20 images.<br>

![](https://github.com/shashankhalo7/Omniglot_meta_learning/blob/master/omniglot_grid.jpg "Omniglot Data")

The dataset can be downloaded from [here](https://github.com/brendenlake/omniglot#citing-this-data-set).There are two type of data available one is the strokes data which contains the timestamped position of the pen strokes in the format `[x,y,t]` where x and y are the coordinates and t is the time in milliseconds. Another is the images data which contains the images of the hand drawn characters. We will be using the images dataset for the one shot classification problem.So download the `images_background.zip` and `images_evaluation.zip` inside `python` folder for training and testing data respectively.  

#### Citing this data set

Please cite the following paper:

[Lake, B. M., Salakhutdinov, R., and Tenenbaum, J. B. (2015). Human-level concept learning through probabilistic program induction.](https://arxiv.org/abs/1902.03477) Science, 350(6266), 1332-1338.

**Check the Code posted in this repo for Implementation**(Comming Soon)
