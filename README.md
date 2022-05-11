# Fetch-Robotics-DDPG-HER
PyTorch immplementation of Deep Deterministic Policy Gradient (DDPG) with Hindsight Experience Replay (HER)

This repo is for EECS6892 Final Project

Model/Training configs can be specified in config.yaml

To train the model, run
```
python train.py --run_name her_sparse --use_her --sparse_reward
```

Add `--use_her` to use Hindsight Experience Replay, Add `--sparse_reward` to run the sparse reward version of the environment

DDPG+HER performance on FetchReach-v1
![DDPG-HER](https://github.com/wangyz1999/Fetch-Robotics-DDPG-HER/blob/main/plot.png?raw=true)

Suggested Readings:
- [Continuous control with deep reinforcement learning](https://arxiv.org/abs/1509.02971)
- [Hindsight Experience Replay](https://arxiv.org/abs/1707.01495)
- [Multi-Goal Reinforcement Learning: Challenging Robotics Environments and Request for Research](https://arxiv.org/abs/1802.09464)
- [DDPG OpenAI Spinning Up](https://spinningup.openai.com/en/latest/algorithms/ddpg.html)
- [Ingredients for Robotics Research](https://openai.com/blog/ingredients-for-robotics-research/)


Some coding structure and/or functions mimics the following repository:
- [RLkit](https://github.com/rail-berkeley/rlkit)
- [hindsight-experience-replay](https://github.com/TianhongDai/hindsight-experience-replay)