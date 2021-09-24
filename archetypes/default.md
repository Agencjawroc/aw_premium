---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
slug: "{{ $seed := .Filename }}{{ $random := delimit (shuffle (split (md5 $seed) "" )) "" }}{{ $random }}"
---

