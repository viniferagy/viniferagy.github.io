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
    <p class="lede">Ph.D. student at the School of Computer Science, <a href="https://english.pku.edu.cn/" target="_blank" rel="noopener">Peking University</a>, advised by Prof.&nbsp;Houfeng&nbsp;Wang.</p>
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
      {% if site.author.huggingface %}<a href="{{ site.author.huggingface }}" target="_blank" rel="noopener">Hugging Face</a>{% endif %}
    </div>
  </div>
  <div class="portrait">
    <img
      src="{{ site.author.avatar | relative_url }}"
      alt="{{ site.author.name }}"
      width="148"
      height="148"
      loading="eager"
      fetchpriority="high"
    >
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
  <h2 class="eyebrow" id="h-pubs">Publications<span class="count">11 entries</span></h2>
  <div class="tabs" role="group" aria-label="Filter publications">
    <button class="tab" data-filter="all" aria-pressed="true">All · 11</button>
    <button class="tab" data-filter="first" aria-pressed="false">First-author · 3</button>
    <button class="tab" data-filter="co" aria-pressed="false">Co-author · 8</button>
  </div>
  <div class="publist">

    <!-- ====== 2026 ====== -->

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge preprint">arXiv 2026</span></div>
        <h3><a href="https://arxiv.org/abs/2605.01749" target="_blank" rel="noopener">Only Say What You Know: Calibration-Aware Generation for Long-Form Factuality</a></h3>
        <p class="au">Wen Luo, <span class="me">Guangyue Peng</span>, Liang Wang, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2605.01749" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="first">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge">ICML 2026</span><span class="role">First author</span></div>
        <h3><a href="https://icml.cc/virtual/2026/poster/62852" target="_blank" rel="noopener">Measuring and Mitigating Post-hoc Rationalization in Reverse Chain-of-Thought Generation</a></h3>
        <p class="au"><span class="me">Guangyue Peng</span>, Zongchao Chen, Wen Luo, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2602.14469" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://icml.cc/virtual/2026/poster/62852" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/viniferagy/SSR" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge tech-report">Technical Report</span></div>
        <h3><a href="https://arxiv.org/abs/2602.13367" target="_blank" rel="noopener">Nanbeige4.1-3B: A Small General Model that Reasons, Aligns, and Acts</a></h3>
        <p class="au">Chen Yang, <span class="me">Guangyue Peng</span>, Jiahao Zhu, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2602.13367" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://huggingface.co/Nanbeige/Nanbeige4.1-3B" target="_blank" rel="noopener"><svg class="brand-icon huggingface" viewBox="0 0 24 24" aria-hidden="true"><circle cx="12" cy="12" r="7.2"/><path d="M8.1 4.2 6.8 2.3M15.9 4.2l1.3-1.9M7.3 11.2h.1M16.6 11.2h.1M8.6 15.1c1.7 1.4 5.1 1.4 6.8 0M5.2 17.8c-1.4-.4-2.5-1.6-2.8-3M18.8 17.8c1.4-.4 2.5-1.6 2.8-3"/></svg>Model<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge">ACL 2026 Findings</span></div>
        <h3><a href="https://aclanthology.org/2026.findings-acl.1545/" target="_blank" rel="noopener">PACE: Prefix-Protected and Difficulty-Aware Compression for Efficient Reasoning</a></h3>
        <p class="au">Ruixiang Feng, ..., <span class="me">Guangyue Peng</span>, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2602.11639" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2026.findings-acl.1545/" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge oral">ACL 2026 · Oral</span></div>
        <h3><a href="https://aclanthology.org/2026.acl-long.1173/" target="_blank" rel="noopener">Two Pathways to Truthfulness: On the Intrinsic Encoding of LLM Hallucinations</a></h3>
        <p class="au">Wen Luo, <span class="me">Guangyue Peng</span>, Wei Li, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2601.07422" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2026.acl-long.1173/" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2026</div>
      <div>
        <div class="meta"><span class="badge">ICSME 2026</span></div>
        <h3><a href="https://conf.researchr.org/details/icsme-2026/icsme-2026-papers/24/SWE-Ext-Scaling-and-Extending-Augmented-Data-for-Mid-Training-of-Repository-Level-Co" target="_blank" rel="noopener">SWE-Ext: Scaling and Extending Augmented Data for Mid-Training of Repository-Level Coding Tasks</a></h3>
        <p class="au">Wei Li, Xin Zhang, Shaohang Wei, Wen Luo, Feifan Song, <span class="me">Guangyue Peng</span>, et al.</p>
        <div class="links">
          <a class="src" href="https://conf.researchr.org/details/icsme-2026/icsme-2026-papers/24/SWE-Ext-Scaling-and-Extending-Augmented-Data-for-Mid-Training-of-Repository-Level-Co" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <!-- ====== 2025 ====== -->

    <article class="pub" data-role="first">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span><span class="role">First author</span></div>
        <h3><a href="https://aclanthology.org/2025.acl-long.1385/" target="_blank" rel="noopener">Learn to Memorize: Scalable Continual Learning in Semiparametric Models with Mixture-of-Neighbors Induction Memory</a></h3>
        <p class="au"><span class="me">Guangyue Peng</span>, Tao Ge, Wen Luo, et al.</p>
        <div class="links">
          <a class="src" href="https://aclanthology.org/2025.acl-long.1385/" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/viniferagy/MoNIM" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="first">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025 Findings</span><span class="role">First author</span></div>
        <h3><a href="https://aclanthology.org/2025.findings-acl.1090/" target="_blank" rel="noopener">Encode Errors: Representational Retrieval of In-Context Demonstrations for Multilingual Grammatical Error Correction</a></h3>
        <p class="au"><span class="me">Guangyue Peng</span>, Wei Li, Wen Luo, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2606.15416" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.findings-acl.1090/" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/viniferagy/GER" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span></div>
        <h3><a href="https://aclanthology.org/2025.acl-long.1320/" target="_blank" rel="noopener">Odysseus Navigates the Sirens' Song: Dynamic Focus Decoding for Factual and Diverse Open-Ended Text Generation</a></h3>
        <p class="au">Wen Luo, Feifan Song, Wei Li, <span class="me">Guangyue Peng</span>, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2503.08057" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.acl-long.1320/" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/RowanWenLuo/Siren-DFD" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">ACL 2025</span></div>
        <h3><a href="https://aclanthology.org/2025.acl-long.839/" target="_blank" rel="noopener">FEA-Bench: A Benchmark for Evaluating Repository-Level Code Generation for Feature Implementation</a></h3>
        <p class="au">Wei Li, Xin Zhang, ..., Wen Luo, <span class="me">Guangyue Peng</span>, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2503.06680" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.acl-long.839/" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/microsoft/FEA-Bench" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

    <article class="pub" data-role="co">
      <div class="yr">2025</div>
      <div>
        <div class="meta"><span class="badge">NAACL 2025</span></div>
        <h3><a href="https://aclanthology.org/2025.naacl-long.251/" target="_blank" rel="noopener">Explanation based In-Context Demonstrations Retrieval for Multilingual Grammatical Error Correction</a></h3>
        <p class="au">Wei Li, Wen Luo, <span class="me">Guangyue Peng</span>, et al.</p>
        <div class="links">
          <a class="src" href="https://arxiv.org/abs/2502.08507" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.naacl-long.251/" target="_blank" rel="noopener"><svg class="link-icon" viewBox="0 0 24 24" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/GMago-LeWay/FewShotGEC" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
      </div>
    </article>

  </div>
</section>

<section id="honors-and-awards" aria-labelledby="h-honors">
  <h2 class="eyebrow" id="h-honors">Honors &amp; Awards<span class="count">06</span></h2>
  <div class="rows">
    <div class="row">
      <div class="when">2025</div>
      <p class="what"><b>Huawei Scholarship</b>, School of Computer Science, Peking University</p>
    </div>
    <div class="row">
      <div class="when">2025</div>
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
      <p class="what"><b>Ph.D., Peking University</b><small>School of Computer Science</small></p>
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
