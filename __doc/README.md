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

git diff # voir les différence entre les versions d'un même fichier 
```
