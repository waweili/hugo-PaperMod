+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date | dateFormat "2006-01-02" }}
featured_image = "/basic.png"
tags = ['tag1']
draft = true
+++
