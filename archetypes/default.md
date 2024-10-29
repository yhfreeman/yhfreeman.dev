---
title: "{{ replace .Name "-" " " | title }}"
date: {{ if .Date }}{{ .Date }}{{ else }}2024-10-28T00:00:00Z{{ end }}
draft: true
---
