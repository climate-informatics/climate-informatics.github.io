## Registration {#registration}

Registration will open in early 2027. The registration fee is expected to be between €400 and
€500 per accepted contribution; the final amount and what it includes will be announced when
registration opens. Please note that a registration fee is required for each accepted paper or
extended abstract, and each contribution must be presented in person at the conference to be
included in the proceedings.

{% comment %}
Hidden for now. To show it, delete the "comment" line above, this line and the "endcomment" line below.
| Category | Early registration | Regular registration |
|----------|--------------------|----------------------|
{% for f in page.ci27.fees %}| {{ f.category }} | {% if f.early == "TBA" %}*TBA*{% else %}{{ f.early }}{% endif %} | {% if f.regular == "TBA" %}*TBA*{% else %}{{ f.regular }}{% endif %} |
{% endfor %}{: .ci27-fees}

{% if page.ci27.registration_url != "" %}[Register]({{ page.ci27.registration_url }}){: .btn .btn--primary .btn--large}{% else %}<span class="btn btn--large ci27-btn-disabled">Registration opening soon</span>{% endif %}
{: .ci27-cta}
{% endcomment %}
