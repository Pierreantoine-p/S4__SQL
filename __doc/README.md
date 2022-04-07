# Trombin-o-clock

## Au menu du jour

- Organiser un projet
- SQL

## Commandes GIT

```text
git init # Initialise un nouveau repo git en local: il crée le dossier .git

# ATTENTION là il faut un repo Github existant
git remote add origin git@github.com:<...>.git # On lie le repo GH au local

git remote -v # pour voir le(s) remote(s) actuel(s)

git status # Montre les différence entre l'arbre de travail et l'index GIT

git add README.md __docs/CLIENT.md
git add .  # Faire en sorte que le fichier (ou tous les fichiers avec `.`) soit suivi par git

git add CHEMIN_RELATIF_VERS_FICHIER1 CHEMIN_RELATIF_VERS_FICHIER2 # pour cibler un seul fichier ou plusieurs

git commit -m "MON MESSAGE" # Valider les modifications dans les commits

git log # voir l'historique des commits

git branch # voir les branches existantes en local

git diff # voir les différence entre les versions d'un même fichier [`q` pour quitter]

git push # envoie les modifications en ligne
```

## User stories

### Modèle

> *Persona → Besoin → Objectif*

|  #  | En tant que...       | je veux... | dans le but de (si besoin)|
| --- | -------------------- | ---------- | ------------------------- |
|  1  | visiteur             |            |                           |
|  2  | visiteur             |            |                           |
|  3  | utilisateur connecté |            |                           |
|  4  | admin                |            |                           |

|  #  | En tant que... | je veux...                                  | dans le but de (si besoin)              |
| --- | -------------- | ------------------------------------------- | --------------------------------------- |
|  1  | Visiteur       | une page d'accueil                          | accéder aux fonctionnalités             |
|  2  | Visiteur       | accéder à la liste des promos               | ...                                     |
|  3  | Visiteur       | accéder au détail d'une promo               | voir la liste des étudiants de la promo |
|  4  | Visiteur       | accéder à la liste exhaustive des étudiants | ...                                     |
|  5  | Visiteur       | accéder au détail d'un étudiant             | ...                                     |
|  6  | Admin          | modifier les infos d'une promo              | ...                                     |
|  7  | Admin          | modifier les infos d'un étudiant            | ...  

## Kanban

Github Projects

| Backlog           | To do                | WIP      | To test  | Done      |
| ----------------- | -------------------- | -------- | -------- | --------- |
| toutes les tâches | à faire (maintenant) | en cours | à tester | terminées |

## Cycles de développement

- modèle en cascade *waterfall-model*
- modèle en V
- modèle itératif (ex : agile)

## Wireframe

Il s'agit bien d'une maquette FONCTIONNELLE et pas d'une pré-maquette graphique.

<https://draw.io>  
<https://wireframe.cc/>

## Architecture

Node + Express
