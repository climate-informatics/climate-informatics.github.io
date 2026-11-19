---
# =============================================================================
#  CI 2027 · 16th International Conference on Climate Informatics
#  Landing page, published at /ci27/
#
#  Everything for CI 2027 lives in the ci27/ folder:
#    ci27/index.md            this page
#    ci27/assets/css/         styles used only by this page
#    ci27/assets/images/      logos and pictures
#
#  Lists that repeat (dates, speakers, programme, fees, committee) are in the
#  DATA section below. The text of each section is plain Markdown further down.
#  Anything still unknown is written as "TBA" and shown as "to be announced".
# =============================================================================
title: "Climate Informatics 2027"
excerpt: "16th International Conference on Climate Informatics<br>10–14 May 2027 · Lecce, Italy"
permalink: /ci27/
layout: splash
classes: ci27-page     # lets ci27.css style this page only
author_profile: false
share: false
search: false          # not listed in the site's internal search
# sitemap: false       # uncomment to also keep the page out of sitemap.xml
header:
  overlay_color: "#0f4c5c"
  # For a photo instead of the coloured banner, put it in ci27/assets/images/
  # and uncomment these two lines:
  # overlay_image: /ci27/assets/images/header.jpg
  # overlay_filter: "0.45"
  actions:
    - label: "Call for papers"
      url: "/ci27/#call-for-papers"
    - label: "Important dates"
      url: "/ci27/#dates"

# ----------------------------------------------------------------------------- DATA
ci27:
  # Link to the CMT submission portal. Leave empty until it exists:
  # the button then shows "opens 30 November 2026".
  submission_url: ""
  submission_opens: "30 November 2026"
  # Link to the registration platform. Leave empty until it exists.
  registration_url: ""
  contact_email: "climate.informatics.workshop@gmail.com"
  mailing_list: "https://groups.google.com/g/climate-informatics-news"

  dates:
    - label: "Abstract & paper submission opens"
      date: "30 November 2026"
    - label: "Abstract & paper submission deadline"
      date: "5 February 2027"
      highlight: true
    - label: "Notification of results"
      date: "5 March 2027"
    - label: "Camera-ready copy of full papers"
      date: "2 April 2027"
    - label: "Registration deadline"
      date: "9 April 2027"
    - label: "Conference"
      date: "10–14 May 2027"
      highlight: true

  # Indicative topics (to be confirmed with the programme committee).
  topics:
    - "Machine learning for climate and weather prediction, nowcasting and downscaling"
    - "Hybrid and physics-informed Earth-system modelling"
    - "Extremes, detection and attribution"
    - "Data assimilation, reanalysis and remote sensing"
    - "Causality, interpretability and uncertainty quantification"
    - "Climate impacts, adaptation and decision support"
    - "Datasets, benchmarks and open, reproducible science"

  # Invited speakers. Replace "TBA" entries with real ones as they are confirmed:
  #   - name: "Jane Doe"
  #     affiliation: "University of Somewhere"
  #     photo: "/ci27/assets/images/speakers/jane-doe.jpg"
  #     url: "https://..."
  speakers:
    - name: "TBA"
    - name: "TBA"
    - name: "TBA"
    - name: "TBA"

  # Programme, one entry per day. Add sessions under "items" when known:
  #   items:
  #     - time: "09:00"
  #       title: "Opening"
  agenda:
    - day: "Monday"
      date: "10 May 2027"
      items: []
    - day: "Tuesday"
      date: "11 May 2027"
      items: []
    - day: "Wednesday"
      date: "12 May 2027"
      items: []
    - day: "Thursday"
      date: "13 May 2027"
      items: []
    - day: "Friday"
      date: "14 May 2027"
      items: []

  fees:
    - category: "Students"
      early: "TBA"
      regular: "TBA"
    - category: "Academic & public research"
      early: "TBA"
      regular: "TBA"
    - category: "Industry"
      early: "TBA"
      regular: "TBA"

  committee:
    - role: "General chairs"
      members: ["TBA"]
    - role: "Programme chairs"
      members: ["TBA"]
    - role: "Hackathon chairs"
      members: ["TBA"]
    - role: "Local organising committee"
      members: ["TBA"]
    - role: "Programme committee"
      members: ["TBA"]
