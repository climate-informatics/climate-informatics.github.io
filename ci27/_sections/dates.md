## Important dates {#dates}

<div class="ci27-timeline">
{% for d in page.ci27.dates %}
  <div class="ci27-timeline__item{% if d.highlight %} ci27-timeline__item--key{% endif %}">
    <span class="ci27-timeline__date">{{ d.date }}</span>
    <span class="ci27-timeline__label">{{ d.label }}</span>
  </div>
{% endfor %}
</div>

Deadlines are at 23:59 Anywhere on Earth (AoE) unless stated otherwise.
{: .ci27-note}
