8:59
<ul>
{% for member in site.data.song %}
  <li>{{ member.Track }}</li>
  <li>{{ member.Duration }}</li>
  <li>{{ member.Album }}</li>
  <li>{{ member.Artist }}</li>
  <li>{{ member.Year }}</li>
  <li>{{ member.Label }}</li>
  <li>{{ member.Lyrics }}</li>
  {% for singer in member.Singers %}
  <ul>
    <li>{{ singer.singer }}</li>
  {% endfor %}
  </ul>
{% endfor %}
</ul>
