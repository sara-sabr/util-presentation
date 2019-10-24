---
layout: default
title: Page d'accueil
ref: home
lang: fr
permalink: /accueil.html
---
Pour utiliser cet outil, vous devez soit enregistrer votre fichier "markdown" sur le repo de projet dans le dossier de présentation, soit pointer vers un lien d'un fichier externe accepté (validé au niveau de l'organisation ou de l'utilisateur GitHub).

Les modes suivants existent (classés par priorité) :
- markdown : Une présentation trouvée dans le dossier du référentiel'présentation'.
- url : Une URL entièrement qualifiée
- gh-scope : Un nom d'utilisateur/org et de référentiel GitHub. Ex : e-wu/test ou sara-sabr/ITStrategy.
             Doit être jumelé avec gh-file.
- gh-file : Un chemin d'accès GitHub vers un fichier md. (Doit être trouvé dans le "master" par défaut)
- gh-branch : Une autre branche

Exemple utilisant les fichiers situés dans le dossier `presentation` du répertoire de projet:

```html
https://sara-sabr.github.io/util-presentation/presentation.html?markdown=/en/example.md
```

Exemple utilisant un URL qualifé en paramètre:

```html
https://raw.githubusercontent.com/sara-sabr/ITStrategy/master/presentations/en/2019-11-12-OSS-Using.md

Note : Cet utilitaire est basé sur les projets de logiciels libres [Reveal.js](https://revealjs.com/#/https://revealjs.com/#/) et [Jekyll](https://jekyllrb.com/).
