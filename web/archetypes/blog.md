---
title: "{{ .Date | dateFormat "2006-01-02" }}"
date: {{ .Date }}
# set publishDate if to be published at a later time
publishDate: {{ .Date | dateFormat "2006-01-02" }}
students: []
categories: ["blog"]
# [event], spotlight, etc
posts: []
draft: true
---

