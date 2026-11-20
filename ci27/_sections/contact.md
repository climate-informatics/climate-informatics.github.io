## Contact {#contact}

For questions about CI 2027, contact the organizing committee:
{% for c in page.ci27.contacts %}
- **{{ c.name }}**: [{{ c.email }}](mailto:{{ c.email }}){% endfor %}

To write to all of us at once, use [this link](mailto:{{ page.ci27.contacts | map: "email" | join: "," }}).