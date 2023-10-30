## Education

<ul style="margin:0 0 5px; list-style: none; padding-left: 0;">
  {% for link in site.data.education.main %}
  <li>
    <img src="{{ link.logo }}" alt="{{ link.school }}" style="float:left;padding-right:1.5rem;height:60px" />
    <big><a href="{{ link.url }}"><b>{{ link.school }}</b></a></big> <span style="float:right;"> {{ link.time }} </span>
    <br>
    <strong>{{ link.degree }}</strong> in {{ link.major }}
  </li>
  <br>
  {% endfor %}
</ul>