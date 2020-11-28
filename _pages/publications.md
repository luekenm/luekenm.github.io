---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* *Poster*

    Lueken, M., Nguyen, J., Riebschleger, K., Hunt, S., Pike, S. T., Nybo, S. E., 2020 West Michigan Regional Undergraduate Science Research Conference, "BIOPOLYMER®: BIOBricks POLYketide Metabolic EngineeRing of minimal polyketide synthases," (2020).
