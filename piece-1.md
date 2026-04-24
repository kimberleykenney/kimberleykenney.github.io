---
layout: default
title: Piece 1 — Procedural Help-Center Article Audit and Rewrite
permalink: /piece-1/
---

<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
    color: #1f2933;
    background: #faf9f7;
    line-height: 1.65;
  }

  .page {
    max-width: 920px;
    margin: 0 auto;
    padding: 64px 24px 96px;
  }

  .back-link {
    display: inline-block;
    margin-bottom: 32px;
    color: #6b7280;
    text-decoration: none;
    font-size: 0.95rem;
  }

  .back-link:hover {
    text-decoration: underline;
  }

  h1 {
    font-size: 2.6rem;
    margin-bottom: 16px;
    color: #111827;
  }

  h2 {
    font-size: 1.5rem;
    margin-top: 48px;
    margin-bottom: 14px;
    color: #111827;
  }

  h3 {
    font-size: 1.15rem;
    margin-top: 28px;
    color: #111827;
  }

  p, li {
    color: #374151;
  }

  .lede {
    font-size: 1.1rem;
    color: #4b5563;
    margin-bottom: 32px;
    max-width: 720px;
  }

  .card {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 18px;
    padding: 24px 26px;
    box-shadow: 0 10px 30px rgba(17, 24, 39, 0.05);
  }

  .card p {
    margin-bottom: 10px;
  }

  .card p:last-child {
    margin-bottom: 0;
  }

  .finding-list {
    list-style: none;
    padding: 0;
    margin-top: 16px;
  }

  .finding-list li {
    padding: 14px 0;
    border-top: 1px solid #e5e7eb;
  }

  .finding-list li:first-child {
    border-top: none;
    padding-top: 0;
  }

  .article-wrap {
    background: #f3f1ed;
    border-radius: 22px;
    padding: 24px;
  }

  .article-page {
    background: #ffffff;
    border-radius: 16px;
    padding: 36px;
    max-width: 720px;
    margin: 0 auto;
  }

  .article-kicker {
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: #6b7280;
    margin-bottom: 10px;
  }

  .note-box {
    background: #f9fafb;
    border-left: 4px solid #d1d5db;
    padding: 14px 16px;
    margin: 20px 0;
  }

  .footer-note {
    margin-top: 56px;
    padding-top: 16px;
    border-top: 1px solid #e5e7eb;
    font-size: 0.9rem;
    color: #6b7280;
    font-style: italic;
  }
</style>

<main class="page">

<a class="back-link" href="/">← Back to portfolio</a>

<h1>Piece 1 — Procedural Help-Center Article Audit and Rewrite</h1>

<p class="lede">
  This sample evaluates an existing help-center article and demonstrates how it can be improved for clarity, usability, and task completion.
</p>

<h2>Project Overview</h2>
<section class="card">
  <p><strong>Document type:</strong> Help-center procedural article audit and rewrite</p>
  <p><strong>Scenario:</strong> Fintech card setup with a multi-app workflow</p>
  <p><strong>Challenge:</strong> Transform reference-style content into task-based user guidance</p>
  <p><strong>Skills demonstrated:</strong> Content audit, user flow optimization, cross-platform documentation</p>
  <p><strong>Primary audience:</strong> First-time cardholders adding a card to a digital wallet</p>
</section>

<h2>Documentation Audit</h2>
<section class="card">

<h3>Project Context</h3>
<p>
  The setup requires switching between apps, retrieving card details, and completing verification. These steps introduce friction for first-time users.
</p>

<p>
  <strong>Original article:</strong>
  <a href="https://help.trykeep.com/en/articles/10132858-how-to-add-your-keep-card-to-your-digital-wallet" target="_blank">View source</a>
</p>

<h3>Key Findings</h3>
<ul class="finding-list">
  <li><strong>App switching is unclear.</strong> Users aren’t guided between Keep and wallet apps.</li>
  <li><strong>Missing prerequisites.</strong> Users may start without required information.</li>
  <li><strong>Steps lack clarity.</strong> Instructions combine actions or assume context.</li>
  <li><strong>Platform flows unclear.</strong> iPhone vs Android isn’t instantly obvious.</li>
  <li><strong>Visuals underused.</strong> Screenshots aren’t integrated into steps.</li>
  <li><strong>Weak troubleshooting.</strong> Common issues aren’t addressed directly.</li>
</ul>

<h3>Impact</h3>
<p>
  These issues increase friction and make a simple setup feel more complex than necessary.
</p>

<h3>Recommended Approach</h3>
<p>
  Use a task-based structure, clearer steps, better platform separation, and targeted troubleshooting.
</p>

</section>

<h2>Rewritten Article</h2>

<div class="article-wrap">
<section class="article-page">

<div class="article-kicker">Sample help-center article</div>

<h3>Add your card to Apple Wallet or Google Wallet</h3>

<p>
  Add your card for contactless payments. Setup takes a few minutes.
</p>

<h4>Before you begin</h4>
<ul>
  <li>Access to your account</li>
  <li>Your card details</li>
  <li>Wallet app installed</li>
  <li>Access to verification method</li>
</ul>

<div class="note-box">
  You may need to switch between apps during setup.
</div>

<h4>iPhone</h4>
<ol>
  <li>Open Apple Wallet</li>
  <li>Tap +</li>
  <li>Enter card details from Keep</li>
  <li>Verify via code</li>
</ol>

<h4>Android</h4>
<ol>
  <li>Open Google Wallet</li>
  <li>Add card</li>
  <li>Enter details</li>
  <li>Verify</li>
</ol>

</section>
</div>

<p class="footer-note">
  This sample is independently created for demonstration purposes and is based on publicly available information and reasonable assumptions.
</p>

</main>
