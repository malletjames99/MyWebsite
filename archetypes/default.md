---
title: "{{ replace .Name "-" " " | title }}"
date: {{ $date := .Date.Format "02.01.2006" }}
draft: true
---

