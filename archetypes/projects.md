---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
weight: 0 # Order in which to show this project on the home page
external_link: "" # Optional external link instead of modal
resources:
    - src: .jpg
      params:
          weight: -100 # Optional weighting for a specific image in this project folder
draft: false
---
