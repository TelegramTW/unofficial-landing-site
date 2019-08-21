---
layout:     page
title:      聊天群組
permalink:  /AllGroups
list_off:   true
---

<div class="container-fluid">
  <div class="row">
    {% for g in site.data.groups %}
    <a name="{{ g.anchor }}"></a>
    <div class="col-xs-12">
      <div class="bs-callout bs-callout-danger">
        <h4>{{ g.section }}</h4>
        <p>
          {% if g.prepend_markdown %}{{ g.prepend_markdown | markdownify }}{% endif %}
          {% if g.subgroups %}
            {% for sgs in g.subgroups %}
            <div class="bs-callout bs-callout-info">
              {% capture lg %}
#### {{ sgs.title }}

{% include list_groups.md groups=sgs.groups sgs=sgs %}
              {% endcapture %}
              {{ lg | markdownify | remove: '<p>' | remove: '</p>' }}
            </div>
            {% endfor %}
          {% endif %}
          {% unless g.subgroups %}
            {% capture lg %}
{% include list_groups.md groups=g.groups %}
            {% endcapture %}
            {{ lg | markdownify | remove: '<p>' | remove: '</p>' }}
          {% endunless %}
          {% if g.append_markdown %}{{ g.append_markdown | markdownify }}{% endif %}
        </p>
      </div>
    </div>
    {% endfor %}
  </div>
</div>
