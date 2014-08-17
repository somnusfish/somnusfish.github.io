---
layout: post-index
title: Some Tips
excerpt: "A List of Posts"
---
<ul>
    {% for tag in site.tags %}    
      <li><a href="/tags/{{ tag[0] }}">{{ tag[0] }}</a></li>
    {% endfor %}
</ul>
