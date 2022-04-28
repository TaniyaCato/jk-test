---
layout: default 
title: Welcome To My Site Sketchers
descprition: This is my site 
---
## Sketched By Taniya 

Displaying the site title: {{ site.title }}

<!DOCTYPE html>
<html lang="{{ site.lang | slice: 0,2 | default: "en" }}">
{% include head.html %}
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    {% seo %}

    <link rel="alternate" type="application/rss+xml" title="{{ site.title }}"
        href="{{ '/feed.xml' | relative_url }}">

    {% include head/favicon.html %}
    {% include head/styles.html %}
</head>
© 2022 GitHub, Inc.

<body>
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