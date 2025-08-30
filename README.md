# Snake AI 🐍🤖

## Introduction
This project implements the **Snake game** along with a **Q-learning agent** that learns to play it.  
It includes both a **visual version** (with `pygame`) and a **non-visual version** (for faster training).  

The project is organized into:
- **`LearnSnake`** → Core Snake logic without visualization (training environment).  
- **`VisualSnake`** → Snake game with `pygame` rendering.  
- **`SnakeQAgent`** → Reinforcement learning agent using Q-learning.  
- **`main.py`** → Orchestrates training and gameplay.  

---

## Table of Contents
- [Installation](#installation)  
- [Usage](#usage)  
- [Features](#features)  
- [Dependencies](#dependencies)  
- [Project Structure](#project-structure)  
- [Examples](#examples)  
- [Contributors](#contributors)  
- [License](#license)  

---

## Installation
Clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/Snake-AI.git
cd Snake-AI
pip install numpy pygame matplotlib
