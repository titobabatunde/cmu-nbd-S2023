---
title: Sessions
nav:
  order: 2
  tooltip: 3D printing, rock climbing, and more
---

# <i class="fa-solid fa-chalkboard-user"></i>Sessions


<p style="text-align:center">Come learn about biomechanics through fun sessions!</p>

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="tools" filters="group: featured" %}

{% include section.html %}

## More

{% include list.html component="card" data="tools" filters="group: more" style="small" %}
<!-- 
Built with <a href="https://github.com/greenelab/lab-website-template">Lab Website  in _includes/footer.html 

{%- capture text -%}
  See {{ page.name | default: page.title }}'s papers on the Research page
{%- endcapture -%}
in _layouts/member.html
-->