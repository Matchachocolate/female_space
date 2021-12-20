---
layout: default
---

<div class="row">
     <div class="column">
         <div class="card">
            {% for exhibit in site.exhibits %}
            <img src= "{{ exhibit.image-url }}" style="width: 50px;">
            <div class="container">
                <h2>{{ exhibit.name }}</h2>
            </div>
            {% endfor %}
        </div>
    </div>
 </div>

