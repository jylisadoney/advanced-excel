---
title: Home
---
# Advanced Excel

Do you want to learn advanced excel features? 

This site will get you:
- use advanced functions
- create templates
- apply conditional formatting
- utilize data verification
- create pivot tables

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> hosted by the <a href="https://www.lib.uidaho.edu/" target="_blank">University of Idaho Library</a> ({{ site.pub_year }})
>
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}}. (get [source code]({{ site.repo }}))
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
