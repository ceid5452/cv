
   
### Filiopoulou Dionysia 
_______________________ 

### Personal Information

[{{site.data.personal.page}}](http://{{ site.data.personal.page }}) -- {{site.data.personal.email }} <br/>

{% for item in site.data.personal.urls %}[{{item.link}}](http://{{ item.link }})<br>{% endfor %}

_______________________

### Education

{% for edu in site.data.education.education %}
{{edu.years}}<br>
__{{edu.subject}}__ <br>
{{edu.institute}} <br> 
*{{edu.city}}* <br> <br>
{% endfor %}

_______________________

### Languages

{% for l in site.data.languages.languages %}
{{l.langA}} :  {{l.levelA}}  
{{l.langB}} :  {{l.levelB}}
{% endfor %}

_______________________

### Conferences

{% for s in site.data.conferences.conferences %}
{{s.years}} :  {{s.years}}  
{{s.event}} :  {{s.event}}
{{s.city}}  :  {{s.city}}
{% endfor %}

_______________________
