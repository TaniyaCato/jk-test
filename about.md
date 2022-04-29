---
layout: about
title: Contact
description: Get to know me!
---


<head>
<div class="home-page">
  <!-- home page header -->
  <section class="home-page-header">
    <div class="container text-center">
      <h1 class="animated fadeInDownBig">{{ page.title | default: 'HOME' }}</h1>
      <p> Need To Get In Touch? </p>
      {%- if page.action -%}
        {%- include home-action-btn.html action_btn=action_btn dropdown=dropdown dropdown_items=dropdown_items -%}
      {%- endif -%}
</head>
    </div>
  </section>
<body>
<!-- Create a Loop -->
    {% for block in site.date.news.story %}
    <div class="cards">
    <div class="card">
        <div class="pic">
        <img src="{{block.image}}" alt="{{block.image-alt}}">
        </div>
    <div class="content">
    <h3 class="title">{{block.title}}</h3>
    <h4>{{block.subtitle}}</h4>
    <p>{{block.story-content}}</p>
    <p><a href="{{block.tag-link}}">{{block.tag}}</a></p>
    </div>
    </div>
    </div>
    {% end for %}
<!-- End of Loop -->
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
    <!-- page content -->
    <main class="page-content" role="main">
      <p> Feel free to reach out to me for an questions about sketching</p>
    </main>
    {% for block in site.date.news.story %}
    
    

    <!-- page footer -->
    {% include footer.html %}
  </div>
  {% include scripts.html %}
</body>

