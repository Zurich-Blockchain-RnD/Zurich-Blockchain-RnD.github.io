---
title: Get Started
layout: default
---

<!-- start blog section -->
<section>
    <div class="container">
      {% for post in site.categories.getStarted %}
        <div class="blog-list-simple">
            <div class="row">
                <div class="col-md-2 col-sm-12 sm-margin-20px-bottom">
                  <div class="blog-list-simple-img"><a href="{{ post.url }}" ><img alt="img" src="{{ base }}{{ post.thumbnail }}"></a>
                  </div>
                </div>
                <div class="col-md-10 col-sm-12">
                    <div class="blog-list-simple-text">
                        <h4>{{ post.title }}</h4>
                        <ul class="meta">
                          {% if post.responsible %}
                            <li>
                                <a href="{{ post.responsible.link }}">
                                    <i aria-hidden="true" class="fa fa-user"></i> Responsible
                                </a>
                            </li>
                          {% endif %}
                          {% if post.folder %}
                            <li>
                                <a href="{{ post.folder }}">
                                    <i aria-hidden="true" class="fa fa-folder-open"></i> GitHub folder
                                </a>
                            </li>
                          {% endif %}
                        </ul>
                        {% if post.description %}
                        <p> {{ post.description }}</p>
                        {% else %}
                        <p> description coming soon.</p>
                        {% endif %}
                            <div class="text-left margin-10px-top"><a href="{{ post.url }}" class="butn small"><span>Read More</span></a></div>
                    </div>
                </div>
            </div>
        </div>
      {% endfor %}
    </div>
</section>
