# Snake_DeepRL
Bachelor Project Course C2

Implement a game with Reinforcement Learning (OpenAI Gym), and use a Deep Neural Network (Keras) to train it.

The chosen game was Snake, and here is implemented in a version of Snake for OpenAI Gym, in the file snake_env, that returns the standard Gym funtions:
-env.reset, env.render, env.step, env.observation_space, env.action_space.

The file snake_dqn calls the env and uses Keras to create a double q-network and train it.
