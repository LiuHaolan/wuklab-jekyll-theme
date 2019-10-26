## Installation and Usage

install jekyll by:
https://jekyllrb.com/docs/installation/ubuntu/

install bundle
```
bundle install
```

After making your modifies,
build and run your website in localhost by:
```
bundle exec jekyll server
```
Then visit localhost:4000 in your explorer

replace _site directory with wuklab.github.io

Visit a new Wuklab!


## How to use
 - Place a image in `/img/portfolio/`
 - Replace `your-email@domain.com` in `_config.yml` with your email address. Refer to [formspree](http://formspree.io/) for more information.
 - Create posts to display your projects. Use the follow as an example:
```txt
---
layout: default
modal-id: 1
date: 2014-07-18
img: cabin.png
alt: image-alt
project-date: July 2014
client: The Client
category: Web Development
description: The description of the project

---
```
