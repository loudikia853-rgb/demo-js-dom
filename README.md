# Démo commune — Git & JavaScript/DOM

Un seul projet pour les deux présentations : une page web interactive, suivie par Git (3 commits).

## Utiliser

Ouvrir `index.html` dans un navigateur. Aucune installation, aucun serveur.

## Git (à montrer en démo)

```bash
git log --oneline --graph --decorate   # 3 commits
git remote -v                          # lien avec GitHub
git status                             # doit être propre
```

## Publier sur GitHub (une seule fois)

```bash
git remote add origin https://github.com/VOTRE-COMPTE/demo-js-dom.git
git branch -M main
git push -u origin main
```

Créer le dépôt sur https://github.com/new **sans** README (il existe déjà ici).

> Les commits ont été créés avec l'auteur « Prénom Nom / email@exemple.com ». Avant de pousser, vous pouvez le remplacer :
> `git config --local user.name "Votre Nom"` et `git config --local user.email "votre@email.com"`, puis `git commit --amend --reset-author --no-edit` pour le dernier commit.
