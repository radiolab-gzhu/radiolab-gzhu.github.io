---
nav: true
nav_order: 2
layout: default
permalink: /recent activity
title: recent activity
description: recent activity of our lab
---
<div class="activity-list">
  <ul class="activity-list">
    {% for activity in site.data.activity %}
      <li class="activity-list-item">
        <a href="{{ activity.url }}"> {{ activity.title }} </a>
      </li>
    {% endfor %}
  </ul>
</div>
