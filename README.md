# Fetch-Robotics-DDPG-HER
PyTorch immplementation of Deep Deterministic Policy Gradient (DDPG) with Hindsight Experience Replay (HER)

Final Project for EECS6892

Configs are specified in config.yaml

To train the model, run
```
python train.py --run_name her_sparse --use_her --sparse_reward
```

Add `--use_her` to use Hindsight Experience Replay, Add `--sparse_reward` to run the sparse reward version of the environment