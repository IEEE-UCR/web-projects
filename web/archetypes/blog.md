---
title: "{{ .Date | dateFormat "2006-01-02" }}"
date: {{ .Date }}
# set publishDate if to be published at a later time
publishDate: {{ .Date | dateFormat "2006-01-02" }}
students: []
categories: ["blog"]
# [event], spotlight, etc
posts: []
sticky: false
stickyEnd: {{ now.AddDate 0 1 0 | dateFormat "2006-01-02" }}
draft: true
---

