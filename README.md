# BipedalWalkerHardcore-v2
Using ARS(Augmented Random Search) policy in OpenAI gym BipedalWalkerHardcore-v2

---

## Abstract
OpenAI gym BipedalWalkerHardcore-v2 https://gym.openai.com/envs/BipedalWalkerHardcore-v2/ is harder than the basic one (BipedalWalker).

You have to get the reward 300 in 2000 training timesteps, you will get reward -100 when the robot fall down and the game is over.

## Environment
Training on the Google Colab. 

If you want to train in jupyter notebook, although you run ```!pip install gym[all]``` or ```!pip install Box2D```, it may have possible to get the error like "No module named ‘Box2D’". Then you can follow the direction for install PyBox2D.whl 
(Python Extension Packages for Windows) in https://ithelp.ithome.com.tw/articles/10229349.

---

training 2,000 timesteps:

training 4,000 timesteps:

![](https://github.com/wesley989898/BipedalWalkerHardcore-v2/blob/master/4000_timesteps.gif)

training 10,000 timesteps:

## timesteps
You can change timesteps in ```agent.train_population(2000)```. (ex:2000 to 4000)

But if you want to paticipate the GYM contest, it only allow training below 2000 to finish the job.
