+++
title = "Projects"
description = "My projects"
sort_by = "date"
paginate_by = 15
+++

{% admonition(type="info", title="Info about the listed projects") %}
Not all my projects are listed here, only public ones.
{% end %}

{{ projects(path="data.toml", format="toml") }}
