---
title: Female in Space
layout: index_layout
---

  <div class="timeline">
        <div class="container left">
            <div class="content">
              <h2>Anna Lee Fisher</h2>
              <p>First mother in space</p>
            </div>
        </div>
    <div class="container right">
        <div class="content">
        <ul>
              {% for astronaut in site.astronauts %}

               <img src="https://images-assets.nasa.gov/image/S92-40463/S92-40463~medium.jpg" width = 100>
               <p><a href="{{ astronaut.url }}">{{ astronaut.name }}</a></p>
               <p>{{ astronaut.record }}</p>

              {% endfor %}
        </ul>
      </div>
    </div>