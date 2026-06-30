# 🐦 Flappy Bird AI using Deep Q Network (DQN)

A Deep Reinforcement Learning project where an AI agent learns to play **Flappy Bird** using the **Deep Q Network (DQN)** algorithm implemented with **PyTorch** and **Gymnasium**.

---

## 📌 Project Overview

This project demonstrates how Reinforcement Learning can be used to train an AI agent to play the classic Flappy Bird game.

Instead of manually programming the bird, the agent learns through trial and error by interacting with the environment, receiving rewards and penalties, and maximizing cumulative rewards.

---

## ✨ Features

- 🧠 Deep Q Network (DQN)
- 🎮 Flappy Bird Gymnasium Environment
- 🔄 Experience Replay Memory
- 🎯 Epsilon-Greedy Exploration
- 🎯 Target Network Synchronization
- ⚡ PyTorch Implementation
- ⚙️ YAML Hyperparameter Configuration
- 💾 Automatic Model Saving

---

## 📂 Project Structure

```text
Deep-Q-Network-FlappyBird/
│
├── agent.py
├── dqn.py
├── experience_replay.py
├── game_flappy_bird.py
├── parameters.yaml
├── runs/
│   ├── flappybirdv0.pt
│   └── flappybirdv0.log
├── .gitignore
└── README.md
```

---

## 🧠 Deep Q Network Workflow

```text
Environment
      │
      ▼
Current State
      │
      ▼
Deep Q Network
      │
      ▼
Q Values
      │
      ▼
Choose Best Action
      │
      ▼
Reward + Next State
      │
      ▼
Replay Memory
      │
      ▼
Train Neural Network
      │
      ▼
Repeat
```

---

## 🎮 Action Space

| Action | Description |
|--------|-------------|
| 0 | Do Nothing |
| 1 | Flap |

---

## ⚙️ Hyperparameters

| Parameter | Value |
|-----------|-------|
| Learning Rate | 0.001 |
| Gamma | 0.99 |
| Replay Memory | 100000 |
| Mini Batch Size | 32 |
| Initial Epsilon | 1.0 |
| Minimum Epsilon | 0.05 |
| Epsilon Decay | 0.9995 |
| Target Network Sync | 10 |

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/ritikasainii1234-cloud/Deep-Q-Network-FlappyBird.git
```

Move into the project directory

```bash
cd Deep-Q-Network-FlappyBird
```

Install the required packages

```bash
pip install gymnasium
pip install flappy-bird-gymnasium
pip install pygame
pip install pyyaml
pip install torch torchvision torchaudio
```

---

## ▶️ Run the Game

```bash
python game_flappy_bird.py
```

---

## 🏋️ Train the Agent

```bash
python agent.py --train flappybirdv0
```

---

## 🎮 Test the Trained Agent

```bash
python agent.py flappybirdv0
```

---

## 📁 Output

After training, the best model is automatically saved in:

```text
runs/flappybirdv0.pt
```

Training logs are stored in:

```text
runs/flappybirdv0.log
```

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Gymnasium
- Flappy Bird Gymnasium
- NumPy
- PyGame
- YAML

---

## 📚 Concepts Covered

- Reinforcement Learning
- Deep Reinforcement Learning
- Deep Q Network (DQN)
- Bellman Equation
- Experience Replay
- Target Network
- Epsilon-Greedy Exploration
- Neural Networks

---

## 🚀 Future Improvements

- Double DQN
- Dueling DQN
- Prioritized Experience Replay
- TensorBoard Integration
- Gameplay Recording
- Reward Visualization

---

## 📸 Gameplay

## 🎮 Gameplay

<p align="center">
  <img src="images/gameplay.gif" width="320">
</p>

---

## 👩‍💻 Author

**Ritika Saini**

B.Tech CSE (Artificial Intelligence & Machine Learning)

GitHub: https://github.com/ritikasainii1234-cloud

---

⭐ If you found this project useful, consider giving it a Star!