## Experience

<ul style="margin:0 0 5px; list-style: none; padding-left: 0;">
  {% for link in site.data.experience.main %}
  <li>
    <img src="{{ link.logo }}" alt="{{ link.employer }}" style="float:left;padding-right:1.5rem;padding-top:0.5rem;height:60px" />
    <big><a href="{{ link.url }}"><b>{{ link.employer }}</b></a></big> <span style="float:right;"> {{ link.location }} </span>
    <br>
    <strong>{{ link.title }}</strong> <span style="float:right;"> {{ link.time }} </span>
    <br>
    {{ link.duties }}
  </li>
  <br>
  {% endfor %}
</ul>

