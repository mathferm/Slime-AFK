# Slime-AFK
Il s'agit d'un programme simple pour héberger et automatiser un bot slime pour Hypixel Skyblock.

## Caractéristiques
- Envoi automatique sur ton island.
- Configuration simplifiée.

## Installation
- Remplissez les champs du `config.json`.
- Exécutez `npm install`.
- Fait!

## Usage
- Pour démarrer le bot, exécutez `npm start` ou `node index.js`.
- Le bot rejoindra Hypixel et entrera automatiquement dans son island.

## Configuration
- `server`:
    - `ip` - IP du serveur auquel se connecter.
    - `port` - port du serveur auquel se connecter (le plus souvent `25565`).
- `account`:
    - `username` - Email de votre compte Mojang/Microsoft.
    - `accountType` - `mojang` ou `microsoft`, type de votre compte.
- `bot`:
    - `logAllMessages` - s'il est défini sur `true`, enregistre tous les messages que le bot reçoit dans la console.
    - `logTime` - si défini sur `true`, enregistre l'heure de tous les événements du bot dans la console.
