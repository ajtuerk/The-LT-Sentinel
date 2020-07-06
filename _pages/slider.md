---
title: "Slides"
layout: default
permalink: "/slides.html"
---
<div class="container">
<div class="row justify-content-center">
    <div class="col-md-8">        
        <div class="row align-items-center mb-5">
            <div class="col-md-9">
                <h2 class="font-weight-bold">{{page.title}}</h2>    
            </div>
            <div class="col-md-3 text-right">
                <img alt="{{ site.authors.joe.name }}" src="{{site.baseurl}}/{{ site.authors.joe.avatar }}" class="rounded-circle" height="100" width="100">
            </div>
        </div>
        <h4 class="font-weight-bold spanborder"><span>Posts by {{page.title}}</span></h4>
            {% for slide in site.slider %}
                <a href="{{site.baseurl}}{{slide.url}}">
                    <h2>{{ slide.name }}</h2>
                    <p>{{ slide.content | markdownify }}</p>
                </a>
            {% endfor %}
    </div>
</div>
</div>
<!-- ---
name: The first slider post!
directory: /assets/images/
author: Alex
category: Local
images:
  - "1.jpg"
  - "1.jpg"
  - "1.jpg"
--- -->
