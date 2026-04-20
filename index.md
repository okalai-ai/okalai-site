---
layout: default
title: Home
---

<section class="hero">
  <div class="container hero-columns">
    <div class="hero-inner">
      <div class="hero-badge" data-sr>Applied AI Research</div>
      <h1 data-sr>AI for underrepresented settings.</h1>
      <p class="hero-sub" data-sr>
        Applied AI for underrepresented settings. We research and build AI systems
        for communities and languages underserved by today's state-of-the-art models.
      </p>
      <div class="hero-cta" data-sr>
        <a href="#research" class="btn btn-primary">Our Research</a>
        <a href="#products" class="btn btn-outline">See Products</a>
      </div>
    </div>
    <div class="hero-image" data-sr>
      <img src="/assets/images/okalai-hero.jpg" alt="Okalai AI" loading="eager" />
    </div>
  </div>
  <div class="hero-gradient"></div>
</section>

<section id="architecture" class="section">
  <div class="container">
    <div class="section-header" data-sr>
      <span class="section-label">The Stack</span>
    </div>
    <div class="stack">
      <a class="stack-item stack-item--research" href="#research" data-sr>
        <div class="stack-label">Layer 01</div>
        <div class="stack-name">Research</div>
        <div class="stack-deliverable">Publications</div>
        <p class="stack-desc">Foundational research that defines the principles and methods behind our systems.</p>
      </a>
      <a class="stack-item stack-item--models" href="#models" data-sr>
        <div class="stack-label">Layer 02</div>
        <div class="stack-name">Models</div>
        <div class="stack-deliverable">OkaLM</div>
        <p class="stack-desc">Language models and other machine learning models for underrepresented languages and settings.</p>
      </a>
      <a class="stack-item stack-item--tools" href="#tools" data-sr>
        <div class="stack-label">Layer 03</div>
        <div class="stack-name">Tools and Data</div>
        <div class="stack-deliverable">OkaLex</div>
        <p class="stack-desc">Data and interactive tools built on top of the models and novel datasets for learning, exploration, and practical use.</p>
      </a>
      <a class="stack-item stack-item--applications" href="#applications" data-sr>
        <div class="stack-label">Layer 04</div>
        <div class="stack-name">Applications</div>
        <div class="stack-deliverable">Coming soon</div>
        <p class="stack-desc">End-user systems that apply our research to real-world problems.</p>
      </a>
    </div>
  </div>
</section>

<section id="news" class="news-ticker">
  <div class="container">
    <div class="news-items">
      <div class="news-item">
        <span class="news-date">Apr 2026</span>
        <span class="news-text">Paper "Grammar as Control: Modular Language Generation for the Long Tail" accepted at ACL 2026</span>
      </div>
      <div class="news-item">
        <span class="news-date">Mar 2026</span>
        <span class="news-text">Kwanyama language reference and learning platform</span>
        <a href="https://okalex.org" class="news-link" target="_blank" rel="noopener">Visit &rarr;</a>
      </div>
      <div class="news-item">
        <span class="news-date">Feb 2026</span>
        <span class="news-text">Paper on Kwanyama LLMs (1B, 3B, 8B) accepted at LREC 2026</span>
      </div>
      <div class="news-item">
        <span class="news-date">Jul 2025</span>
        <span class="news-text">Outstanding Paper Award at ACL 2025 for typology-guided multilingual adaptation</span>
        <a href="https://ndapa.us/assets/docs/papers/2025-moi-acl.pdf" class="news-link" target="_blank" rel="noopener">PDF &rarr;</a>
      </div>
    </div>
  </div>
</section>

