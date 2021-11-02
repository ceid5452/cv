## Filiopoulou Dionysia ceid5452
### Personal Information

**Name:** {{ site.data.personal.name }}<br>
**Email:** {{ site.data.personal.email }}<br>
**Date of Birth:** {{ site.data.personal.birthday }}<br>
**City:** {{ site.data.personal.city }}<br>
**LinkedIn link:** [{{site.data.personal.linkedin}}](http://{{ site.data.personal.linkedin }})<br> 
**GitHub link:** {{ site.data.personal.github }}<br>

_______________________

### Education

{% for edu in site.data.education.education %}
    **Period time:** {{ edu.years }}<br>
    **Subject:** {{ edu.subject }}<br>
    **Diploma Thesis:** {{ edu.diplomathesis }}<br> 
    **Institute:** {{ edu.institute }<br> 
    **City:** {{ edu.city }} <br>
{% endfor %}

_______________________

### Expirenece

{% for ex in site.data.experience.experience %}
   **Period Time:** {{ ex.years }}<br> 
   **Job Title:** {{ ex.job }}<br> 
   **Company:** {{ ex.employer }}<br> 
   **Company Link:** [{{ ex.employerlink }}](http://{{ ex.employerlink }})<br> 
   **City:** {{ exp.city }})<br> 
{% endfor %}

_______________________

### Conferences

{% for conf in site.data.conferences.conferences %}
   **Year:** {{ conf.years }}<br> 
   **Event name:** {{ conf.event }}<br> 
   **City:** {{ conf.city }}<br> 
{% endfor %}

_______________________

### Languages

**Greek:** {{ site.data.languages.greek }}<br>
**English:** {{ site.data.languages.english }}<br>
**French:** {{ site.data.languages.french }}<br>


_______________________
