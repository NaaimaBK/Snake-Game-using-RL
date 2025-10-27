# 🐍 Snake Game using Reinforcement Learning

Un jeu Snake classique implémenté avec Python et Pygame, utilisant l'apprentissage par renforcement (Reinforcement Learning) pour entraîner un agent intelligent.

## 🎮 Fonctionnalités

- **Jeu Snake classique** avec interface graphique Pygame
- **Implémentation RL** avec Deep Q-Learning
- **Réseau de neurones** pour l'apprentissage
- **Système de mémoire de replay** pour l'entraînement
- **Visualisation en temps réel** des progrès de l'entraînement
- **Mode jeu humain** vs **mode IA**

## 🏗️ Architecture du Projet
Snake-Game-using-RL/
│
├── src/                          # Code source principal
│   ├── agent.py                  # Agent RL et algorithme DQN
│   ├── game.py                   # Environnement du jeu Snake
│   ├── model.py                  # Architecture du réseau de neurones
│   ├── replay_model.py           # Mémoire de replay experience
│   ├── helper.py                 # Fonctions utilitaires
│   └── snake_game_human.py       # Version jouable par un humain
│
├── models/                       # Modèles entraînés sauvegardés
│   ├── best_model.pth
│   └── latest_model.pth
│
├── assets/                       # Ressources graphiques et sons
│   ├── images/
│   │   ├── snake.png
│   │   ├── apple.png
│   │   └── background.jpg
│   └── fonts/
│       └── arial.ttf
│
├── README.md                     # Documentation principale
└── .gitignore                    # Fichiers à ignorer par Git


## 🚀 Installation

### Prérequis
- Python 3.7+
- Pip

### Installation des dépendances
pip install pygame numpy torch matplotlib

## 🎯 Utilisation
### Jouer en mode humain
python snake_game_human.py

### Entraîner l'agent RL
python game.py

### Tester un modèle pré-entraîné
python replay_model.py
