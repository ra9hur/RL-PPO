![Course Image](images/course_image.jpg)

In this repo you can find my implementation for exercises of the [Deep Reinforcement Learning Course](https://huggingface.co/deep-rl-course) from [Hugging Face](https://huggingface.co/).

The original course material is implemented in notebooks for Google Colab. However, I have tried to implement and run locally to gain better understanding of these exercises.

# UNITS

You can find the exercise for each unit in his respective folder. Here is a brief summary of each one:
- [Unit 1](unit-1): **Introduction** A general introduction to Reinforcement Learning, where you can learn the basic concepts. In the exercise you can train an agent controlling a simple spaceship to land on the moon.

- [Unit 2](unit-2): **Q-Learning** model explanation. In the exercise you can train a Q-Learning agent (**implemented from scratch**) to play in two different environments: [Frozen Lake v1](https://www.gymlibrary.dev/environments/toy_text/frozen_lake/) and [Taxi v3](https://www.gymlibrary.dev/environments/toy_text/taxi/).

- [Unit 3](unit-3): **Deep Q-Learning** model explanation. In the exercise you can train a Deep Q-Learning agent to play Atari games using the game frames and Convolutional Neural Network (CNN).

- [Unit 4](unit-4): A review of **Policy-based methods**. In the exercise you have to implement the *Policy Gradient* algorithm using *Pytorch* to play in two different environments.

- [Unit 5](unit-5): Introduction to the fundamentals ot the [ML-Agents](https://github.com/Unity-Technologies/ml-agents) **toolkit**. In the exercise you have to train agents for two [Unity](https://unity.com/) environments: *SnowballTarget* (created at Hugging Face) and *Pyramids* (created by the Unity team).

- [Unit 6](unit-6): This unit explains a new algorithm called **Actor-Critic**, which is a combination of *Value-Based* and *Policy-Based* methods. In the exercise you can train agents for two robotic based environments.

- [Unit 7](unit-7): An introduction to **Multi-Agents Reinforcement Learning (MARL)**. In the exercise you have to train a MARL system to play soccer in a 2vs2 match. The environment is a [Unity](https://unity.com/) environment and the model is trained using [ML-Agents](https://github.com/Unity-Technologies/ml-agents).

- [Unit 8 part 1](unit-8): Explanation of the **Proximal Policy Optimization (PPO)** algorithm. In the exercise you implement a PPO agent from scratch using Pytorch to play Lunar Lander environment.

- [Unit 8 part 2](unit-8-part2): Application of the **Proximal Policy Optimization (PPO)** algorithm in a [VizDoom](https://vizdoom.cs.put.edu.pl/) environment. The exercise uses the *Health Gathering Supreme* environment from VizDoom, and uses the [Sample Factory](https://www.samplefactory.dev/) library (focused on efficiency) to train the models with a high-throughput pipeline.

