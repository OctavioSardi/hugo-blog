+++
date = '{{ .Date }}'
draft = false
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
author = "Octavio Sardi"
tags = '{{ .Page.tags }}'
+++