<section id="research" class="section">
  <div class="container">
    <div class="section-header" data-sr>
      <span class="section-label">Layer 01 · Research</span>
      <h2>Research</h2>
      <p class="section-desc">Foundational research on multilingual and low-resource NLP. Selected publications:</p>
    </div>

    <div class="papers">
      <div class="paper-card" data-sr>
        <div class="paper-venue"><span class="venue-tag">ACL 2026</span></div>
        <h3>Grammar as Control: Modular Language Generation for the Long Tail</h3>
        <div class="paper-links">
          <a href="https://ndapa.us/assets/docs/papers/2026-acl-mtig.pdf" class="paper-link" target="_blank" rel="noopener">📄 PDF</a>
          <a href="https://github.com/okalai-ai/mtig" class="paper-link" target="_blank" rel="noopener">💾 Data</a>
        </div>
        <div class="cite-block">
          <button class="btn-cite" onclick="this.nextElementSibling.classList.toggle('show')">Cite this work</button>
          <pre class="cite-bibtex">@inproceedings{nakashole2026grammar,
  title={Grammar as Control: Modular Language Generation for the Long Tail},
  author={Nakashole, Ndapa},
  booktitle={Proceedings of ACL},
  year={2026}
}</pre>
        </div>
      </div>

      <div class="paper-card" data-sr>
        <div class="paper-venue"><span class="venue-tag">LREC 2026</span></div>
        <h3>Sentiment Analysis and Language Models for <a href="https://okalex.org/" target="_blank" rel="noopener">Oshikwanyama</a></h3>
        <p class="paper-detail"><em>1B, 3B, and 8B parameter LLMs for <a href="https://okalex.org/" target="_blank" rel="noopener">Oshikwanyama</a></em></p>
        <div class="paper-links">
          <a href="https://ndapa.us/assets/docs/papers/2026-lrec-oka.pdf" class="paper-link" target="_blank" rel="noopener">📄 PDF</a>
          <a href="https://github.com/okalai-ai/okaResource" class="paper-link" target="_blank" rel="noopener">💾 Data</a>
          <a href="https://huggingface.co/okalai-ai" class="paper-link" target="_blank" rel="noopener">🤗 Hugging Face</a>
        </div>
        <div class="cite-block">
          <button class="btn-cite" onclick="this.nextElementSibling.classList.toggle('show')">Cite this work</button>
          <pre class="cite-bibtex">@inproceedings{nakashole2026oshikwanyama,
  title={Sentiment Analysis and Language Models for Oshikwanyama},
  author={Nakashole, Ndapa},
  booktitle={Proceedings of LREC},
  year={2026}
}</pre>
        </div>
      </div>

      <div class="paper-card" data-sr>
        <div class="paper-venue">
          <span class="venue-tag">ACL 2025</span>
          <span class="award-tag">Outstanding Paper Award</span>
        </div>
        <h3>Typology-Guided Adaptation in Multilingual Models</h3>
        <div class="paper-links">
          <a href="https://ndapa.us/assets/docs/papers/2025-moi-acl.pdf" class="paper-link">PDF</a>
          <a href="https://github.com/okalai-ai/moimoe" class="paper-link">Data</a>
        </div>
        <div class="cite-block">
          <button class="btn-cite" onclick="this.nextElementSibling.classList.toggle('show')">Cite this work</button>
          <pre class="cite-bibtex">@inproceedings{nakashole2025typology,
  title={Typology-Guided Adaptation in Multilingual Models},
  author={Nakashole, Ndapa},
  booktitle={Proceedings of ACL},
  year={2025}
}</pre>
        </div>
      </div>
    </div>
    <div style="margin-top: 2rem;" data-sr>
      <a href="/research" class="btn btn-primary">All publications &rarr;</a>
    </div>
  </div>
</section>

