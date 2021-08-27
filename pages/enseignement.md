---
layout: page
title: Enseignements
description: Cours 2021/2022
---

            {% for link in site.navigationbar2 %}
              <a class="brand" href="{{ link.path }}">{{ link.title }}</a>
            {% endfor %}

- [Accueil](../index.html)
- [Cours de statistiques bayesiennes](bayes/index_bayes.html)
