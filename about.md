---
layout: about
title: About me 
description: Get to know me!
---

# About Me 
!DOCTYPE html>
<html lang="{{ site.lang | slice: 0,2 | default: "en" }}">

{% include head.html %}
<head>
<div class="about-page">
  <!-- home page header -->
  <section class="about-page-header">
    <div class="container text-center">
      <h1 class="animated fadeInDownBig">{{ page.title | default: 'HOME' }}</h1>
      <p> This Page is to showcase my sketches </p>
      {%- if page.action -%}
        {%- include home-action-btn.html action_btn=action_btn dropdown=dropdown dropdown_items=dropdown_items -%}
      {%- endif -%}
</head>
    </div>
  </section>
<body>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    {% seo %}

    <link rel="alternate" type="application/rss+xml" title="{{ site.title }}"
        href="{{ '/feed.xml' | relative_url }}">

    {% include head/favicon.html %}
    {% include head/styles.html %}



  <!-- page container -->
  <div class="page-container">
    <!-- page header -->
    {% include header.html %}
    <!-- page content -->
    <main class="page-content" role="main">
      {{ content }}
    </main>
    <!-- page footer -->
    {% include footer.html %}
  </div>
  {% include scripts.html %}
</body>
</html>

