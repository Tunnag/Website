---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "cover.*"   # put a cover image next to this index.md (any extension)
show_cover: true   # show/hide the cover image on the project page
tags: []
summary: ""        # optional; if empty we'll take .Summary
---

Write a 1–2 sentence summary that will appear on the card.
<!--more-->

Now add the full project details here (images, code, etc.).
