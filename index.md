---
layout: home
title: CE3201
nav_exclude: true
seo:
  type: Course
  name: Civil Engineering Analytics and Data Visualization
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign overview = site.slides | where: "title", "Overview" | first %}
{{ overview.content }}

CE3201 is about data analytics and visualization. Add more description here.  

<small>[Read more...]({{ site.baseurl }}{% link syllabus.md %})</small>

[Find Zoom Links, Recordings, and Slides on LumiNUS](https://luminus.nus.edu.sg){: .btn .btn-blue }

{% for module in site.modules %}
{{ module }}
{% endfor %}

![Image of NUS Campus](./assets/images/NUS-campus.svg)

**This website is in progress and all content is subject to change.**{: .text-grey-dk-000 }
