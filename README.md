## Trading Bot implementation

Our goal for this project is to implement a stock trading bot which is capable of making intelligent decisions that increases the overall profit at a given time. We plan to implement and compare the results of three different techniques namely,  Deep Q-Learning, Double Deep Q-Learning, and Actor -Critic method.

Code References:
Actor critic Pytorch : https://github.com/pytorch/examples/blob/master/reinforcement_learning/actor_critic.py

#### Team Members

- [Thasleem Tajudeen](https://github.com/Thaslim)
- [Mohdi Habibi](https://github.com/mohdihabibi)
- [Rakesh Amireddy](https://github.com/rakeshamireddy)


#### Steps to run DQN 

    - python3 train.py data/GOOG.csv --episode-count 1000 --debug --window-size 5
    - python3 eval.py data/GOOG_2019.csv --window-size 5 --model-name model_dqn_1000 --debug


#### Actor-Critic Test Results
![](https://github.com/mohdihabibi/Trading-Bot/blob/master/Actor-Critic/Test_results-AC.png)

#### DQN Test Results
![](https://github.com/mohdihabibi/Trading-Bot/blob/master/DQN/plots/DQN_Test_Sell_vs_Buy.png)

#### DDQN Test Results
