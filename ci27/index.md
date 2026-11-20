---
# =============================================================================
#  CI 2027 · 16th International Conference on Climate Informatics
#  Landing page, published at /ci27/
#
#  Everything for CI 2027 lives in the ci27/ folder:
#    ci27/index.md            this page: settings, data and the list of sections
#    ci27/_sections/          one Markdown file per section of the page
#    ci27/assets/css/         styles used only by this page
#    ci27/assets/images/      logos and pictures
#
#  To edit the text of a section, open its file in ci27/_sections/.
#  To hide or show a section (and its link in the menu), set "show" in the
#  "sections" list below. The folder starts with "_", so Jekyll does not publish
#  those files as pages of their own: they only appear inside this page.
#  Lists that repeat (dates, topics, speakers, programme, fees) are in the
#  DATA section below.
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
  overlay_image: /ci27/assets/images/campus_ecotekne.jpg
  overlay_filter: "0.45"
  actions:
    - label: "Call for papers"
      url: "/ci27/#call-for-papers"
    - label: "Important dates"
      url: "/ci27/#dates"

# ----------------------------------------------------------------------------- SECTIONS
# Order of the page. Each entry:
#   id:    anchor of the section (must match the {#id} of the heading in the file)
#   menu:  label in the in-page menu (leave empty to keep it out of the menu)
#   file:  file in ci27/_sections/
#   show:  true to show the section, false to hide it (and its menu link)
sections:
  - { id: about,                  menu: "About",       file: about.md,                  show: true }
  - { id: dates,                  menu: "Dates",       file: dates.md,                  show: true }
  - { id: call-for-papers,        menu: "Call for papers", file: call-for-papers.md,    show: true }
  - { id: submission-guidelines,  menu: "Submission",  file: submission-guidelines.md,  show: true }
  - { id: author-guidelines,      menu: "Authors",     file: author-guidelines.md,      show: true }
  - { id: presenter-guidelines,   menu: "Presenters",  file: presenter-guidelines.md,   show: true }
  - { id: speakers,               menu: "Speakers",    file: speakers.md,               show: false }
  - { id: programme,              menu: "Programme",   file: programme.md,              show: true }
  - { id: hackathon,              menu: "Hackathon",   file: hackathon.md,              show: true }
  - { id: registration,           menu: "Registration", file: registration.md,          show: true }
  - { id: venue,                  menu: "Venue",       file: venue.md,                  show: true }
  - { id: committee,              menu: "Committee",   file: committee.md,              show: true }
  - { id: contact,                menu: "Contact",     file: contact.md,                show: true }

# ----------------------------------------------------------------------------- DATA
ci27:
  # Link to the CMT submission portal. Leave empty until it exists:
  # the button then shows "opens 30 November 2026".
  submission_url: "https://cmt3.research.microsoft.com/CI2027/Submission/Index"
  submission_opens: "30 November 2026"
  # Link to the registration platform. Leave empty until it exists.
  registration_url: "https://cmt3.research.microsoft.com/CI2027/Submission/Index"
  contact_email: "climate.informatics.workshop@gmail.com"
  mailing_list: "https://groups.google.com/g/climate-informatics-news"
  # Extended abstract templates (files in ci27/assets/files/)
  template_word: "/ci27/assets/files/ci2027-extended-abstract-template.docx"
  template_latex: "/ci27/assets/files/ci2027-extended-abstract-template-latex.zip"

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

  # Topics of interest (same as CI 2026).
  topics:
    - "Knowledge-guided and hybrid Earth-system modelling"
    - "Prediction, nowcasting, downscaling and extremes"
    - "Data assimilation, reanalysis and remote sensing"
    - "Causal discovery, interpretability, calibration and uncertainty quantification"
    - "Climate impacts, adaptation/mitigation decision support and policy"
    - "Reusable datasets, benchmarks and evaluation tools"
    - "Principled positions on ethics, reproducibility and open science"

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
---

<!-- When you change ci27.css, increase the number after ?v= so browsers load the new version -->
<div class="ci27-assets"><link rel="stylesheet" href="{{ '/ci27/assets/css/ci27.css' | relative_url }}?v=2"></div>

<!-- In-page menu: built from the "sections" list in the front matter -->
<div class="ci27-nav" role="navigation" aria-label="CI 2027 sections">
  <a class="ci27-nav__logo" href="#" title="Back to top"><img src="{{ '/ci27/assets/images/climateinformatics.png' | relative_url }}" alt="Climate Informatics"></a>
  <ul>
{% for s in page.sections %}{% if s.show and s.menu != "" %}    <li><a href="#{{ s.id }}">{{ s.menu }}</a></li>
{% endif %}{% endfor %}  </ul>
</div>

<div class="ci27-facts">
  <div class="ci27-fact"><span class="ci27-fact__label">When</span><span class="ci27-fact__value">10–14 May 2027</span></div>
  <div class="ci27-fact"><span class="ci27-fact__label">Where</span><span class="ci27-fact__value">Campus Ecotekne, Lecce</span></div>
  <div class="ci27-fact"><span class="ci27-fact__label">Submission deadline</span><span class="ci27-fact__value">5 February 2027</span></div>
</div>
{% for s in page.sections %}{% if s.show %}

{% include_relative _sections/{{ s.file }} %}
{% endif %}{% endfor %}
