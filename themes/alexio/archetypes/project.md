---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
description: ""
tags: []
categories: []
project:
    status: DEV
    github: 
    url: 
---
# {{< params Title >}}
{{< project {{< params project >}} >}}