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
    padding: 26px;
    box-shadow: 0 10px 30px rgba(17, 24, 39, 0.05);
  }

  .card p {
    margin-bottom: 10px;
  }

  .card p:last-child {
    margin-bottom: 0;
  }

  .finding-list {
    margin-top: 16px;
  }

  .finding-list li {
    margin-bottom: 16px;
  }

  .finding-list strong {
    color: #111827;
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
  <p><strong>Primary audience:</strong> Keep cardholders adding a card to a digital wallet for the first time</p>
</section>

<h2>Documentation Audit</h2>
<section class="card">

<h3>Project Context</h3>
<p>
  The original wallet setup article covers the correct task, but the workflow involves multiple systems, verification steps, and app switching. Users may need to retrieve card details from Keep, switch between Keep and their wallet app, and complete verification by SMS or email.
</p>

<p>
  <strong>Original article reviewed:</strong>
  <a href="https://help.trykeep.com/en/articles/10132858-how-to-add-your-keep-card-to-your-digital-wallet" target="_blank">View the original article</a>
</p>

<h3>Overview</h3>
<p>
  The article includes the core task information, but it is structured more like reference content than a task-focused guide. For first-time users, that increases effort and makes the setup flow harder to follow.
</p>

<h3>Key Findings</h3>
<ul class="finding-list">
  <li>
    <strong>App switching is not clearly guided.</strong> Users may lose their place when moving between Keep and their mobile wallet. The article should include explicit transitions that guide movement between apps.
  </li>
  <li>
    <strong>Prerequisites are incomplete.</strong> Users may begin setup without access to required details or verification methods, interrupting completion.
  </li>
  <li>
    <strong>Steps combine multiple actions or assume context.</strong> Instructions require interpretation instead of guiding users step by step.
  </li>
  <li>
    <strong>Platform-specific flows are not clearly separated.</strong> Users may struggle to quickly identify the correct path for their device.
  </li>
  <li>
    <strong>Screenshots are not fully integrated.</strong> Visuals are less effective without direct reference in the steps.
  </li>
  <li>
    <strong>Troubleshooting is too general.</strong> Common setup blockers are not addressed clearly or specifically.
  </li>
</ul>

<h3>Summary of Impact</h3>
<p>
  In its current form, the article creates unnecessary effort during a relatively simple setup task. The main usability issues are incomplete preparation guidance, weak app-switching cues, and instructions that require too much interpretation.
</p>

<p>
  Improving the article would reduce friction, increase successful completion, and reduce avoidable support requests.
</p>

<h3>Recommended Approach</h3>
<p>
  The article should adopt a task-based structure, include clear prerequisites, separate platform-specific flows, guide app switching explicitly, and include targeted troubleshooting.
</p>

</section>

<h2>Rewritten Article</h2>

<div class="article-wrap">
<section class="article-page">

<div class="article-kicker">Sample help-center article</div>

<h3>Add your Keep card to Apple Wallet or Google Wallet</h3>

<p>
  Use this article to add your Keep Corporate Card for contactless payments.
</p>

<p>
  Setup takes a few minutes and requires access to your card details and a verification code.
</p>

<h4>Before you begin</h4>
<ul>
  <li>Access to your Keep account</li>
  <li>Access to the card you want to add</li>
  <li>Apple Wallet or Google Wallet set up</li>
  <li>Access to your verification method</li>
</ul>

<div class="note-box">
  You may need to switch between Keep and your mobile wallet during setup.
</div>

<h4>Add your card on iPhone</h4>
<ol>
  <li>Open Apple Wallet</li>
  <li>Tap the + icon</li>
  <li>Enter card details from Keep</li>
  <li>Complete verification</li>
</ol>

<h4>Add your card on Android</h4>
<ol>
  <li>Open Google Wallet</li>
  <li>Add a new card</li>
  <li>Enter card details</li>
  <li>Complete verification</li>
</ol>

</section>
</div>

<p class="footer-note">
  This is an independent documentation sample created for portfolio purposes. It is based on publicly available information and reasonable product assumptions.
</p>

</main>
