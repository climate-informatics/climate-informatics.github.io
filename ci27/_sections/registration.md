## Registration {#registration}

The registration deadline is **9 April 2027**. Opening date, fees and what is included will be
announced here.

{% comment %}
Hidden for now. To show it, delete the "comment" line above, this line and the "endcomment" line below.
| Category | Early registration | Regular registration |
|----------|--------------------|----------------------|
{% for f in page.ci27.fees %}| {{ f.category }} | {% if f.early == "TBA" %}*TBA*{% else %}{{ f.early }}{% endif %} | {% if f.regular == "TBA" %}*TBA*{% else %}{{ f.regular }}{% endif %} |
{% endfor %}{: .ci27-fees}

{% if page.ci27.registration_url != "" %}[Register]({{ page.ci27.registration_url }}){: .btn .btn--primary .btn--large}{% else %}<span class="btn btn--large ci27-btn-disabled">Registration opening soon</span>{% endif %}
{: .ci27-cta}
{% endcomment %}
