# Lawyerify Decap CMS

## Table of contents

- [Features](#features)
- [Screenshot](#screenshot)
- [Depend repository](#depend-repository)
- [Live demo](#live-demo)
- [Install](#install)
- [Documentations](#documentations)
- [License](#license)


## Features
- rubrics `create false`
- pages
- persons
- places
- expertises
- posts
  - auteurs (posts taxonomy)
  - expertises (posts taxonomy)
  - categories (posts taxonomy)
  - tags (posts taxonomy)
- publications
- config
  - menu `create false`
    - primary
    - secondary
    - legal
    - social
  - top banner
  - seo

## Screenshot


## Depend repository
* Hugolify Decap CMS : https://github.com/hugolify/hugolify-decap-cms

## Live demo
- Front: https://demo.lawyerify.io

## Install

Edit `config/_default/module.yaml` to install the `lawyerify-decap-cms` module with `hugolify-decap-cms`:
```yml
imports:
  - path: github.com/hugolify/lawyerify-decap-cms
  - path: github.com/hugolify/hugolify-decap-cms
```

## Documentations
https://github.com/hugolify/hugolify-template/wiki

## License
Hugolify is free for personal or commercial projects (MIT license)
