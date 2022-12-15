# TP - Git

Prénom :
Nom :

## Avant de commencer

- Créez un dépôt privé vide (décochez "Initialize repository with a README") sur Gitlab et ajoutez moi : jean-smaug
- Clonez ce dépôt et changez l'url du dépôt distant avec la commande distante

```bash
# Afficher l'URL du dépôt distant
git remote -v

# Mettre à jour l'URL du dépôt distant
git remote set-url origin <URL_DE_VOTRE_DEPOT_GITLAB>
```

## Partie 1 - Explications (14 points)

Cette partie est une restitution des connaissances que vous avez acquises sur l'utilisation de Git et Github. Plutôt que de vous laisser libre sur la rédaction, cela est sous forme de questions-réponses. Détaillez en utilisant les concepts vus en cours (zones, cycle de vie, référence...).
Répondez aux questions directement dans le `README.md` de la branche `master`. N'effacez **PAS** les questions, merci.
Pensez aussi à mettre votre prénom et votre nom en haut du fichier.

### Quelle sont les deux façons d'initialiser un dépôt ? (1 point)

<!-- TODO: répondre ici -->

### À quoi sert une Pull Request / Merge Request ? (1 point)

<!-- TODO: répondre ici -->

### Qu'est ce qu'une branche ? (1 point)

<!-- TODO: répondre ici -->

### Vous venez de modifier un fichier. Comment créer un commit ? (3 points)

<!-- TODO: répondre ici -->

### Pourquoi est-il plus prudent d'utiliser `origin/master` plutôt que `master` pour se mettre à jour ? (1 point)

<!-- TODO: répondre ici -->

### A quoi servent les commandes `git status`, `git log` ? Quand les utiliser ? (2 points)

<!-- TODO: répondre ici -->

### Quelles sont les conditions qui doivent être réunies pour que des conflits surviennent ? (2 points)

<!-- TODO: répondre ici -->

### Imaginez que la branche master du dépôt distant contient de nouveaux commits. Comment intégrer ces commits dans votre branche ? (3 points)

<!-- TODO: répondre ici -->

## Partie 2 - Intégration continue (6 points)

Vous devez mettre en place une intégration continue sur ce projet. Vous devrez utiliser [Gitlab CI](https://docs.gitlab.com/ee/ci/README.html).

Utilisez la branche `php-ci`.
Votre intégration continue devra executer le script `test`.

Vous devrez faire le nécessaire afin que l'intégration continue soit au vert.

## Liens utiles

- Je valide

  - https://learngitbranching.js.org
  - https://git-scm.com/book/fr/v2
  - https://dev.to/unseenwizzard/learn-git-concepts-not-commands-4gjc

- Ça à l'air bien mais je n'ai pas regardé en détail

  - https://www.grafikart.fr/formations/git

## Contact

Si vous avez des questions et que je ne réponds pas sur Discord vous pouvez essayer via [Twitter](https://twitter.com/_MaximeBlanc)
