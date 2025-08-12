---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% assign cv = site.data.cv %}

Education
======
{% for edu in cv.education %}
* {{ edu.studyType }} in {{ edu.area }}, {{ edu.institution }}, {{ edu.startDate | date: "%Y" }} - {{ edu.endDate | date: "%Y" }}
  {% if edu.gpa %}  
  GPA: {{ edu.gpa }}  
  {% endif %}
  {% if edu.advisor %}  
  Advisor: {{ edu.advisor }}  
  {% endif %}
  {% if edu.thesis %}  
  Thesis: {{ edu.thesis }}  
  {% endif %}
  {% if edu.degreeProject %}  
  Degree Project: {{ edu.degreeProject }}  
  {% endif %}
{% endfor %}

Work experience
======
{% for job in cv.work %}
* {{ job.startDate | date: "%Y-%m" }} - {{ job.endDate }}: {{ job.position }}
  * {{ job.company }}, {{ job.location }}
  * {{ job.summary }}
{% endfor %}

Awards
======
{% for award in cv.awards %}
* {{ award.title }}, {{ award.awarder }}, {{ award.date | date: "%Y" }}
  * {{ award.summary }}
{% endfor %}

Editorial Activities
======
{% for ed in cv.editorial %}
* {{ ed.role }}, {{ ed.journal }}, {{ ed.date }}
{% endfor %}

Teaching
======
{% for teach in cv.teaching %}
* {{ teach.course }}, {{ teach.institution }}, {{ teach.date | date: "%Y" }}
  * {{ teach.role }}
  * {{ teach.description }}
{% endfor %}

Projects
======
{% for proj in cv.portfolio %}
* {{ proj.name }} ({{ proj.date | date: "%Y-%m" }})
  * {{ proj.description }}
{% endfor %}

Publications
======
{% for pub in cv.publications %}
* {{ pub.name }}
  * {{ pub.publisher }}, {{ pub.releaseDate | date: "%Y-%m" }}
  * Authors: {{ pub.authors | join: ", " }}
  * [Link]({{ pub.website }})
  * {{ pub.summary }}
{% endfor %}
