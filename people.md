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
    {% include headshot.html img=person.img name=person.name position=person.position academia=person.academia scholar=person.scholar orcid=person.orcid github=person.github linkedin=person.linkedin %}
{% endfor %}
</div>

### Graduated Students
- Mohammad Ahmadi, PhD, -- 2025 [LinkedIn](https://www.linkedin.com/in/mohammad-ahmadi-ba27a91a3/)
- Md Rubel Ahmed, PhD, 2018--2023 [webpage](https://rubelahmed57.github.io/)
- Hernan Palombo, PhD, 2015--2020 [webpage](https://www.linkedin.com/in/hernanpalombo)
- Yuting Cao, PhD, 2019, [webpage](https://www.linkedin.com/in/caoyuting/?ts=1576368962044&trk=profile_share_wechat&from=singlemessage&isappinstalled=0)
- Haiqiong Yao, PhD, 2010
- Laureano Griffin, MS, Fall, 2023
- Yuting Cao, MS, 2015
- Hernan Palombo, MS, 2014
- Yingying Zhang, MS, 2010
- Ryan Mabry, MS, 2006
- Jared Ahrens, MS, 2006

### Previous REU Students
{% for person in site.data.people.previous_reu %}
- {{ person.name }}, {{ person.position }}, {{ person.timeline }}
{% endfor %}