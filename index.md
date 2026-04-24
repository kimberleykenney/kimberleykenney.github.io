---
layout: default
title: Kimberley Kenney | Technical Writing Portfolio
---

<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
    color: #1f2933;
    background: #faf9f7;
    line-height: 1.6;
  }

  .portfolio-home {
    max-width: 880px;
    margin: 0 auto;
    padding: 72px 24px 96px;
  }

  .eyebrow {
    text-transform: uppercase;
    letter-spacing: 0.12em;
    font-size: 0.78rem;
    color: #6b7280;
    margin-bottom: 18px;
    font-weight: 600;
  }

  h1 {
    font-size: 3rem;
    line-height: 1.1;
    margin: 0 0 16px;
    color: #111827;
  }

  .intro {
    font-size: 1.2rem;
    max-width: 700px;
    color: #4b5563;
    margin-bottom: 44px;
  }

  .section-title {
    font-size: 1rem;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    color: #6b7280;
    margin-bottom: 18px;
    font-weight: 700;
  }

  .sample-grid {
    display: grid;
    gap: 18px;
  }

  .sample-card {
    display: block;
    padding: 24px 26px;
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 18px;
    text-decoration: none;
    color: inherit;
    box-shadow: 0 10px 30px rgba(17, 24, 39, 0.05);
    transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  }

  .sample-card:hover {
    transform: translateY(-3px);
    border-color: #c7cdd6;
    box-shadow: 0 14px 36px rgba(17, 24, 39, 0.09);
  }

  .sample-number {
    font-size: 0.78rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: #6b7280;
    font-weight: 700;
    margin-bottom: 8px;
  }

  .sample-card h2 {
    font-size: 1.28rem;
    margin: 0 0 8px;
    color: #111827;
  }

  .sample-card p {
    margin: 0;
    color: #4b5563;
  }

  .footer-note {
  margin-top: 56px;
  padding-top: 18px;
  border-top: 1px solid #e5e7eb;
  font-size: 0.9rem;
  color: #6b7280;
  font-style: italic;
  max-width: 680px;
}

  @media (max-width: 640px) {
    .portfolio-home {
      padding: 48px 20px 72px;
    }

    h1 {
      font-size: 2.25rem;
    }

    .intro {
      font-size: 1.05rem;
    }
  }
</style>

<main class="portfolio-home">

  <div class="eyebrow">Technical Writing Portfolio</div>

  <h1>Kimberley Kenney</h1>

  <p class="intro">
    Selected portfolio samples in help-center content, documentation strategy, and user-focused content design.
  </p>

  <div class="section-title">Samples</div>

  <section class="sample-grid">

    <a class="sample-card" href="/piece-1/">
      <div class="sample-number">Piece 1</div>
      <h2>Procedural Help-Center Article Audit and Rewrite</h2>
      <p>
        An audit and rewrite of an existing help-center article, focused on clarity, task flow, and user support.
      </p>
    </a>

    <a class="sample-card" href="/piece-2/">
      <div class="sample-number">Piece 2</div>
      <h2>Getting-Started Help-Center Article</h2>
      <p>
        A structured onboarding article designed to help users understand key card tasks and next steps.
      </p>
    </a>

    <a class="sample-card" href="/piece-3/">
      <div class="sample-number">Piece 3</div>
      <h2>Internal Documentation Recommendations Memo</h2>
      <p>
        A strategic internal memo identifying documentation gaps and recommending practical content improvements.
      </p>
    </a>

    <a class="sample-card" href="/piece-4/">
      <div class="sample-number">Piece 4</div>
      <h2>Internal Documentation Launch Brief</h2>
      <p>
        A launch-focused documentation brief showing how content can support product readiness and cross-functional alignment.
      </p>
    </a>

  </section>

  <p class="footer-note">
    Portfolio samples are for demonstration purposes and are based on publicly available information, reasonable product assumptions, and technical writing best practices.
  </p>

</main>
