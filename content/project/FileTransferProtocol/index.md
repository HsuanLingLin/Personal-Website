---
title: Reliable File Transfer Protocol · C/C++ · Socket Programming 
summary: A reliable file transfer protocol using customized UDP.
tags:
  - Database
date: '2022-03-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 'Reliable File Transfer Protocol'
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
+ Designed a reliable file transfer protocol using UDP that using only 1MB of memory to transmit files with any size.
+ Built a robust protocol by designing smart ACK response, error detection, and re-transmission mechanisms to handle unreliable network such as packet delay, drop, reorder, mangle, and duplicate.