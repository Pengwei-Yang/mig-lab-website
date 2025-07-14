---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

I didn't meet you during the best times of my life; it's meeting you that gave me the best times of my life.



Our laboratory is now hiring interns, master students, Ph.D. students, postdoctoral researchers, and engineers. Welcome to join us.


{% include section.html %}
## Faculties
{% include list.html data="members" component="portrait"
   filter="role == 'teacher'" %}

## PhD Students
{% include list.html data="members" component="portrait"
   filter="role == 'phd'" style="small" %}

## Masters Students
{% include list.html data="members" component="portrait"
   filter="role == 'master'" style="small" %}

## Alumni
{% include list.html data="members" component="portrait"
   filter="role == 'former'" style="small" %}

{% include section.html %}
