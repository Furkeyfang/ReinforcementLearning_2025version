# Reinforcement Learning path(2025)     

This is my **first time** to share my code and experience of research on reinforcement learning, in which I will follow a **normal learning path** to update.    
From the **Q learning** to **DQN**, from **the finite action space** to **infinite action space**, I will unfold the picture of Reinforcement learning for you.

The reference material
------------------------
1. To practise your big picture and fundamental [EasyRl 磨菇书](https://datawhalechina.github.io/easy-rl/#/chapter1/chapter1).  
2. To practise your coding ability [动手学强化学习](https://hrl.boyuai.com/chapter/intro).  
3. To have some visual courses [Deep RL Bootcame(from openai)](https://sites.google.com/view/deep-rl-bootcamp/lectures).
4. To have more practical guide [OpenAI Spinning up](https://spinningup.openai.com/en/latest/index.html).

The first project (2025.5.2)
--------------------------
1. Practise the **Q learning** and **Sarsa** on Cliffwalking env.   
2. Compare the difference of this algorithms.
### Here is a finding WOW
When you run the code of **Sarsa** (under the condition of **epsilon = 0.1** and decreasing slowly) , you will find that it cannot converge to -13 (the best reward) as well as **Q learning** after enough training times. However, when epsilon decreases in a faster speed, **Sarsa** can work as well as **Q learning**  
### Here are so thought
1. Is the training times too low (20000 times) for **Sarsa**.
2. Epsilon is not set well so that the exploration time too long for **Sarsa** ? 
