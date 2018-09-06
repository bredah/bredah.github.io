---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /pt
header:
  image: /assets/img/home-header.jpg
tagline: > # this means to ignore newlines until "repository:"
  Aqui é onde compartilhar os meus estudos, tutoriais, etc. Caso queira entrar 
  em contato, utilize as redes socias abaixo!
excerpt: >
  Aqui é onde compartilhar os meus estudos, tutoriais, etc. Caso queira entrar 
  em contato, utilize as redes socias abaixo!
# repository:
#   is_project_page: true
#   show_downloads: false
#   repository_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog
#   zip_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.zip
#   tar_url: https://gitlab.com/lorepirri/jekyll-theme-simple-blog/repository/master/archive.tar.gz
ref: home
lang: pt
---

Acesse aqui os últimos projetos e artigos escritos!

<h2>Últimos Artigos</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" %}

---

<h2>Últimos Projetos</h2>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="projects" max=3 %}
