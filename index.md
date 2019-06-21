---
layout: default
---

# Make @ the MILL!

> Workshop offered as part of [Idaho 4-H State Teen Association Convention](http://www.uidaho.edu/extension/4h/events/stac),
> hosted by [University of Idaho Library's](http://www.lib.uidaho.edu/) the [MILL](http://mill.lib.uidaho.edu/).
> June 2016, 2017, 2018, & 2019

{% include image.html file="stac_2019.jpg" alt="2019 STAC logo: we are idaho's future" %}

Join us for a hands-on session in The MILL, UI Library's Making, Innovating, and Learning Laboratory! 

This workshop will provide an opportunity to engage with emerging technologies that offer the stepping stones for solving real world challenges of the future. 
Explore The MILL’s many resources, including tools for fabricating and printing (3-D printer and vinyl cutter); open source electronic-based tools for coding and programming (Arduino, Raspberry Pi, and Makey Makey); and tools for virtual and augmented reality (Google cardboard, View-Master, and Leap Motion). 
Use your creativity and curiosity to collaborate with peers on a simple electronics-based project using Arduino to explore engineering and technology.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

{% include figure.html img="ui_library_horizontal.png" alt="UIdaho Library logo" width="50%" %}

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
