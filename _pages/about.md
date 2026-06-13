---
permalink: /
title: ""
excerpt: ""
redirect_from: 
  - /about/
  - /about.html
---

<section class="hero" id="about-me" aria-label="Introduction">
  <div class="hgroup">
    <p class="eyebrow">Ph.D. Student · Computational Linguistics</p>
    <h1>{{ site.author.name }}</h1>
    <p class="lede">Ph.D. student at the State Key Laboratory of Multimedia Information Processing, School of Computer Science, <a href="https://english.pku.edu.cn/" target="_blank" rel="noopener">Peking University</a>, advised by Prof.&nbsp;Houfeng&nbsp;Wang.</p>
    <div class="tokens" aria-label="Research focus: reasoning, retrieval augmentation, memory">
      <span class="tok" data-gloss="improving faithfulness of chain-of-thought generation" style="--p:.94"><i class="ix">[0]</i>reasoning<span class="bar"><i></i></span><span class="p">p = 0.94</span></span>
      <span class="tok" data-gloss="enhancing retrieval for in-context learning" style="--p:.96"><i class="ix">[1]</i>retrieval-aug<span class="bar"><i></i></span><span class="p">p = 0.96</span></span>
      <span class="tok" data-gloss="scalable memory for continual learning" style="--p:.91"><i class="ix">[2]</i>memory<span class="bar"><i></i></span><span class="p">p = 0.91</span></span>
    </div>
    <div class="chips">
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener">GitHub</a>{% endif %}
      {% if site.author.email %}<a href="mailto:{{ site.author.email }}">Email</a>{% endif %}
      {% if site.author.googlescholar %}<a href="{{ site.author.googlescholar }}" target="_blank" rel="noopener">Scholar</a>{% endif %}
      {% if site.author.dblp %}<a href="{{ site.author.dblp }}" target="_blank" rel="noopener">DBLP</a>{% endif %}
      {% if site.author.orcid %}<a href="{{ site.author.orcid }}" target="_blank" rel="noopener">ORCID</a>{% endif %}
    </div>
  </div>
  <div class="portrait">
    <img src="{{ site.author.avatar }}" alt="{{ site.author.name }}" width="148" height="148">
  </div>
</section>

<section id="about" aria-labelledby="h-about">
  <h2 class="eyebrow" id="h-about">About</h2>
  <div class="prose">
    <p>My research centers on large language models, with a particular focus on <span class="hl">reasoning faithfulness</span>, <span class="hl">retrieval-augmented generation</span>, and <span class="hl">long-term memory</span>. I study how models can reason more faithfully and reliably, how they can ground generation in retrieved knowledge, and how they can keep learning over time without forgetting.</p>
    <p>Feel free to reach out if you are interested in collaboration or have related research ideas.</p>
  </div>
</section>

