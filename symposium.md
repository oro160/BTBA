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
            Our annual symposiums attract more than 350 professionals and students every year from biology-related fields across the US. This two-day event is a great platform for attendees to network and engage in conversations about career development and trending topics in biotechnology. This year (2019), the symposium will be held on August 3-4 at Harvard University Northwest Science Building, Cambridge, MA. We are honored to have Dr. Seng H. Cheng, Senior Vice President and Chief Scientific Officer at Pfizer and Dr. Jenny P-Y Ting, William Rand Kenan Professor at University of North Carolina at Chapel Hill as our keynote speakers. The registration is opening soon. Please check our [2019 BTBA symposium website] for more information.   
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


