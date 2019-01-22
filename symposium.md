---
title: symposium
---

<div class="row align-items-center py-auto my-auto py-md-5 my-md-5">
    <div class="col-12 col-md col-lg-5">
        <h1 class="display-1">
            Annual Symposium
        </h1>
    </div>
    <div class="col-12 col-md">
        <hr>
        <!-- <img src="{{ "/assets/img/btba_logo.png" | absolute_url }}" alt="BTBA logo" class="float-left p-4" width="150"> -->
        <p class="">
            Our 2018 BTBA symposium is going to be held on June 2-3 at Harvard University Science Center, Cambridge, MA. The registration is opening soon. Please check our [official 2018 BTBA symposium website](http://btbatw.org/2018) for more information about our keynote speakers and career panels.
        </p>
    </div>
</div>


<hr class="mt-5 mb-4" />
## Past Symposia

<div class="row">
    {% assign years = "2018,2017,2016,2015,2014,2013" | split: ',' %}
    {% for year in years %}
    <a class="col-4 col-md-3 col-lg-2" href="http://btbatw.org/{{ year }}/">
        {% capture new_var %}{{ year }}.jpg{% endcapture %}
        <img src="{{ '/assets/img/symposium_cover/symposium_pb-' | append: new_var | absolute_url }}" alt="{{ year }} Cover">
        <h3 class="text-center btn-link">{{ year }}</h3>
    </a>
    {% endfor %}
</div>


