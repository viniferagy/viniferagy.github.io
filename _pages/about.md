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
          <a class="src" href="https://arxiv.org/abs/2605.01749" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2602.14469" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://icml.cc/virtual/2026/poster/62852" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/viniferagy/SSR" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.53 2.87 8.37 6.84 9.73.5.1.68-.22.68-.5 0-.25-.01-1.07-.02-1.94-2.78.62-3.37-1.21-3.37-1.21-.46-1.2-1.12-1.52-1.12-1.52-.92-.64.07-.63.07-.63 1.02.07 1.55 1.07 1.55 1.07.9 1.58 2.36 1.12 2.94.86.09-.67.35-1.12.64-1.38-2.22-.26-4.55-1.14-4.55-5.05 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.7 0 0 .84-.28 2.75 1.05A9.32 9.32 0 0 1 12 6.95c.85 0 1.7.12 2.5.34 1.9-1.33 2.74-1.05 2.74-1.05.55 1.4.2 2.44.1 2.7.64.72 1.03 1.63 1.03 2.75 0 3.92-2.34 4.78-4.57 5.03.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.8 0 .28.18.61.69.5A10.05 10.05 0 0 0 22 12.26C22 6.58 17.52 2 12 2Z"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2602.13367" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://huggingface.co/Nanbeige/Nanbeige4.1-3B" target="_blank" rel="noopener"><svg class="brand-icon huggingface" viewBox="0 0 24 24" aria-hidden="true"><path d="M12.025 1.13c-5.77 0-10.449 4.647-10.449 10.378 0 1.112.178 2.181.503 3.185.064-.222.203-.444.416-.577a.96.96 0 0 1 .524-.15c.293 0 .584.124.84.284.278.173.48.408.71.694.226.282.458.611.684.951v-.014c.017-.324.106-.622.264-.874s.403-.487.762-.543c.3-.047.596.06.787.203s.31.313.4.467c.15.257.212.468.233.542.01.026.653 1.552 1.657 2.54.616.605 1.01 1.223 1.082 1.912.055.537-.096 1.059-.38 1.572.637.121 1.294.187 1.967.187.657 0 1.298-.063 1.921-.178-.287-.517-.44-1.041-.384-1.581.07-.69.465-1.307 1.081-1.913 1.004-.987 1.647-2.513 1.657-2.539.021-.074.083-.285.233-.542.09-.154.208-.323.4-.467a1.08 1.08 0 0 1 .787-.203c.359.056.604.29.762.543s.247.55.265.874v.015c.225-.34.457-.67.683-.952.23-.286.432-.52.71-.694.257-.16.547-.284.84-.285a.97.97 0 0 1 .524.151c.228.143.373.388.43.625l.006.04a10.3 10.3 0 0 0 .534-3.273c0-5.731-4.678-10.378-10.449-10.378M8.327 6.583a1.5 1.5 0 0 1 .713.174 1.487 1.487 0 0 1 .617 2.013c-.183.343-.762-.214-1.102-.094-.38.134-.532.914-.917.71a1.487 1.487 0 0 1 .69-2.803m7.486 0a1.487 1.487 0 0 1 .689 2.803c-.385.204-.536-.576-.916-.71-.34-.12-.92.437-1.103.094a1.487 1.487 0 0 1 .617-2.013 1.5 1.5 0 0 1 .713-.174m-10.68 1.55a.96.96 0 1 1 0 1.921.96.96 0 0 1 0-1.92m13.838 0a.96.96 0 1 1 0 1.92.96.96 0 0 1 0-1.92M8.489 11.458c.588.01 1.965 1.157 3.572 1.164 1.607-.007 2.984-1.155 3.572-1.164.196-.003.305.12.305.454 0 .886-.424 2.328-1.563 3.202-.22-.756-1.396-1.366-1.63-1.32q-.011.001-.02.006l-.044.026-.01.008-.03.024q-.018.017-.035.036l-.032.04a1 1 0 0 0-.058.09l-.014.025q-.049.088-.11.19a1 1 0 0 1-.083.116 1.2 1.2 0 0 1-.173.18q-.035.029-.075.058a1.3 1.3 0 0 1-.251-.243 1 1 0 0 1-.076-.107c-.124-.193-.177-.363-.337-.444-.034-.016-.104-.008-.2.022q-.094.03-.216.087-.06.028-.125.063l-.13.074q-.067.04-.136.086a3 3 0 0 0-.135.096 3 3 0 0 0-.26.219 2 2 0 0 0-.12.121 2 2 0 0 0-.106.128l-.002.002a2 2 0 0 0-.09.132l-.001.001a1.2 1.2 0 0 0-.105.212c-.008.024-.016.048-.024.073-1.139-.875-1.563-2.317-1.563-3.203 0-.334.109-.457.305-.454m.836 10.354c.824-1.19.766-2.082-.365-3.194-1.13-1.112-1.789-2.738-1.789-2.738s-.246-.945-.806-.858-.97 1.499.202 2.362c1.173.864-.233 1.45-.685.64-.45-.812-1.683-2.896-2.322-3.295s-1.089-.175-.938.647 2.822 2.813 2.562 3.244-1.176-.506-1.176-.506-2.866-2.567-3.49-1.898.473 1.23 2.037 2.16c1.564.932 1.686 1.178 1.464 1.53s-3.675-2.511-4-1.297c-.323 1.214 3.524 1.567 3.287 2.405-.238.839-2.71-1.587-3.216-.642-.506.946 3.49 2.056 3.522 2.064 1.29.33 4.568 1.028 5.713-.624m5.349 0c-.824-1.19-.766-2.082.365-3.194 1.13-1.112 1.789-2.738 1.789-2.738s.246-.945.806-.858.97 1.499-.202 2.362c-1.173.864.233 1.45.685.64.451-.812 1.683-2.896 2.322-3.295s1.089-.175.938.647-2.822 2.813-2.562 3.244 1.176-.506 1.176-.506 2.866-2.567 3.49-1.898-.473 1.23-2.037 2.16c-1.564.932-1.686 1.178-1.464 1.53s3.675-2.511 4-1.297c.323 1.214-3.524 1.567-3.287 2.405.238.839 2.71-1.587 3.216-.642.506.946-3.49 2.056-3.522 2.064-1.29.33-4.568 1.028-5.713-.624"/></svg>Model<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2602.11639" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2026.findings-acl.1545/" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2601.07422" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2026.acl-long.1173/" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://conf.researchr.org/details/icsme-2026/icsme-2026-papers/24/SWE-Ext-Scaling-and-Extending-Augmented-Data-for-Mid-Training-of-Repository-Level-Co" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://aclanthology.org/2025.acl-long.1385/" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/viniferagy/MoNIM" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.53 2.87 8.37 6.84 9.73.5.1.68-.22.68-.5 0-.25-.01-1.07-.02-1.94-2.78.62-3.37-1.21-3.37-1.21-.46-1.2-1.12-1.52-1.12-1.52-.92-.64.07-.63.07-.63 1.02.07 1.55 1.07 1.55 1.07.9 1.58 2.36 1.12 2.94.86.09-.67.35-1.12.64-1.38-2.22-.26-4.55-1.14-4.55-5.05 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.7 0 0 .84-.28 2.75 1.05A9.32 9.32 0 0 1 12 6.95c.85 0 1.7.12 2.5.34 1.9-1.33 2.74-1.05 2.74-1.05.55 1.4.2 2.44.1 2.7.64.72 1.03 1.63 1.03 2.75 0 3.92-2.34 4.78-4.57 5.03.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.8 0 .28.18.61.69.5A10.05 10.05 0 0 0 22 12.26C22 6.58 17.52 2 12 2Z"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2606.15416" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.findings-acl.1090/" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/viniferagy/GER" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.53 2.87 8.37 6.84 9.73.5.1.68-.22.68-.5 0-.25-.01-1.07-.02-1.94-2.78.62-3.37-1.21-3.37-1.21-.46-1.2-1.12-1.52-1.12-1.52-.92-.64.07-.63.07-.63 1.02.07 1.55 1.07 1.55 1.07.9 1.58 2.36 1.12 2.94.86.09-.67.35-1.12.64-1.38-2.22-.26-4.55-1.14-4.55-5.05 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.7 0 0 .84-.28 2.75 1.05A9.32 9.32 0 0 1 12 6.95c.85 0 1.7.12 2.5.34 1.9-1.33 2.74-1.05 2.74-1.05.55 1.4.2 2.44.1 2.7.64.72 1.03 1.63 1.03 2.75 0 3.92-2.34 4.78-4.57 5.03.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.8 0 .28.18.61.69.5A10.05 10.05 0 0 0 22 12.26C22 6.58 17.52 2 12 2Z"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2503.08057" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.acl-long.1320/" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/RowanWenLuo/Siren-DFD" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.53 2.87 8.37 6.84 9.73.5.1.68-.22.68-.5 0-.25-.01-1.07-.02-1.94-2.78.62-3.37-1.21-3.37-1.21-.46-1.2-1.12-1.52-1.12-1.52-.92-.64.07-.63.07-.63 1.02.07 1.55 1.07 1.55 1.07.9 1.58 2.36 1.12 2.94.86.09-.67.35-1.12.64-1.38-2.22-.26-4.55-1.14-4.55-5.05 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.7 0 0 .84-.28 2.75 1.05A9.32 9.32 0 0 1 12 6.95c.85 0 1.7.12 2.5.34 1.9-1.33 2.74-1.05 2.74-1.05.55 1.4.2 2.44.1 2.7.64.72 1.03 1.63 1.03 2.75 0 3.92-2.34 4.78-4.57 5.03.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.8 0 .28.18.61.69.5A10.05 10.05 0 0 0 22 12.26C22 6.58 17.52 2 12 2Z"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2503.06680" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.acl-long.839/" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/microsoft/FEA-Bench" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.53 2.87 8.37 6.84 9.73.5.1.68-.22.68-.5 0-.25-.01-1.07-.02-1.94-2.78.62-3.37-1.21-3.37-1.21-.46-1.2-1.12-1.52-1.12-1.52-.92-.64.07-.63.07-.63 1.02.07 1.55 1.07 1.55 1.07.9 1.58 2.36 1.12 2.94.86.09-.67.35-1.12.64-1.38-2.22-.26-4.55-1.14-4.55-5.05 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.7 0 0 .84-.28 2.75 1.05A9.32 9.32 0 0 1 12 6.95c.85 0 1.7.12 2.5.34 1.9-1.33 2.74-1.05 2.74-1.05.55 1.4.2 2.44.1 2.7.64.72 1.03 1.63 1.03 2.75 0 3.92-2.34 4.78-4.57 5.03.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.8 0 .28.18.61.69.5A10.05 10.05 0 0 0 22 12.26C22 6.58 17.52 2 12 2Z"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
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
          <a class="src" href="https://arxiv.org/abs/2502.08507" target="_blank" rel="noopener">arXiv<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://aclanthology.org/2025.naacl-long.251/" target="_blank" rel="noopener">Conference<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
          <a class="src" href="https://github.com/GMago-LeWay/FewShotGEC" target="_blank" rel="noopener"><svg class="brand-icon github" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.53 2.87 8.37 6.84 9.73.5.1.68-.22.68-.5 0-.25-.01-1.07-.02-1.94-2.78.62-3.37-1.21-3.37-1.21-.46-1.2-1.12-1.52-1.12-1.52-.92-.64.07-.63.07-.63 1.02.07 1.55 1.07 1.55 1.07.9 1.58 2.36 1.12 2.94.86.09-.67.35-1.12.64-1.38-2.22-.26-4.55-1.14-4.55-5.05 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.7 0 0 .84-.28 2.75 1.05A9.32 9.32 0 0 1 12 6.95c.85 0 1.7.12 2.5.34 1.9-1.33 2.74-1.05 2.74-1.05.55 1.4.2 2.44.1 2.7.64.72 1.03 1.63 1.03 2.75 0 3.92-2.34 4.78-4.57 5.03.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.8 0 .28.18.61.69.5A10.05 10.05 0 0 0 22 12.26C22 6.58 17.52 2 12 2Z"/></svg>Code<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 17 17 7M9 7h8v8"/></svg></a>
        </div>
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
