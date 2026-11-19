+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = '{{ .Date }}'
draft = true
tags = ['photos']
summary = ''

# Optional captions:
# [[resources]]
#   src = 'photos/IMG_0001.jpg'
#   title = 'Caption text'
+++

Copy your photos into the photos/ folder next to this file.

{{< gallery match="photos/*" >}}
