# Holdem

Reinformcement learning for Limited Holdem


## Usage

```bash
cd holdem
python train.py
```

An example to test the codebase is to run the following command:

```bash
python train.py --log-dir="experiments/limit_holdem_dqn_test/" --num-episodes=50000 --num-eval-games=2000 --save-every 10000  
```