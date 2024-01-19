<div align="center">
  <h1><code>BERT Demo</code></h1>
  <p>
    <strong>Démonstration rapide des capacités de BERT pour le cours de DEEP de l'École Centrale de Nantes.</strong>
  </p>
  <p>
    <img alt="logo ECN" src="https://upload.wikimedia.org/wikipedia/fr/thumb/c/c0/Logo_ECN.svg/1200px-Logo_ECN.svg.png" height="300" width="475">
  </p>
</div>

# Installation

Après avoir cloner/télécharger ce dépôt, vous pouvez créer un nouvel environnement virtuel Python avec:

```bash
python3 -m venv venv && source venv/bin/activate
```

Puis installer les dépendances:

```bash
pip install -r requirements.txt
```

# Présentation

## Fill Mask

Ce notebook a pour but de montrer une utilisation très facile et rapide de BERT pour compléter les mots manquants dans les phrases.

## Sentiment Analysis

Ce notebook a pour but de démontrer les capacités de BERT pour faire des plongements de textes dans $R^n$ et la méthode du token `"[CLS]"` pour le sentiment analysis.