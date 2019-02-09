---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /
header:
  image: /assets/img/home-header.jpg
tagline: > # this means to ignore newlines until "repository:"
  See my tutorials and projects.
excerpt: >
  See my tutorials and projects.
repository:
  # is_project_page: true
  # show_downloads: false
  # repository_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog
  # zip_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.zip
  # tar_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.tar.gz
ref: home
lang: en
---

Look at the latest articles and projects!

<h2>Latest Articles</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" %}

---

<h2>Latest Projects</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="projects" max=3 %}
