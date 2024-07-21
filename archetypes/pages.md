---
{{ $file_components := split .File.ContentBaseName `-`}}
title:  '{{ delimit $file_components " " | title }}'
slug:   '{{ delimit $file_components "-" }}'
---
