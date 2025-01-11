+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
image = //via.placeholder.com/640x150
alt_text = '{{ replace .Name "-" " " | title }} screenshot'
summary = "summary of the {{ replace .Name "-" " " | title }} project"
tech_used = ['JavaScript', 'CSS', 'HTML']
+++

description of the {{ replace .Name "-" " " | title }} project...
