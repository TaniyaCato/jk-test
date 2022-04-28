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
    <!-- page content -->
    <main class="page-content" role="main">
      <p> Feel free to reach out to me for an questions about sketching </p>
    </main>
    <!-- page footer -->
    {% include footer.html %}
  </div>
  {% include scripts.html %}
</body>

