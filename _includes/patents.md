## Patents

<ul style="margin:0 0 5px;">
  {% for link in site.data.patents.main %}
  <li>
    <a href="{{ link.url }}">{{ link.title }}</a>: {{ link.description }}
  </li>
  <br>
  {% endfor %}
</ul>

