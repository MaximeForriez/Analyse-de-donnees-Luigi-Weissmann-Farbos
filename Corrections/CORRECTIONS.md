# Élements de corrections

## Séance 2.

### Questions

- Très bon travail.

### Code

- Il manque l'encodage avec la fonction `open()`. Il faut préciser `encoding="utf-8"`.

```
    with open("./data/resultats-elections-presidentielles-2022-1er-tour.csv", "r", encoding="utf-8") as fichier:
        contenu = pd.read_csv(fichier)
```

## Séance 3.

### Questions

- **Question 5.** C'est l'inverse. La variance n'est pas dans la même unité que la moyenne, tandis que l'écart type l'est. Par la suite, vous rétablissez la bonne réponse. C'est incohérent. Il manque dans les quantiles les plus utilisés : les déciles. De même, les déciles sont importants dans l'interprétation d'une boîte de dispersion.

- Bon travail.

### Code

- Il manque le type de lecture la fonction `open()`. Il faut préciser `"r"`.

```
    with open("./data/resultats-elections-presidentielles-2022-1er-tour.csv", "r", encoding="utf-8") as fichier:
        contenu = pd.read_csv(fichier)
```

## Séance 4

### Questions

- Bon travail. Quelques imprécisions, mais rien de bien important.

### Code

- Votre code n'enregistre pas les images.

## Séance 5

### Questions

- Bon travail.

### Code

- Vous avez écrit vos chemins en adresse absolue `"/Users/hsen/Desktop/STT/data/Echantillonnage-100-Echantillons.csv"`. Pour que je lise votre code sans problème sur ma machine, il aurait fallu utiliser une adresse relative : `"./data/Echantillonnage-100-Echantillons.csv"`. C'est un point de détail, mais il est important si vous êtes amené à travailler en groupe.

- Le test de normalité n'est pas bon. L'échantillon 1 est une loi normale, tandis que l'échantillon 2 est une loi de Pareto (bonus).

- Bonus. L'algorithme n'est pas parfait et incorrect, mais il y a de l'idée.

## Séance 6

### Questions

- Bon travail.

### Code

- Le problème d'encodage se pose encore.

- Le problème d'enregistrement des images se pose encore.

## Humanités numériques

- Où est votre réflexion sur les humanités numériques ?

## Remarques générales

- Aucun dépôt régulier sur `GitHub`.

- Vos fichiers `*.py` ne doivent pas avoir de noms fantaisistes. Ils devaient tous s'appeler `main.py`.

- Rapport assez complexe à lire. Faites attention pour votre mémoire final, cela ne passera pas.

- Code de qualité. Bravo !
