## Call for papers {#call-for-papers}

We invite contributions across the full intersection of machine learning, data science and
climate research: work that advances our understanding of the Earth system, supports climate
adaptation and mitigation, or makes climate data and models more transparent and accessible.

### Topics of interest
{% for t in page.ci27.topics %}
- {{ t }}{% endfor %}
{: .ci27-topics}

### What reviewers look for

Submissions should be clearly relevant to climate science, compare against appropriate
baselines and include a rigorous evaluation that addresses uncertainty, robustness and
limitations. Authors are strongly encouraged to share code, data and other artifacts so that
results can be reproduced.

### Submission tracks

There are two tracks, **full papers** and **extended abstracts**. Both are due on
**5 February 2027** (23:59 AoE) and are submitted through Microsoft CMT
(see [Submission guidelines](#submission-guidelines)). Each author may submit only one paper.

#### Full papers

- Original, unpublished work of up to **8 pages**, not counting acknowledgements, references
  and appendices or supplementary material.
- Prepared with the [Environmental Data Science](https://www.cambridge.org/core/journals/environmental-data-science)
  (EDS) LaTeX or Word templates, available from Cambridge University Press and Overleaf.
- Accepted full papers are considered for an oral or poster presentation, and accepted papers
  that are presented at the conference are published in *Environmental Data Science*.

#### Extended abstracts

- At least **300 words** and at most **2 pages** in total, including figures and references.
  The work must be original; preliminary or ongoing research is welcome.
- Must include **at least one figure or schematic** that visually summarises the research.
- Suggested structure: *Introduction and objectives*, *Methods and data*,
  *Preliminary results and/or expected outcomes* (including implications and limitations).
- Use the CI 2027 template:
  [Word (.docx)]({{ page.ci27.template_word | relative_url }}) ·
  [LaTeX (.zip)]({{ page.ci27.template_latex | relative_url }})
- Accepted extended abstracts are considered for a poster presentation.

### Paper categories

When submitting, choose the single category that best describes the main contribution of
your work. Categories are used to assign reviewers and follow the article types of
*Environmental Data Science*. They apply to both tracks, except position papers, which are
accepted as full papers only.

- **Application papers:** research progress on, or a solution to, a real-world problem in an
  environmental field, made possible by data science (for example, using AI to better
  understand climate applications or to improve forecasting tools).
- **Methods papers:** new data-science methodology motivated by an environmental problem,
  usually demonstrated on one or more climate applications.
- **Data papers:** the creation and usefulness of reusable environmental datasets or
  benchmarks. The data must be available in a publicly accessible repository.
- **Position papers** (full papers only): well-argued views on the adoption of AI and data
  science, or on obstacles to it, or on environmental data issues such as ethics, law, policy,
  standards and services.

### Review process

- Reviewing is **double-blind**. Manuscripts and supplementary material must not reveal the
  authors' identity, directly or indirectly; submissions that do may be desk-rejected.
- Posting related work on arXiv is allowed. If you cite your own preprint, refer to it in the
  third person and avoid wording that reveals authorship.
- Reviewers' identities are not disclosed to authors.

{% if page.ci27.submission_url != "" %}[Submit your paper]({{ page.ci27.submission_url }}){: .btn .btn--primary .btn--large}{% else %}<span class="btn btn--large ci27-btn-disabled">Submission portal opens {{ page.ci27.submission_opens }}</span>{% endif %}
{: .ci27-cta}
