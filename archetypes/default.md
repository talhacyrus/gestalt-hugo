---
CUID: {{ .Date }}

type: "Default"
layout: ""

draft: true
feature: false
private: false
headless: false
highlight: false

date: {{ .Date }}
publishDate: ""
expiryDate: ""
lastmod: ""

url: ""
slug: ""
aliases: []
linkTitle: ""

series: []
title: "{{ replace .Name "-" " " | title }}"
subtitle: ""
summary: ""
description: ""

authors: ["{{ .Site.Params.defaultAuthor }}"]
authorsNoteType: ""
authorsNoteCustom: ""

tags: []
---
