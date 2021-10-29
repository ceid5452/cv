
   
### Filiopoulou Dionysia ceid5452
_______________________ 

### Personal Information

{% for p in site.data.personal_details.personal_details %} 
<dl>
<dt> Name: </dt>
<dd> {{p.name}} </dd> 
<dt> Email: </dt>
<dd> {{p.email}} </dd> 
<dt> Github Link: </dt> 
<dd> https://{{p.link}} </dd>
</dl>
{% endfor %}
 
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
