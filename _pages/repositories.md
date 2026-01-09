---
layout: page
permalink: /repositories/
title: Repositories
description: Codes released for some of my open source projects. Feel free to check them out.
nav: true
nav_order: 3
---

## GitHub Stats

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}
---

### Contribution Graph

<img src="http://ghchart.rshah.org/sn91" alt="sn91's Github chart" />

---

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
