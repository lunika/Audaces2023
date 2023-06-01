---
theme: purplin
title: "GIP France Université Numériques : services et des technos"
---

# Audaces 2023

GIP France Université Numériques : services et des technos

<BarBottom  title="Audaces 2023">
  <Item text="openfun">
    <carbon:logo-github />
  </Item>
  <Item text="@open_fun">
    <carbon:logo-twitter />
  </Item>
  <Item text="blog.openfun.fr">
    <carbon:link />
  </Item>
</BarBottom>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: intro
---

# FUN ?

France Université Numérique

- ✨ **2013**
- 🌐 **fun-mooc.fr** : Plateforme de Mooc francophone
- ♻️ **Services** : Outils opensource
- 👷 **8 devs** : une petite équipe

<BarBottom  title="Audaces 2023">
  <Item text="openfun">
    <carbon:logo-github />
  </Item>
  <Item text="@open_fun">
    <carbon:logo-twitter />
  </Item>
  <Item text="blog.openfun.fr">
    <carbon:link />
  </Item>
</BarBottom>

<!--
Créée en 2013 par le MESR
Historiquement plateforme de cours en ligne internationale
Pus récemment : créer des outils opensource dédiés à l'éducation. Notion de bien commun dédié à l'éducation
Volonté de notre part de partager notre savoir.
-->

---
layout: intro
---

# Historique

- 🐍 **python**
- 📄 **Open edX** : Learning Management System
- 💩 **Fork** : plutôt que de contribuer/externaliser...

<BarBottom  title="Audaces 2023">
  <Item text="openfun">
    <carbon:logo-github />
  </Item>
  <Item text="@open_fun">
    <carbon:logo-twitter />
  </Item>
  <Item text="blog.openfun.fr">
    <carbon:link />
  </Item>
</BarBottom>

<!--
- Choix d'utiliser le LMS Open Edx. A été opensourcé au moment d'en choisir un, choisi par l'INRIA
- Développé en python, FUN ne fera que du python depuis
- Choix de Fork pour rajouter et modifier des fonctionnalités.
-->


---
layout: intro
---

# OpenFun

Orga open source de FUN MOOC

- ✨ **2018** : projets open source
- 🚧 **Mikado** : Refactorisation de l'existant
- 👷 **LTI** : Learning Tools Interoperability 

<BarBottom  title="Audaces 2023">
  <Item text="openfun">
    <carbon:logo-github />
  </Item>
  <Item text="@open_fun">
    <carbon:logo-twitter />
  </Item>
  <Item text="blog.openfun.fr">
    <carbon:link />
  </Item>
</BarBottom>

<!--
- 2018 changement de paradigme, de nouveaux projets sont lancés et tous en opensource
- Mise en place de la stratégie Mikado
- Découverte du protocole LTI
-->

---
layout: intro
---

# Mikado

Dans quel cas l'utiliser ?

- 📈 Grosse dette technique
- 🚨 Code non maintenable ni évolutif
- 💀 Upgrade dépendances impossible

🔥 Refactorisation obligatoire 🔥

<BarBottom  title="Audaces 2023">
  <Item text="openfun">
    <carbon:logo-github />
  </Item>
  <Item text="@open_fun">
    <carbon:logo-twitter />
  </Item>
  <Item text="blog.openfun.fr">
    <carbon:link />
  </Item>
</BarBottom>

<!--
Dans quel cas utiliser la méthode Mikado ?
- Dette technique accumulée et colossale
- Code non maintenable ni évolutif
- Upgrade dépendances impossible

La refactorisation de l'existant devient une obligation.
Oui mais, nous n'avons pas réellement la main sur le code
-->

---
layout: image-x
image: '/images/RefactoringGraphExample.png'
imageOrder: 2
---

# Mikado

Méthode

- Définir l'objectif à atteindre de la factorisation
- Garder un code qui fonctionne tout au long du processus
- Itération par expérimentation

<BarBottom  title="Audaces 2023">
  <Item text="openfun">
    <carbon:logo-github />
  </Item>
  <Item text="@open_fun">
    <carbon:logo-twitter />
  </Item>
  <Item text="blog.openfun.fr">
    <carbon:link />
  </Item>
</BarBottom>


---
layout: image-x
image: '/images/handbook.png'
imageOrder: 2
---

# Handbook

https://handbook.openfun.fr/

---
layout: image-x
image: '/images/DoKub.png'
imageOrder: 2
---

# Runtime

https://github.com/openfun/arnold

---
layout: intro
---

# FUN-APPS

https://github.com/openfun/fun-apps

---
layout: image-x
image: '/images/python-docker.png'
imageOrder: 2
---

# Stack technique

- 🐍 **python** : Django / DRF / FastApi
- 🐋 **docker** : docker + helm + k8s
- <mdi-react /> **reactjs** : react + typescript

---
layout: intro
---

# LTI

Learning Tools Interoperability 

---
layout: intro
---

# XAPI

Experience API

---
layout: image-x
image: '/images/marsha-color-light.png'
imageOrder: 2
---

# Marsha

https://github.com/openfun/marsha 

https://marsha.education

- ~ 18k requêtes/heure

---
layout: image-x
image: '/images/marsha-color-light.png'
imageOrder: 2
---

# LCMS

Learning Content Management System

- VOD (hls)
- Webinaire (jitsi -> RTMP -> hls)
- Classe virtuelle (BigBlueButton)
- Markdown editor (MD + katex + mathjax)
- Dépôt de documents
- Documents
- ???

---
layout: image-x
image: '/images/marsha-color-light.png'
imageOrder: 2
---

# Stack

- <mdi-language-python /> Django + DRF + channels
- <mdi-react /> React + typescript
- <mdi-docker /> Docker
- <mdi-terraform /> Terraform
- <mdi-lambda /> Lambda function
- <mdi-xmpp /> XMPP

---
layout: image-x
image: '/images/richie-color-light.png'
imageorder: 2
---

# Richie

https://github.com/openfun/richie

Portail catalogue de cours

---
layout: image-x
image: '/images/ashley-color-light.png'
imageOrder: 2
---

# Ashley

https://github.com/openfun/ashley

Multi tenant forum

---
layout: image-x
image: '/images/cunningham.png'
imageOrder: 2
---

# Cunningham

https://github.com/openfun/cunningham

Design System