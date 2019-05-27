---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
<!-- Custom JavaScript files set in YAML front matter -->
{% for js in page.customjs %}
<script async type="text/javascript" src="{{ js }}"></script>
{% endfor %}
---

