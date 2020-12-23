9:39
<ul>
{% for member in site.data.song %}
  <li>{{ member.Track }}</li>
  <li>{{ member.Duration }}</li>
  <li>{{ member.Album }}</li>
  <li>{{ member.Artist }}</li>
  <li>{{ member.Year }}</li>
  <li>{{ member.Label }}</li>
  <li>{{ member.Lyrics }}</li>
  <li>{{ member.Singers.singer[0] }}</li>
  </ul>
{% endfor %}
</ul>
