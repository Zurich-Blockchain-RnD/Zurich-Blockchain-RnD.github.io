---
title: Insurance
layout: default
folder: https://github.com/Zurich-Blockchain-RnD/insurance
thumbnail: /assets/img/blog/getStarted/Do-not-delete.png
responsible:
        link: https://github.com/TammyStar
        name: TammyStar
description: Here goes the description of the Insurance project. This will be shown also on the Get Projects page.
---

<section>
    <div class="container">
        <div class="project-single">
            <div class="row project-single-text margin-30px-tb">
                <div class="col-lg-7 col-md-12">
                    <div class="section-heading half left">
                        <h4>{{ page.title }}</h4>
                    </div>
                    <p>{{ page. description }}</p>
                </div>
                <div class="col-lg-4 col-md-12 offset-lg-1">
                    <div class="section-heading half left">
                        <h6>Project Information</h6>
                    </div>
                    <div class="project-single-info">
                        <ul class="no-margin">
                            <li><span class="vertical-align-top">Status:</span> <span class="value">Ongoing</span></li>
                            <!--<li><span class="vertical-align-top">Started:</span> <span class="value">{{ page.date | date_to_long_string }}</span></li>-->
                            <li><span class="vertical-align-top">GitHub:</span> <span class="value"><a href="{{ page.folder }}">link</a></span></li>
                            <li><span class="vertical-align-top">Responsible:</span> <span class="value"><a href="{{ page.responsible.link }}">{{ page.responsible.name }}</a></span></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="row margin-50px-bottom sm-margin-30px-bottom">
              <div class="col-12">
              {% highlight html %}

              Insert your code here
              {% endhighlight %}
              <p>Than normal paraghraph</p>
              <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. </p>
              {% highlight html %}

              other code ...
              {% endhighlight %}
            </div>
          </div>
        </div>
     </div>
</section>
