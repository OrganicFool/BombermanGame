# BombermanGame
A keras implementation of the student selection problem on QM‘s Design &amp; Build Winter Hack, which based on PPO algorithm and Imitation learning pre-train strategy

## Description
In the Code, I define a environment for the bomber game(a little different bewteen origin version).The hyperparameters are set at the top of each script.
## Version
keras:2.2.4

tensorflow:1.13.1(it only ran on gpu before)
## Usage
**Step 1.
Install [Keras 2.2.4](https://github.com/fchollet/keras) 
with [TensorFlow](https://github.com/tensorflow/tensorflow) backend.**
```
pip install tensorflow-gpu
pip install keras==2.2.4
```

**Step 2. Clone this repository to local.**
```
git clone https://github.com/AntiBupt/Ensemble-method-based-on-reinforcement-learning.git
cd Ensemble-method-based-on-reinforcement-learning
```
**Step 3. Train the model with default configuration.**
```
python train.py
```
## problems(10/19/2019)
1.A lot of hyperparameters can't be adjusted

2.demo.py(I plan to write a script for generating a video for show) 

3.It only supportted classification and numpy input(ImageDataGenerator will be used)

4.No available checkpoint

5.OpenAI gym API(gym.openai.com) it will be compatiable with gym API

## problems(12/16/2019)
pre_train isn't available now because of the change of input dimension, this will be updated later.


## Contact me
```
E-mail:xiahandong6250@bupt.edu.cn
WeChat:xhd19990625
```
