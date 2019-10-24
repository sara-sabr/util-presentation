---
layout: default
title: Home Page
ref: home
lang: en
permalink: /home.html
---
To use this tool, you need to either save your markdown file on the project repo in the presentation folder or link to an external accepted file (validated at GitHub organisation/user level).

The following mode exists (ordered by priority):
- markdown : A presentation found in repository folder 'presentation'
- url      : A fully qualified URL
- gh-scope : A GitHub user/org and repository name. Ex: e-wu/test or sara-sabr/ITStrategy.
             Must be paired with gh-file.
- gh-file  : A GitHub file path to a md file. (Must be found in master by default)
- gh-branch: Another branch

Example using a file located in the `presentation` folder of the project repository:

```html
https://sara-sabr.github.io/util-presentation/presentation.html?markdown=/en/example.md
```

Example using a qualified URL parameter:

```html
https://raw.githubusercontent.com/sara-sabr/ITStrategy/master/presentations/en/2019-11-12-OSS-Using.md
```

Note: This utility is powered by the [Reveal.js](https://revealjs.com/#/https://revealjs.com/#/) and [Jekyll](https://jekyllrb.com/) open source projects.
