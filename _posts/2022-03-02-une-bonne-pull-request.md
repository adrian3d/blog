---
layout: post
title:  "Une bonne Pull Request."
author_name: "Adrian"
---

## De l'importance de faciliter le travail des reviewers

Lorsque j'étais chez Cinemur, en 2016, nous avons mis en place un système de Pull Requests pour améliorer notre code à chaque nouveau déploiement. Mais nous étions jeunes et fous et nous vite tombé dans l'écueil de la lecture du code à la va-vite sans réelle compréhension du travail de l'autre.

Ce *post* va vous permettre de comprendre comment, au fil des ans, j'ai compris les principes qui régissent une bonne PR.

## C'est parti !
### Les PR les plus courtes sont les meilleurs

Une bonne PR est une PR courte, et cela, à plusieurs titres.
- Cela permet d'éviter des conflits au *merge* de la PR. Une grosse PR se gère beaucoup moins bien quand vient le moment de résoudre les potentiels conflits dans le code.
