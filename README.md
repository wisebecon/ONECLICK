# ONECLICK V0.1

ONECLICK est une base Electron de macro recorder pour macOS et Windows.

## Installation

```bash
npm install
npm start
```

Build :

```bash
npm run build:mac
npm run build:win
```

## macOS

Pour enregistrer/contrôler la souris au niveau du système, macOS peut demander l'autorisation Accessibilité à ONECLICK.

## V0.1

- Plusieurs macros
- Enregistrement global de mouvements et clics souris
- Enregistrement global des événements clavier
- Touche F1 à F24 configurable par macro
- Relecture rapide ou avec les timings enregistrés
- Éditeur des actions
- Sauvegarde locale des macros
- Import / export JSON

### Limitation V0.1

La capture clavier est enregistrée pour préparer le moteur de replay complet, mais la relecture clavier n'est pas encore activée dans cette version. La V0.2 pourra ajouter le replay clavier complet, le drag-and-drop des actions, l'ajout manuel d'actions et des contrôles de vitesse.
