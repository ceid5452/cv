## Filiopoulou Dionysia ceid5452

{{site.data.personal.name }}
{{site.data.personal.email }}
_______________________

{% for item in site.data.personal.urls %}
[{{item.link}}](http://{{ item.link }})<br>
{% endfor %}

_______________________

### Education

{% for edu in site.data.education.education %}
{{edu.years}}<br>
**{{edu.subject}}**<br>
{{edu.diplomaThesis}}<br> 
{{edu.institute}}<br> 
*{{edu.city}}*<br> <br>
{% endfor %}

_______________________

## Expirenece

{% for exp in site.data.experience.experience %}
    {{exp.years}}<br> 
    **{{exp.job}}**<br> 
    {{exp.company}}<br> 
    {{exp.company}}<br> 
   [{{exp.employer}}](http://{{ exp.link }})<br> 
    *{{exp.city}}*<br> 
{% endfor %}

_______________________

### Conferences

{% for conf in site.data.conferences.conferences %}
   {{conf.years}}<br> 
   **{{conf.event}}**<br> 
   {{conf.city}}<br> 
{% endfor %}

_______________________

### Languages

**Greek:** {{site.data.languages.greek }}
**English:** {{site.data.languages.english }}
**French:** {{site.data.languages.french }}


_______________________
