---
date: {{ .Date }}
title: {{ replace .Name "-" " " | title }}
type: "prestations"
draft: false
prestation_key: {{ .Name }}
---

Lorem ipsum summary of the prestation.
<!--more-->
Lorem ipsum rest of the prestation.