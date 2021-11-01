## Filiopoulou Dionysia ceid5452
### Personal Information

{{cv.site.personal.name }}
{{cv.site.personal.email }}
_______________________

{% for item in cv.site.personal.urls %}
[{{item.link}}](http://{{ item.link }})<br>
{% endfor %}

_______________________

### Education

{% for edu in cv.site.education.education %}
{{edu.years}}<br>
**{{edu.subject}}**<br>
{{edu.diplomaThesis}}<br> 
{{edu.institute}}<br> 
*{{edu.city}}*<br> <br>
{% endfor %}

_______________________

### Expirenece

{% for exp in cv.site.experience.experience %}
    {{exp.years}}<br> 
    **{{exp.job}}**<br> 
    {{exp.company}}<br> 
    {{exp.company}}<br> 
   [{{exp.employer}}](http://{{ exp.link }})<br> 
    *{{exp.city}}*<br> 
{% endfor %}

_______________________

### Conferences

{% for conf in cv.site.conferences.conferences %}
   {{conf.years}}<br> 
   **{{conf.event}}**<br> 
   {{conf.city}}<br> 
{% endfor %}

_______________________

### Languages

**Greek:** {{cv.site.languages.greek }}<br>
**English:** {{cv.site.languages.english }}<br>
**French:** {{cv.site.languages.french }}<br>


_______________________
