I am an Assistant Professor in the [Department of Electrical and Computer Engineering](https://eng.auburn.edu/ece/) at [Auburn University](https://www.auburn.edu/), with affiliation to the [Neuroimaging Center](https://www.eng.auburn.edu/research/centers/mri/). 

I obtained my PhD in Electrical and Computer Engineering from the Johns Hopkins University, where I had been very fortunate to have [Dr. Trac D. Tran](https://engineering.jhu.edu/faculty/trac-duy-tran/) as my advisor. My PhD research focused on compressive sensing and Bayesian methods with applications in signal and image processing. During my postdoctoral training, I first worked on computational imaging and inverse problems in [Dr. Ivan Dokmanic&#x0301;](https://dmi.unibas.ch/de/personen/ivan-dokmanic/)'s group at the University of Illinois at Urbana-Champaign. I then moved on to investigating neurodegenerative diseases using magnetic resonance imaging in [Dr. Deqiang Qiu](https://randomprogram.net/index.html)'s group at Emory University.







<hr class="my-5">
<h2 id="students">Students</h2>

<div class="row">
  {% for p in site.data.students %}
  <div class="col-12 col-sm-6 col-md-4 mb-4 d-flex">
    <div class="card w-100">
      {% if p.image %}
      <img class="card-img-top" src="{{ p.image | relative_url }}" alt="{{ p.name }}">
      {% endif %}
      <div class="card-body">
        <h5 class="card-title mb-1">{{ p.name }}</h5>
        {% if p.role %}<div class="text-muted mb-2">{{ p.role }}</div>{% endif %}

        <div class="small">
          {% if p.email %}<div><a href="mailto:{{ p.email }}">{{ p.email }}</a></div>{% endif %}
          {% if p.website %}<div><a href="{{ p.website }}" target="_blank" rel="noopener">Website</a></div>{% endif %}
          {% if p.github %}<div><a href="https://github.com/{{ p.github }}" target="_blank" rel="noopener">GitHub</a></div>{% endif %}
          {% if p.linkedin %}<div><a href="https://www.linkedin.com/in/{{ p.linkedin }}/" target="_blank" rel="noopener">LinkedIn</a></div>{% endif %}
          {% if p.scholar %}<div><a href="https://scholar.google.com/citations?user={{ p.scholar }}" target="_blank" rel="noopener">Google Scholar</a></div>{% endif %}
        </div>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
