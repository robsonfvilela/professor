+++
date = '{{ .Date }}'
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
draft = false
weight = 10
[params]
  author = 'John Smith'
+++