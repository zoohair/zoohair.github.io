# Personal landing page. Based on the Jekyll theme [landing-page bootstrap theme ](http://startbootstrap.com/templates/landing-page/)

## How to use
 - Place images `/img/projects/`
 - Create posts in _posts with the following layout

```txt
---
layout: default
img: img.gif
category: projects
title: Awesome project<br>Year
description: |
  <p class="lead">description</p>
links: #List of links
  - title: title on page
    url: href

venue: where was this?
authors: who did this?
---

```

To run locally:
```
#Install tools
brew install ruby
gem install bundler
bundle install #run in local folder
#Add this in bashrc
export LC_ALL="en_US.UTF-8"
export LANG="en_US.UTF-8"
#Serve locally. Should be available on http://localhost:4000/
bundle exec jekyll serve
```
