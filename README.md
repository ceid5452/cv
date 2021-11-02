## Filiopoulou Dionysia ceid5452
### Personal Information

**Name:** {{site.data.personal.name }}<br>
**Email:** {{site.data.personal.email }}<br>

_______________________

### Personal Links

{% for item in site.data.personal.urls %}
    **{{item.name}}**: http://{{ item.link }}<br>
{% endfor %}

_______________________

### Education

{% for edu in site.data.education.education %}
    **Period time:** {{edu.years}}<br>
    **Subject:** {{edu.subject}}<br>
    **Diploma Thesis:** {{edu.diplomaThesis}}<br> 
    **Institute:** {{edu.institute}}<br> 
    **City:** {{edu.city}} <br>
{% endfor %}

_______________________

### Expirenece

{% for exp in site.data.experience.experience %}
    **Period time:** {{exp.years}}<br> 
    **Job Title:** {{exp.job}}<br> 
    **Company:** {{exp.company}}<br> 
    **Company Link:** [{{exp.employer}}](http://{{exp.employer}})<br> 
    **City:** {{exp.city}}<br> 
{% endfor %}

_______________________

### Conferences

{% for conf in site.data.conferences.conferences %}
   **Year:** {{conf.years}}<br> 
   **Event name:** {{conf.event}}<br> 
   **City:** {{conf.city}}<br> 
{% endfor %}

_______________________

### Languages

**Greek:** {{site.data.languages.greek }}<br>
**English:** {{site.data.languages.english }}<br>
**French:** {{site.data.languages.french }}<br>


_______________________
