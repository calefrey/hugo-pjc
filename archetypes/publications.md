---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
params:
    authors: 'John Smith, **Sleve McDichael**, Bob Dugnutt'
    publication: 'ICML, 2024'
    url: 'https://cat3d.github.io/'
draft: false
---
A summary of the publication