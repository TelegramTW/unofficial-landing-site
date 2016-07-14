{% assign groups = include.groups %}
{% for g in groups %}
{{ forloop.index0 }}. [{{ g.title }}]({{ g.link }}){% if g.description %}{{ g.description | prepend: " - " }}{% endif %}
{% if g.note %}<br />

    {{ g.note | strip | newline_to_br }}<br /><br />

{% endif %}
{% endfor %}