---
layout: default
title: Home
---

<section class="hero">
  <div class="container hero-columns">
    <div class="hero-inner">
      <div class="hero-badge" data-sr>Applied AI Research</div>
      <h1 data-sr>Building AI for every language.</h1>
      <p class="hero-sub" data-sr>
        We research and build language technology where today's LLMs fall short,
        the thousands of languages left behind by state-of-the-art AI.
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

<section id="news" class="news-ticker">
  <div class="container">
    <div class="news-items">
      <div class="news-item">
        <span class="news-date">Mar 2026</span>
        <span class="news-text">African language reference and learning platform for Bantu languages</span>
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
      <span class="section-label">Research</span>
      <h2>Publications</h2>
      <p class="section-desc">Our work spans multilingual LLMs, typological adaptation, and low-resource NLP.</p>
    </div>

    <div class="papers">
      <div class="paper-card" data-sr>
        <div class="paper-venue"><span class="venue-tag">LREC 2026</span></div>
        <h3>Sentiment Analysis and Language Models for Kwanyama</h3>
        <p class="paper-detail">1B, 3B, and 8B parameter LLMs for Kwanyama, the first large language models for Kwanyama of this scale.</p>
        <p class="paper-author">Ndapa Nakashole</p>
        <div class="cite-block">
          <button class="btn-cite" onclick="this.nextElementSibling.classList.toggle('show')">Cite this work</button>
          <pre class="cite-bibtex">@inproceedings{nakashole2026kwanyama,
  title={Sentiment Analysis and Language Models for Kwanyama},
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
        <p class="paper-detail">Leveraging linguistic typology to improve cross-lingual transfer in multilingual models.</p>
        <p class="paper-author">Ndapa Nakashole</p>
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

<section id="products" class="section section-alt">
  <div class="container">
    <div class="section-header" data-sr>
      <span class="section-label">Products</span>
      <h2>Research in production</h2>
      <p class="section-desc">From the first family of Kwanyama LLMs to interactive language tools, our research, deployed for real users.</p>
    </div>

    <div class="product-card" data-sr>
      <div class="product-info">
        <h3>OkaLM</h3>
        <p class="product-tagline">Kwanyama Language Models</p>
        <p>
          OkaLM is the first family of publicly available large language models for Kwanyama. Available in three sizes (1B, 3B, 8B parameters) to suit different use cases, from lightweight applications to more capable generation.
        </p>
        <div class="model-links">
          <a href="https://huggingface.co/okalai-ai/okalm-1b" class="btn btn-outline" target="_blank" rel="noopener">OkaLM-1B</a>
          <a href="https://huggingface.co/okalai-ai/okalm-3b" class="btn btn-outline" target="_blank" rel="noopener">OkaLM-3B</a>
          <a href="https://huggingface.co/okalai-ai/okalm-8b" class="btn btn-outline" target="_blank" rel="noopener">OkaLM-8B</a>
        </div>
        <a href="https://huggingface.co/okalai-ai" class="btn btn-primary" target="_blank" rel="noopener" style="margin-top: 1rem;">View on Hugging Face &rarr;</a>

        <div class="try-it" data-sr>
          <p class="try-it-label">Try it — generate Kwanyama text with OkaLM-8B</p>
          <div class="try-it-search">
            <input type="text" id="okalm-input" placeholder="Start typing a Kwanyama phrase..." autocomplete="off" />
            <button class="btn btn-primary" id="okalm-generate" style="white-space: nowrap;">Generate</button>
          </div>
          <div id="okalm-results" class="try-it-results"></div>
        </div>
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

    <div class="product-card" data-sr style="margin-top: 3rem;">
      <div class="product-info">
        <h3>OkaLex</h3>
        <p class="product-tagline">African Language Reference and Learning Platform</p>
        <p>
          OkaLex is a  language reference and interactive learning platform for Bantu languages. It currently features bilingual dictionaries for six languages: Kwanyama, Ndonga, Umbundu, Sukuma, Xhosa, and Zulu — each with translations, definitions, parts of speech, and example sentences.
        </p>
        <p>
          Each language includes interactive quizzes, flashcards, and a word-matching game for vocabulary practice. The  language learning aspect is  most developed for Kwanyama, with nearly 50 grammar modules.
        </p>
        <p>
          For schools, linguists, and anyone exploring Bantu languages.
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
