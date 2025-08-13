---
layout: default
---
# People
### Faculty
{% for person in site.data.people.faculty %}
{% include headshot.html img=person.img name=person.name position=person.position academia=person.academia scholar=person.scholar orcid=person.orcid github=person.github linkedin=person.linkedin %}
{% endfor %}
### Current Students
<div class="grid">
{% for person in site.data.people.students %}
{% assign thismod = forloop.index | modulo: 4 %}
{%- if thismod == 0 -%}
</div>
<div class="grid">
{%- endif -%}
{% include headshot.html img=person.img name=person.name position=person.position academia=person.academia scholar=person.scholar orcid=person.orcid github=person.github linkedin=person.linkedin %}
{% endfor %}
</div>

### Graduated Students
<ul>
{% for person in site.data.people.graduated %}
<li>
{{ person.name }}, {{ person.program }}, {{ person.timeline }} {% include socials.html academia=person.academia scholar=person.scholar orcid=person.orcid github=person.github linkedin=person.linkedin %}
</li>
{% endfor %}
</ul>

### Previous REU Students
<ul>
{% for person in site.data.people.previous_reu %}
<li> 
{{ person.name }}, {{ person.program }}, {{ person.timeline }} {% include socials.html academia=person.academia scholar=person.scholar orcid=person.orcid github=person.github linkedin=person.linkedin %}
</li>
{% endfor %}
</ul>