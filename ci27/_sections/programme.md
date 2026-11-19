## Programme {#programme}

The detailed programme will be published.

{% comment %}
Hidden for now. To show it, delete the "comment" line above, this line and the "endcomment" line below.
<div class="ci27-agenda">
{% for day in page.ci27.agenda %}
  <div class="ci27-day">
    <div class="ci27-day__head"><span class="ci27-day__name">{{ day.day }}</span><span class="ci27-day__date">{{ day.date }}</span></div>
    {% if day.items.size > 0 %}<ul class="ci27-day__items">{% for item in day.items %}<li><span class="ci27-day__time">{{ item.time }}</span> {{ item.title }}</li>{% endfor %}</ul>{% else %}<p class="ci27-tba">To be announced</p>{% endif %}
  </div>
{% endfor %}
</div>
{% endcomment %}
