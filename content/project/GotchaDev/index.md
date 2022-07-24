---
title: GotchaDev - Full Stack Web Development · ReactJS
summary: A social networking web application. https://gotchadev.surge.sh/
tags:
  - Web Development and Design
date: '2022-05-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 'GotchaDev'
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
GotchaDev is a facebook-like social networking web application.
GotchaDev exploited React and Redux to construct front-end, realized client-server communication by RESTful APIs, 
implemented back-end by Node.js and MongoDB. The E2E test and unit test used Jest and Enzyme to achieved 80% test coverage.

GotchaDev provides following functionality:
1. users can register a new account or log in with third party authentications. The password is hashed and salted.
{{< figure src="third-party.png" title="screenshot of third-party login" >}} 
2. Display user feed. Users can post and comment articles, and follow other users.
{{< figure src="post.png" title="screenshot of GotchaDev user feed" >}} 
3. Users can customize the profile
{{< figure src="profile-update.png" title="screenshot of customizing profile" >}} 
