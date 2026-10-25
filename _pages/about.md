---
permalink: /
# title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Masoud Nateghi, a fourth-year PhD candidate in the department of Biomedical Informatics at Emory University. I work under the supervision of [Dr. Reza Sameni](https://sameni.info/) at the [Alphanumerics Lab](https://sameni.org/) and my research interests are digital signal processing, biomedical data science, AI for healthcare, and estimation theory. I have been working on biomedical signal processing domain for the past 5 years and have extensive exposure to modalities like EEG, ECG, PCG, PPG, EDA, MSNA, and continuous Blood Pressure. I extract clinically meaningful biomarkers from these biomedical signals and then I feed them to ML/DL models to recognize the hidden patterns in the data.

In my unprofessional life, I am a dad to 2 lovely kitties, Madoud and Doude. I have strong passion for music (rock/metal) and occasionaly play electric guitar. I also geek out on history and am a huge soccer fan. To avoid developing a computer belly, I play soccer (center midfield) and bike around Atlanta with Atlanta Social Bike Rides ([ASBR](https://www.instagram.com/atlantasocialbikerides/)).

Research Interests
======

<ul class="research-interests-grid">
  <li>Digital signal processing</li>
  <li>Biomedical signal processing</li>
  <li>Statistical signal processing</li>
  <li>Biomedical data science</li>
  <li>AI for healthcare</li>
  <li>Estimation theory</li>
  <li>Kalman Filters</li>
  <li>Source Separation</li>
</ul>

Publications
======

{% include base_path %}

<ul>
{% for post in site.publications reversed %}
  {% assign first_author = post.authors | first %}
  {% assign publication_url = post.paperurl | default: post.url %}
  <li>
    <a href="{% if post.paperurl %}{{ publication_url }}{% else %}{{ base_path }}{{ publication_url }}{% endif %}"{% if post.paperurl %} target="_blank" rel="noopener"{% endif %}>{{ post.title }}</a>,
    {% if first_author %}
      {% if first_author == site.author.name %}<strong>{{ first_author }}</strong>{% else %}{{ first_author }}{% endif %}{% if post.authors.size > 1 %} et al.{% endif %},
    {% endif %}
    {% if post.venue %} <em>{{ post.venue }}</em>{% endif %}{% if post.date %}, {{ post.date | date: "%Y" }}{% endif %}
  </li>
{% endfor %}
</ul>
