---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
    - /about/
    - /about.html
---

I am a Principal Scientist and Group Lead at [Prescient Design](https://www.gene.com/scientists/our-scientists/prescient-design), [Genentech](https://www.gene.com/scientists/our-scientists/ji-won-park), developing statistical frameworks for reliable decision making using large models, with applications to model‑guided scientific discovery. My research focuses on uncertainty quantification, Bayesian experimental design, and scalable inference, emphasizing methods that provide formal guarantees, are sample‑efficient, and improve with advances in foundation and generative models. I received my Ph.D. in Physics from [Stanford University](https://kipac.stanford.edu/people/ji-won-park), where I worked on hierarchical Bayesian methods for cosmology. During my Ph.D., I interned at [NASA Ames](https://www.nasa.gov/ames/) and the [Center for Computational Astrophysics](https://www.simonsfoundation.org/flatiron/center-for-computational-astrophysics/) at the Flatiron Institute. I hold a B.S. in Mathematics and a B.S. in Physics from [Duke University](https://duke.edu/).


<h2>Recent events</h2>

{% assign recent_talks = site.talks | sort: 'date' | reverse %}
<ul>
{% for talk in recent_talks limit:5 %}
<li><a href="{{ talk.url }}"><strong>{{ talk.date | date: "%B %d, %Y" }}</strong></a>: {{ talk.type }} "{{ talk.title }}" - {{ talk.venue }} in {{ talk.location }} </li>
{% endfor %}
</ul>

## Research themes
* **Decision-making under uncertainty (AI4Science)**
    * Multi‑objective Bayesian optimization for molecular design
    * Productionalizing ML-guided design of antibodies, small molecules, and molecular glues tailored to project-specific desiderata
* **Inference and prediction in high dimensions**
    * Semantic uncertainty quantification for LLMs
    * Post-hoc calibration (e.g. conformal prediction, semiparametric methods)
    * Out‑of‑distribution generalization, diagnostics for distribution shifts
* **Sampling in high dimensions**
    * Diversity-steered sampling strategies for LLMs
    * Guidance for diffusion-based generative models
    * Sampling algorithms for non‑log‑concave distributions


