 ---  
 title: "computer architecture"  
 layout: archive  
 permalink: categories/study  
 author_profile: true  
 sidebar_main: true  
 type: liquid  
 ---
  
  {% assign posts = site.categories.study %}  
  {% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}  
  
