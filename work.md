---
layout: page
title: Work
permalink: /work/
---
Here you have, my list of cases, all arranged in a single collection called case studies:

<nav>
    <ul>
        {% for casestudies in site.casestudies %}
        <li>
            <a href="{{site.baseurl}}/casestudies/{{casestudies.slug}}/" class="{%if page.url contains casestudies.slug %}current{% endif %}">{{casestudies.title}}</a>
        </li>
        {% endfor %}
    </ul>
</nav>


