{% assign sgs = include.sgs %}
{% assign groups = include.groups %}
{% if sgs.prepend_markdown %}{{ sgs.prepend_markdown | markdownify }}{% endif %}
{% for g in groups %}
{{ forloop.index0 }}. [{{ g.title }}]({{ g.link }}){% if g.description %}{{ g.description | prepend: " - " }}{% endif %}
{% if g.note %}<br />

    {{ g.note | strip | newline_to_br }}<br /><br />

{% endif %}
{% endfor %}
{% if sgs.append_markdown %}{{ sgs.append_markdown | markdownify }}{% endif %}