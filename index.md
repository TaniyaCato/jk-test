---
layout: default 
title: Welcome To My Site Sketchers
descprition: This is my site 
---

<div class="home-page">
  <!-- home page header -->
  <section class="home-page-header">
    <div class="container text-center">
      <h1 class="animated fadeInDownBig">{{ page.title | default: 'HOME' }}</h1>
      <p class="lead">{{ page.excerpt | default: 'By: Taniya Trinidad' }}</p>
      {%- if page.action -%}
        {%- include home-action-btn.html action_btn=action_btn dropdown=dropdown dropdown_items=dropdown_items -%}
      {%- endif -%}
    </div>
  </section>
<head>
<title> Sketched By Taniya </title>
<body>
  <div class="container mt-2 mb-2">
    <div class="row">
      <div class="col-sm">
        <h1>Welcome To My Site</h1>
      </div>
    </div>
    <div class="row">
      <div class="col-sm">
        <p> Hello my name is Taniya Trinidad (like the island), most of my friends call me Niy or Niya. I am from Sicklerville, NJ and I am 23 years old. I 'm a senior at the University of Miami with a major in Criminology and a minor in Motion Pictures, with a Web Mobile Design Cognate. I have a huge interest in the criminal justice system but I also have a second interest for film, art, and design, always have. If I could combine all in the same category, I would, maybe one day I will. I love being creative and day dreaming. I have a very versatile and adventurous personality, I have a lot of interests for alot of different things. I am workout freak, shopping alcoholic, and movie fanatic, I've probably seen every movie to exist.This website is too showcase some of my favorite sketches that I did during quarantine 2020. As a lot may know the country was impacted by a deadly virus Covid 19. This virus left us stuck in our homes for months practically, with a lot of time on our hands. So what better way to take advantage of that time, then draw up a couple of fun and cute sketches.</p>
      </div>
    </div>
  </div>
  </body>
</section>

