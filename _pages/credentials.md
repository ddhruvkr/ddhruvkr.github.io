---
title: "Dhruv Kumar - Experience"
layout: gridlay
excerpt: "Dhruv Kumar: Experience"
sitemap: false
permalink: /credentials/
---

# Education

{% assign number_printed = 0 %}
{% for member in site.data.education %}

{% assign even_odd = number_printed | modulo: 2 %}



<div class="col-sm-12">
  <!--<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />-->
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>

</div>

{% assign number_printed = number_printed | plus: 1 %}



{% endfor %}


<br/>
<br/>

#  Academic Work Experience
{% assign number_printed = 0 %}
{% for member in site.data.academic_work_experience %}

{% assign even_odd = number_printed | modulo: 2 %}



<div class="col-sm-12">
  <!--<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />-->
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  <ul style="overflow: hidden">
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}



{% endfor %}


<br/>
<br/>

#  Industrial Work Experience
{% assign number_printed = 0 %}
{% for member in site.data.industrial_work_experience %}

{% assign even_odd = number_printed | modulo: 2 %}



<div class="col-sm-12">
  <!--<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />-->
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  <ul style="overflow: hidden">
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}



{% endfor %}
