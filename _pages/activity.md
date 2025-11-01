---
nav: true
nav_order: 2
layout: default
permalink: /recent activity
title: activity
description: recent activity of our lab
---

<section class="activity-section">
  <h2 class="activity-title">Activity</h2>
  <div class="activity-list-wrapper">
    <div class="activity-list">
      <ul class="activity-list">
        {% for activity in site.data.activity %}
          <li class="activity-list-item">
            <a href="{% link {{ activity.path }} %}">{{ activity.title }}</a>
          </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</section>
