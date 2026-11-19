## Invited speakers {#speakers}

<div class="ci27-speakers">
{% for s in page.ci27.speakers %}
  <div class="ci27-speaker">
    {% if s.photo %}<img class="ci27-speaker__photo" src="{{ s.photo | relative_url }}" alt="{{ s.name }}">{% else %}<div class="ci27-speaker__photo ci27-speaker__photo--empty"><i class="fas fa-user" aria-hidden="true"></i></div>{% endif %}
    {% if s.name == "TBA" %}<p class="ci27-speaker__name ci27-tba">To be announced</p>{% elsif s.url %}<p class="ci27-speaker__name"><a href="{{ s.url }}">{{ s.name }}</a></p>{% else %}<p class="ci27-speaker__name">{{ s.name }}</p>{% endif %}
    {% if s.affiliation %}<p class="ci27-speaker__affiliation">{{ s.affiliation }}</p>{% endif %}
  </div>
{% endfor %}
</div>
