---
layout: archive
#title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% assign cv_path = '/files/Murad_Zeynalli_CV.pdf' | relative_url %}
{% assign cv_version = site.github.build_revision | default: 'latest' %}

You can [open or download my CV]({{ cv_path }}).

<iframe
  src="{{ cv_path }}?v={{ cv_version }}"
  title="Murad Zeynalli CV"
  width="100%"
  height="800"
  style="border: 0;"
>
  <p>Your browser cannot display the PDF. <a href="{{ cv_path }}">Open or download my CV</a>.</p>
</iframe>

<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  



<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