---

<div class="ci27-assets"><link rel="stylesheet" href="{{ '/ci27/assets/css/ci27.css' | relative_url }}"></div>

<!-- In-page menu: each link jumps to the heading with the same {#id} below -->
<div class="ci27-nav" role="navigation" aria-label="CI 2027 sections">
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#dates">Dates</a></li>
    <li><a href="#call-for-papers">Call for papers</a></li>
    <li><a href="#guidelines">Guidelines</a></li>
    <li><a href="#speakers">Speakers</a></li>
    <li><a href="#programme">Programme</a></li>
    <li><a href="#hackathon">Hackathon</a></li>
    <li><a href="#registration">Registration</a></li>
    <li><a href="#venue">Venue</a></li>
    <li><a href="#committee">Committee</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</div>

<div class="ci27-facts">
  <div class="ci27-fact"><span class="ci27-fact__label">When</span><span class="ci27-fact__value">10–14 May 2027</span></div>
  <div class="ci27-fact"><span class="ci27-fact__label">Where</span><span class="ci27-fact__value">Campus Ecotekne, Lecce</span></div>
  <div class="ci27-fact"><span class="ci27-fact__label">Submission deadline</span><span class="ci27-fact__value">5 February 2027</span></div>
</div>

## About CI 2027 {#about}

The **16th International Conference on Climate Informatics** will take place from
**10 to 14 May 2027** in **Lecce, Italy**, at the Campus Ecotekne of the University of Salento.
CI 2027 is hosted by the [Euro-Mediterranean Center on Climate Change (CMCC)](https://www.cmcc.it/)
and the [University of Salento](https://www.unisalento.it/).

Climate Informatics is an open community working at the intersection of climate science with
statistics, machine learning and data mining. Since 2011 its annual conference has brought
together researchers across these fields to share new methods, datasets and results, and to
start new collaborations.

<div class="ci27-hosts">
  <a href="https://www.cmcc.it/" class="ci27-hosts__logo"><img src="{{ '/ci27/assets/images/cmcc_logo.png' | relative_url }}" alt="CMCC – Euro-Mediterranean Center on Climate Change"></a>
  <a href="https://www.unisalento.it/" class="ci27-hosts__logo"><img src="{{ '/ci27/assets/images/unisalento_logo.png' | relative_url }}" alt="University of Salento"></a>
</div>

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

## Call for papers {#call-for-papers}

We invite contributions that bring together climate and weather science with statistics,
machine learning and data science. Indicative topics include:
{% for t in page.ci27.topics %}
- {{ t }}{% endfor %}
{: .ci27-topics}

Submissions open on **30 November 2026** and close on **5 February 2027**. Submission types,
page limits and templates will be published here when submissions open.

{% if page.ci27.submission_url != "" %}[Submit your paper]({{ page.ci27.submission_url }}){: .btn .btn--primary .btn--large}{% else %}<span class="btn btn--large ci27-btn-disabled">Submission portal opens {{ page.ci27.submission_opens }}</span>{% endif %}
{: .ci27-cta}

## Guidelines {#guidelines}

Provisional guidelines, to be confirmed when submissions open.
{: .ci27-note}

### Author guidelines

- Submissions must be written in English and submitted as PDF.
- Submission types (e.g. full papers and extended abstracts), page limits and templates: *TBA*.
- Review process: *TBA*.
- Submission portal: *TBA* (link available from 30 November 2026).
- Figures should remain readable in greyscale; colour-blind-safe palettes are recommended.
- Publication opportunities for accepted papers: *TBA*.

### Presenter guidelines

- Oral presentations: duration and format *TBA*.
- Posters: size and orientation *TBA*.
- Slides: 16:9 format recommended; how and when to upload them *TBA*.
- Remote presentation: *TBA*.

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

## Programme {#programme}

The detailed programme will be published after the notification of results (5 March 2027).

<div class="ci27-agenda">
{% for day in page.ci27.agenda %}
  <div class="ci27-day">
    <div class="ci27-day__head"><span class="ci27-day__name">{{ day.day }}</span><span class="ci27-day__date">{{ day.date }}</span></div>
    {% if day.items.size > 0 %}<ul class="ci27-day__items">{% for item in day.items %}<li><span class="ci27-day__time">{{ item.time }}</span> {{ item.title }}</li>{% endfor %}</ul>{% else %}<p class="ci27-tba">To be announced</p>{% endif %}
  </div>
{% endfor %}
</div>

## Hackathon {#hackathon}

As in previous editions, CI 2027 will include a hackathon where participants work in teams on
climate data challenges, combining domain expertise with data-science methods.

- **Date:** *TBA*
- **Challenges & data:** *TBA*
- **Sign-up:** *TBA*

## Registration {#registration}

The registration deadline is **9 April 2027**. Opening date, fees and what is included will be
announced here.

| Category | Early registration | Regular registration |
|----------|--------------------|----------------------|
{% for f in page.ci27.fees %}| {{ f.category }} | {% if f.early == "TBA" %}*TBA*{% else %}{{ f.early }}{% endif %} | {% if f.regular == "TBA" %}*TBA*{% else %}{{ f.regular }}{% endif %} |
{% endfor %}{: .ci27-fees}

{% if page.ci27.registration_url != "" %}[Register]({{ page.ci27.registration_url }}){: .btn .btn--primary .btn--large}{% else %}<span class="btn btn--large ci27-btn-disabled">Registration opening soon</span>{% endif %}
{: .ci27-cta}

## Venue & travel {#venue}

### Campus Ecotekne, University of Salento

Strada Provinciale Lecce–Monteroni, 73100 Lecce, Italy.
The campus is about 6 km from Lecce city centre. Building and rooms: *TBA*.

[Open in OpenStreetMap](https://www.openstreetmap.org/?mlat=40.334231&mlon=18.126009#map=15/40.3342/18.1260) ·
[Open in Google Maps](https://www.google.com/maps/search/?api=1&query=Campus+Ecotekne+Lecce)

<div class="ci27-map">
  <iframe title="Map of Campus Ecotekne, Lecce" loading="lazy" src="https://www.openstreetmap.org/export/embed.html?bbox=18.1050%2C40.3240%2C18.1470%2C40.3440&amp;layer=mapnik&amp;marker=40.334231%2C18.126009"></iframe>
</div>

### By plane

**Brindisi airport (BDS)** is the closest, about 40 km from Lecce. Direct buses run from the
airport to Lecce; alternatively take the shuttle bus to Brindisi railway station and a train to
Lecce (about 30 minutes).

**Bari airport (BRI)** is about 150 km away: take the train link to Bari Centrale, then a train
to Lecce.

### By train

Lecce is the southern end of the Adriatic railway line (Bologna – Bari – Lecce) and is also
reachable from Rome. Check timetables on [Trenitalia](https://www.trenitalia.com/). Most hotels
in the centre are within walking distance of the station.

### From Lecce to the campus

City bus line **S13** connects the centre with the campus (stops "Ecotekne"). Taxis are also
available. Shuttle service for participants: *TBA*.

### Accommodation

We recommend staying in Lecce's historic centre. A list of suggested hotels and any agreed
rates: *TBA*.

## Organisation {#committee}

<div class="ci27-committee">
{% for g in page.ci27.committee %}
  <div class="ci27-committee__group">
    <h3>{{ g.role }}</h3>
    <ul>{% for m in g.members %}{% if m == "TBA" %}<li class="ci27-tba">To be announced</li>{% else %}<li>{{ m }}</li>{% endif %}{% endfor %}</ul>
  </div>
{% endfor %}
</div>

## Contact {#contact}

For questions about CI 2027, write to
[{{ page.ci27.contact_email }}](mailto:{{ page.ci27.contact_email }}).

To receive announcements about the call for papers and registration, join the
[Climate Informatics mailing list]({{ page.ci27.mailing_list }}).