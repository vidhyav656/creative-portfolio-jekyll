---
layout: post
title: Installation
image: img/install.jpg

---
I assume you have already downloaded and installed Ruby. Here's what you need to do next:

1. Run <code>gem install jekyll bundler</code>.
2. Copy the theme in your desired folder.
<!--more-->
3. Enter into the folder by executing <code>cd name-of-the-folder</code>.
4. Run <code>bundle install</code>.
5. If you want to access and customize the theme, use <code>bundle exec jekyll serve</code>. This way it will be accessible on <code>http://localhost:4000</code>.
6. Upload the content of the compiled <code>_site</code> folder on your host server.