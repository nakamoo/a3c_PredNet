# Preaictive Net + A3C

This is an attemp to run A3C using Predictive Net agent.

## Requirements

- Python 3.5.1
- chainer 1.8.1
- cached-property 1.3.0
- h5py 2.5.0
- Arcade-Learning-Environment

## Branch
- main

You can use FF/LSTM agent (made by @muupan).

- PredNet

You can use Predictive Net agent (learn only actor and critic).

- PredS

You can use Predictive Net agent (learn actor and cricit, and predic next state).

## Run

```
python a3c_ale.py <number-of-processes> <path-to-atari-rom>
```

## Acknowledgment
This code is mostly  based on muupan's project.