<section id="publications" aria-labelledby="h-pubs">
  <h2 class="eyebrow" id="h-pubs">Publications<span class="count">10 entries</span></h2>
  <div class="tabs" role="group" aria-label="Filter publications">
    <button class="tab" data-filter="all" aria-pressed="true">All · 10</button>
    <button class="tab" data-filter="first" aria-pressed="false">First-author · 3</button>
    <button class="tab" data-filter="co" aria-pressed="false">Co-author · 7</button>
  </div>
  <div class="publist">

    <!-- ====== 2026 ====== -->

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge preprint">arXiv 2026</span></div>
        <h3><a href="https://arxiv.org/abs/2605.01749" target="_blank" rel="noopener">Only Say What You Know: Calibration-Aware Generation for Long-Form Factuality</a></h3>
        <p class="au">Wen Luo, <span class="me">Guangyue Peng</span>, Liang Wang, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2605.01749" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="first">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge">ICML 2026</span><span class="role">First author</span></div>
        <h3><a href="https://arxiv.org/abs/2602.14469" target="_blank" rel="noopener">Measuring and Mitigating Post-hoc Rationalization in Reverse Chain-of-Thought Generation</a></h3>
        <p class="au"><span class="me">Guangyue Peng</span>, Zongchao Chen, Wen Luo, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2602.14469" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge preprint">arXiv 2026</span></div>
        <h3><a href="https://arxiv.org/abs/2602.13367" target="_blank" rel="noopener">Nanbeige4.1-3B: A Small General Model that Reasons, Aligns, and Acts</a></h3>
        <p class="au">Chen Yang, <span class="me">Guangyue Peng</span>, Jiahao Zhu, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2602.13367" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge preprint">arXiv 2026</span></div>
        <h3><a href="https://arxiv.org/abs/2602.11639" target="_blank" rel="noopener">PACE: Prefix-Protected and Difficulty-Aware Compression for Efficient Reasoning</a></h3>
        <p class="au">Ruixiang Feng, ..., <span class="me">Guangyue Peng</span>, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2602.11639" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge oral">ACL 2026 · Oral</span></div>
        <h3><a href="https://arxiv.org/abs/2601.07422" target="_blank" rel="noopener">Two Pathways to Truthfulness: On the Intrinsic Encoding of LLM Hallucinations</a></h3>
        <p class="au">Wen Luo, <span class="me">Guangyue Peng</span>, Wei Li, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2601.07422" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge">ICSME 2026</span></div>
        <h3><a href="https://conf.researchr.org/details/icsme-2026/icsme-2026-papers/24/SWE-Ext-Scaling-and-Extending-Augmented-Data-for-Mid-Training-of-Repository-Level-Co" target="_blank" rel="noopener">SWE-Ext: Scaling and Extending Augmented Data for Mid-Training of Repository-Level Coding Tasks</a></h3>
        <p class="au">Wei Li, Xin Zhang, Shaohang Wei, Wen Luo, Feifan Song, <span class="me">Guangyue Peng</span>, et al.</p>
        <a class="src" href="https://conf.researchr.org/details/icsme-2026/icsme-2026-papers/24/SWE-Ext-Scaling-and-Extending-Augmented-Data-for-Mid-Training-of-Repository-Level-Co" target="_blank" rel="noopener">ICSME<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <!-- ====== 2025 ====== -->

    <article class="pub" data-role="first">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span><span class="role">First author</span></div>
        <h3><a href="https://aclanthology.org/2025.acl-long.1385/" target="_blank" rel="noopener">Learn to Memorize: Scalable Continual Learning in Semiparametric Models with Mixture-of-Neighbors Induction Memory</a></h3>
        <p class="au"><span class="me">Guangyue Peng</span>, Tao Ge, Wen Luo, et al.</p>
        <a class="src" href="https://aclanthology.org/2025.acl-long.1385/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="first">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025 Findings</span><span class="role">First author</span></div>
        <h3><a href="https://aclanthology.org/2025.findings-acl.1090/" target="_blank" rel="noopener">Encode Errors: Representational Retrieval of In-Context Demonstrations for Multilingual Grammatical Error Correction</a></h3>
        <p class="au"><span class="me">Guangyue Peng</span>, Wei Li, Wen Luo, et al.</p>
        <a class="src" href="https://aclanthology.org/2025.findings-acl.1090/" target="_blank" rel="noopener">ACL Anthology<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span></div>
        <h3><a href="https://arxiv.org/abs/2503.06680" target="_blank" rel="noopener">FEA-Bench: A Benchmark for Evaluating Repository-Level Code Generation for Feature Implementation</a></h3>
        <p class="au">Wei Li, Xin Zhang, ..., Wen Luo, <span class="me">Guangyue Peng</span>, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2503.06680" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">NAACL 2025</span></div>
        <h3><a href="https://arxiv.org/abs/2502.08507" target="_blank" rel="noopener">Explanation based In-Context Demonstrations Retrieval for Multilingual Grammatical Error Correction</a></h3>
        <p class="au">Wei Li, Wen Luo, <span class="me">Guangyue Peng</span>, et al.</p>
        <a class="src" href="https://arxiv.org/abs/2502.08507" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
      </div>
    </article>

  </div>
</section>

<section id="honors-and-awards" aria-labelledby="h-honors">
  <h2 class="eyebrow" id="h-honors">Honors &amp; Awards<span class="count">06</span></h2>
  <div class="rows">
    <div class="row">
      <div class="when">2024</div>
      <p class="what"><b>Huawei Scholarship</b>, School of Computer Science, Peking University</p>
    </div>
    <div class="row">
      <div class="when">2024</div>
      <p class="what"><b>BOSS Zhipin Scholarship</b></p>
    </div>
    <div class="row">
      <div class="when">2024</div>
      <p class="what"><b>Merit Student</b>, Peking University</p>
    </div>
    <div class="row">
      <div class="when">2022</div>
      <p class="what"><b>Outstanding Individual Contribution</b>, Beijing Winter Olympics &amp; Paralympics</p>
    </div>
    <div class="row">
      <div class="when">2021</div>
      <p class="what"><b>Fenjiu Group Public Welfare Scholarship</b>, Peking University</p>
    </div>
    <div class="row">
      <div class="when">2019</div>
      <p class="what"><b>Freshman Scholarship</b>, Peking University<span class="honor-rank">Third Prize</span></p>
    </div>
  </div>
</section>

<section id="education" aria-labelledby="h-edu">
  <h2 class="eyebrow" id="h-edu">Education</h2>
  <div class="rows">
    <div class="row">
      <div class="when">2023.09 — 2028.07<br>(expected)</div>
      <p class="what"><b>Ph.D., Peking University</b><small>State Key Laboratory of Multimedia Information Processing, School of Computer Science</small></p>
    </div>
    <div class="row">
      <div class="when">2019.09 — 2023.07</div>
      <p class="what"><b>Undergraduate, Peking University</b><small>Data Science and Big Data Technology, Yuanpei College</small></p>
    </div>
  </div>
</section>

<section id="internships" aria-labelledby="h-intern">
  <h2 class="eyebrow" id="h-intern">Internships</h2>
  <div class="rows">
    <div class="row">
      <div class="when">2025.04 — 2026.03</div>
      <p class="what"><b>BOSS Zhipin</b><small>Research Intern, Algorithm Engineering Group · Beijing</small></p>
    </div>
    <div class="row">
      <div class="when">2023.09 — 2024.08</div>
      <p class="what"><b>Peking University &amp; Founder Group</b><small>University-Enterprise Cooperation Project · Beijing</small></p>
    </div>
    <div class="row">
      <div class="when">2022.09 — 2023.03</div>
      <p class="what"><b>Microsoft Research Asia</b><small>Research Intern, Innovation Engineering Group · Beijing</small></p>
    </div>
  </div>
</section>
