---
layout: default
title: Welcome Sketchers
description: This is my home page 
---

# Welcome To My Site Sketchers 

<div class="home-page">
  <!-- home page header -->
  <section class="home-page-header">
    <div class="container text-center">
      <h1 class="animated fadeInDownBig">{{ page.title | default: 'HOME' }}</h1>
      <p class="lead">{{ page.excerpt | default: 'Excerpt' }}</p>
      {%- if page.action -%}
        {%- include home-action-btn.html action_btn=action_btn dropdown=dropdown dropdown_items=dropdown_items -%}
      {%- endif -%}
    </div>
  </section>