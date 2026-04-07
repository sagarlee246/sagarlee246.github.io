---
layout: page
permalink: /Repositories/
title: Repositories
description: Selected GitHub projects and profile links.
nav: true
nav_order: 3
---

## GitHub Profile

{% if site.data.repositories.github_users %}
  <p><a href="https://github.com/{{ site.data.repositories.github_users.first }}">github.com/{{ site.data.repositories.github_users.first }}</a></p>
{% endif %}

## GitHub Repositories

<div class="repo-gallery">
  <a class="repo-tile" href="https://github.com/sagarlee246/CPPJourney">
    <img class="repo-image repo-image-square" src="{{ '/assets/img/CPPlogo.png' | relative_url | bust_file_cache }}" alt="CPP Journey">
    <span>CPP Journey</span>
  </a>

  <a class="repo-tile" href="https://github.com/sagarlee246/AMAS">
    <img class="repo-image" src="{{ '/assets/img/AMAS.png' | relative_url | bust_file_cache }}" alt="AMAS">
    <span>AMAS</span>
  </a>

  <a class="repo-tile" href="https://github.com/sagarlee246/AppStat">
    <img class="repo-image" src="{{ '/assets/img/AS.png' | relative_url | bust_file_cache }}" alt="AppStat">
    <span>AppStat</span>
  </a>
</div>

<style>
  .repo-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.25rem;
    margin-top: 1rem;
  }

  .repo-tile {
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
    text-decoration: none;
    color: inherit;
  }

  .repo-image {
    width: 100%;
    min-height: 160px;
    border: 1px solid var(--global-divider-color);
    border-radius: 14px;
    background: var(--global-card-bg-color);
    object-fit: cover;
  }

  .repo-image-square {
    object-fit: contain;
    padding: 0.75rem;
  }

  .repo-tile span {
    text-align: center;
    font-weight: 600;
  }
</style>
