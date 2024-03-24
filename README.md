# Chatbot pour ChronoCare

Ce dépôt contient le code et les configurations nécessaires pour le chatbot de ChronoCare. Le chatbot est conçu pour offrir une assistance automatique, répondre à des FAQ et guider les utilisateurs dans leur expérience sur le site.

## Configuration

Le chatbot est développé en Python. Vous devez installer les dépendances avant de démarrer le développement ou le déploiement.

python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

## Démarrage

Pour lancer le chatbot :

python src/main.py

Assurez-vous de configurer les variables d'environnement nécessaires pour la connexion aux services externes, le cas échéant.

go


#### `requirements.txt` pour Chatbot
Listez toutes les dépendances Python nécessaires. Voici un exemple basique incluant `flask` pour un serveur web simple et `python-telegram-bot` pour un bot Telegram.

flask
python-telegram-bot

python