<section id="models" class="section section-alt">
  <div class="container">
    <div class="section-header" data-sr>
      <span class="section-label">Layer 02 · Models</span>
      <h2>Models</h2>
      <p class="section-desc">Language models and other machine learning models for underrepresented languages and settings. One example from our current work:</p>
    </div>

    <div id="okalm" class="product-card" data-sr>
      <div class="product-info">
        <h3>OkaLM</h3>
        <p class="product-tagline">Kwanyama Language Models</p>
        <p>
          OkaLM is the first family of publicly available large language models for Kwanyama. Available in three sizes (1B, 3B, 8B parameters) to suit different use cases, from lightweight applications to more capable generation.
        </p>
        <div class="model-links">
          <a href="https://huggingface.co/okalai-ai/okalm-1b" class="btn btn-outline" target="_blank" rel="noopener">🤗 OkaLM-1B</a>
          <a href="https://huggingface.co/okalai-ai/okalm-3b" class="btn btn-outline" target="_blank" rel="noopener">🤗 OkaLM-3B</a>
          <a href="https://huggingface.co/okalai-ai/okalm-8b" class="btn btn-outline" target="_blank" rel="noopener">🤗 OkaLM-8B</a>
        </div>
        <a href="https://huggingface.co/okalai-ai" class="btn btn-primary" target="_blank" rel="noopener" style="margin-top: 1rem;">🤗 View on Hugging Face &rarr;</a>
      </div>
      <div class="product-stats">
        <div class="stat" data-sr>
          <span class="stat-number">3</span>
          <span class="stat-label">Model Sizes</span>
        </div>
        <div class="stat" data-sr>
          <span class="stat-number">1B–8B</span>
          <span class="stat-label">Parameters</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="tools" class="section">
  <div class="container">
    <div class="section-header" data-sr>
      <span class="section-label">Layer 03 · Tools and Data</span>
      <h2>Tools and Data</h2>
      <p class="section-desc">Data and interactive tools built on top of the models and novel datasets. One example from our current work:</p>
    </div>

    <div id="okalex" class="product-card" data-sr>
      <div class="product-info">
        <h3>OkaLex</h3>
        <p class="product-tagline">Kwanyama Language Reference and Learning Platform</p>
        <p>
          OkaLex is a Kwanyama language reference and interactive learning platform. It features a bilingual dictionary with translations, definitions, parts of speech, and example sentences.
        </p>
        <p>
          The platform includes interactive quizzes, flashcards, and a word-matching game for vocabulary practice, plus nearly 50 grammar modules for Kwanyama learners.
        </p>
        <p>
          For schools, linguists, and anyone exploring Kwanyama.
        </p>
        <a href="https://okalex.org/" class="btn btn-primary" target="_blank" rel="noopener">Visit OkaLex &rarr;</a>
      </div>
      <div class="try-it" data-sr>
        <p class="try-it-label">Try it — search a word</p>
        <div class="try-it-search">
          <input type="text" id="okalex-search" placeholder="e.g. water, mother, sun..." autocomplete="off" />
          <div class="try-it-toggle">
            <button class="toggle-btn active" data-lang="en">English</button>
            <button class="toggle-btn" data-lang="kw">Kwanyama</button>
          </div>
        </div>
        <div id="okalex-results" class="try-it-results"></div>
      </div>
    </div>
  </div>
</section>

<section id="applications" class="section section-alt">
  <div class="container">
    <div class="section-header" data-sr>
      <span class="section-label">Layer 04 · Applications</span>
      <h2>Applications</h2>
      <p class="section-desc">End-user systems that apply our research to real-world problems. Coming soon.</p>
    </div>
  </div>
</section>

<section id="about" class="section">
  <div class="container">
    <div class="section-header" data-sr>
      <span class="section-label">About</span>
      <h2>Who we are</h2>
    </div>
    <div data-sr>
      <p style="font-size: 1.1rem; line-height: 1.8; max-width: 680px;">
        Okalai AI was founded by <a href="https://ndapa.us" target="_blank" rel="noopener" style="color: #6c63ff; font-weight: 600;">Ndapa Nakashole</a>, who serves as Chief Scientist. Ndapa is an Associate Professor of Computer Science at the University of California, San Diego (UCSD). Her research focuses on Natural Language Processing (NLP), and Artificial Intelligence (AI) more broadly.
      </p>
    </div>
  </div>
</section>
