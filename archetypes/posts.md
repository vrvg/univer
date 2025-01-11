+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
author = 'vange'
year = '{{ dateFormat "2006" .Date }}'
month = '{{ dateFormat "2006/01" .Date }}'
categories = ['personal', 'thoughts']
tags = ['software', 'html']
+++

lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

<!--more-->

ut enum ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.