---
date:  '{{ .Date }}'
{{ $file_components := split .File.ContentBaseName `-` | after 2 -}}
title: '{{ delimit $file_components " " | title }}'
slug:  '{{ delimit $file_components "-" }}'
---
