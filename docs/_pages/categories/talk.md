 ---
  title: "talk"
  layout: archive
  permalink: categories/just
  author_profile: true
  sidebar_main: true  
  
  ---
  
  {% assign posts = site.categories.just %}
  {% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
