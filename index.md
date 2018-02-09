---
layout: default
---

{% include figure.html file="decomposition.png" alt="intro image here" width="85%" %}

# Research computing summer school

> organized by WestGrid and University of Manitoba

This event is brought to you by [WestGrid](https://www.westgrid.ca) and the [University of Manitoba ARC Department].

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | prepend: site.url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
