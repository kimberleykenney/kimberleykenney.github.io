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
    max-width: 940px;
    margin: 0 auto;
    padding: 64px 24px 96px;
  }

  .back-link {
    display: inline-block;
    margin-bottom: 36px;
    color: #6b7280;
    text-decoration: none;
    font-size: 0.95rem;
  }

  .back-link:hover {
    text-decoration: underline;
  }

  h1 {
    font-size: 2.65rem;
    line-height: 1.12;
    margin: 0 0 18px;
    color: #111827;
  }

  h2 {
    font-size: 1.55rem;
    margin-top: 56px;
    margin-bottom: 18px;
    color: #111827;
  }

  h3 {
    font-size: 1.2rem;
    margin-top: 34px;
    color: #111827;
  }

  h4 {
    font-size: 1rem;
    margin-top: 28px;
    color: #111827;
  }

  p, li {
    font-size: 1rem;
    color: #374151;
  }

  ul, ol {
    padding-left: 1.35rem;
  }

  li {
    margin-bottom: 8px;
  }

  .lede {
    font-size: 1.12rem;
    color: #4b5563;
    max-width: 780px;
    margin-bottom: 28px;
  }

  .summary-card,
  .content-card,
  .finding,
  .article-page {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    box-shadow: 0 10px 30px rgba(17, 24, 39, 0.05);
  }

  .summary-card {
    border-radius: 18px;
    padding: 24px 26px;
    margin: 28px 0 34px;
  }

  .summary-card p {
    margin: 0 0 10px;
  }

  .summary-card p:last-child {
    margin-bottom: 0;
  }

  .content-card {
    border-radius: 18px;
    padding: 30px;
    margin-top: 24px;
  }

  .finding-grid {
    display: grid;
    gap: 16px;
    margin-top: 20px;
  }

  .finding {
    border-radius: 16px;
    padding: 20px 22px;
  }

  .finding p {
    margin: 0 0 10px;
  }

  .finding p:last-child {
    margin-bottom: 0;
  }

  .finding strong {
    color: #111827;
  }

  .article-wrap {
    background: #f3f1ed;
    border-radius: 24px;
    padding: 28px;
    margin-top: 24px;
  }

  .article-page {
    max-width: 760px;
    margin: 0 auto;
    border-radius: 18px;
    padding: 42px 46px;
  }

  .article-kicker {
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: #6b7280;
    font-size: 0.78rem;
    font-weight: 700;
    margin-bottom: 14px;
  }

  .article-page h3 {
    font-size: 2rem;
    line-height: 1.18;
    margin-top: 0;
    margin-bottom: 16px;
  }

  .note-box {
    background: #f9fafb;
    border-left: 4px solid #d1d5db;
    padding: 16px 18px;
    margin: 22px 0;
  }

  .related {
    margin-top: 40px;
  }

  .footer-note {
    margin-top: 56px;
    padding-top: 18px;
    border-top: 1px solid #e5e7eb;
    font-size: 0.9rem;
    color: #6b7280;
    font-style: italic;
    max-width: 760px;
  }

  @media (max-width: 640px) {
    .page {
      padding: 44px 20px 72px;
    }

    h1 {
      font-size: 2.1rem;
    }

    .content-card,
    .article-page {
      padding: 24px;
    }

    .article-wrap {
      padding: 16px;
    }
  }
</style>

<main class="page">

<a class="back-link" href="/">← Back to portfolio</a>

<h1>Piece 1 — Procedural Help-Center Article Audit and Rewrite</h1>

<p class="lede">
  This portfolio sample evaluates an existing help-center article and rewrites it into a clearer, more task-focused support article.
</p>

<section class="summary-card">
  <p><strong>Document type:</strong> Help-center procedural article audit and rewrite</p>
  <p><strong>Scenario:</strong> Fintech card setup with a multi-app workflow</p>
  <p><strong>Challenge:</strong> Transform reference-style content into task-based user guidance</p>
  <p><strong>Skills demonstrated:</strong> Content audit, user flow optimization, cross-platform documentation</p>
  <p><strong>Primary audience:</strong> Keep cardholders adding a Keep card to Apple Wallet or Google Wallet for the first time</p>
</section>

<section class="content-card">

<h2>Project Context</h2>

<p>
  The original wallet setup article covers the correct task, but the workflow involves multiple systems, verification steps, and app switching. Users may need to retrieve card details from Keep, switch between Keep and their wallet app, and complete verification by SMS or email.
</p>

<p>
  This sample demonstrates both content evaluation and rewriting for usability.
</p>

<p>
  <strong>Original article reviewed:</strong>
  <a href="https://help.trykeep.com/en/articles/10132858-how-to-add-your-keep-card-to-your-digital-wallet" target="_blank">View the original article</a>
</p>

</section>

<h2>Documentation Audit</h2>

<section class="content-card">

<p><strong>Feature:</strong> Add Keep Card to Digital Wallet</p>
<p><strong>Product:</strong> Keep Corporate Card</p>
<p><strong>Document type:</strong> Help-center procedural article</p>

<h3>Overview</h3>

<p>
  The existing article helps users add a Keep Corporate Card to Apple Wallet or Google Wallet for contactless payments. The task is straightforward, but the experience includes several friction points: users may need to retrieve card details from Keep, switch between Keep and their wallet app, and complete verification by SMS or email.
</p>

<p>
  The article includes the core task information, but it is structured more like reference content than a task-focused guide. For first-time users, that increases effort and makes the setup flow harder to follow.
</p>

<h3>Key Findings</h3>

<div class="finding-grid">

  <div class="finding">
    <p><strong>1. App switching is not clearly guided</strong></p>
    <p><strong>Why it matters:</strong> Users may lose their place when moving between Keep and their mobile wallet to retrieve and enter card details.</p>
    <p><strong>Recommended fix:</strong> Add explicit transitions that tell users when to open Keep, when to return to the wallet app, and what to do next.</p>
  </div>

  <div class="finding">
    <p><strong>2. Prerequisites are incomplete</strong></p>
    <p><strong>Why it matters:</strong> Users may begin setup without access to verification methods or card details, which interrupts task completion.</p>
    <p><strong>Recommended fix:</strong> Add realistic prerequisites such as Keep account access and access to the phone number or email used for verification.</p>
  </div>

  <div class="finding">
    <p><strong>3. Steps combine multiple actions or assume context</strong></p>
    <p><strong>Why it matters:</strong> Users must interpret what screen they are on or what action comes next.</p>
    <p><strong>Recommended fix:</strong> Break instructions into smaller steps and use clearer screen and action cues.</p>
  </div>

  <div class="finding">
    <p><strong>4. Platform-specific flows are separated but not strongly signposted</strong></p>
    <p><strong>Why it matters:</strong> Users scanning the page may take longer to find the correct instructions for their device.</p>
    <p><strong>Recommended fix:</strong> Add clearer section labels for iPhone and Android flows.</p>
  </div>

  <div class="finding">
    <p><strong>5. Screenshots are not fully integrated into the instructions</strong></p>
    <p><strong>Why it matters:</strong> Visuals are less useful when they are not referenced directly in the steps.</p>
    <p><strong>Recommended fix:</strong> Add captions or callouts that show what the user should look for in each image.</p>
  </div>

  <div class="finding">
    <p><strong>6. Troubleshooting is too general</strong></p>
    <p><strong>Why it matters:</strong> Users may need support for common setup issues that the article does not address directly.</p>
    <p><strong>Recommended fix:</strong> Add troubleshooting for verification delays, difficulty locating card details, and repeated data-entry errors.</p>
  </div>

</div>

<h3>Summary of Impact</h3>

<p>
  In its current form, the article creates unnecessary effort during a relatively simple setup task. The main usability issues are incomplete preparation guidance, weak app-switching cues, and instructions that require too much interpretation.
</p>

<p>Improving the article would likely:</p>

<ul>
  <li>reduce friction for first-time setup</li>
  <li>increase successful wallet setup completion</li>
  <li>make screenshots more useful as instructional support</li>
  <li>reduce avoidable support questions</li>
</ul>

<h3>Recommended Approach</h3>

<p>To improve usability, the article should:</p>

<ul>
  <li>open with a task-focused introduction</li>
  <li>include practical prerequisites</li>
  <li>separate iPhone and Android flows clearly</li>
  <li>use shorter, more explicit steps</li>
  <li>guide users through switching between Keep and their wallet app</li>
  <li>include troubleshooting for common setup blockers</li>
  <li>move secondary or related content below the main task flow</li>
</ul>

</section>

<h2>Rewritten Article</h2>

<div class="article-wrap">
<section class="article-page">

<div class="article-kicker">Sample help-center article</div>

<h3>Add your Keep card to Apple Wallet or Google Wallet</h3>

<p>
  Use this article to add your Keep Corporate Card to Apple Wallet or Google Wallet for contactless payments.
</p>

<p>
  Setup usually takes a few minutes and requires access to your card details and a verification code.
</p>

<h4>Before you begin</h4>

<p>Make sure you have:</p>

<ul>
  <li>access to your Keep account</li>
  <li>access to the Keep card you want to add</li>
  <li>Apple Wallet or Google Wallet already set up on your device</li>
  <li>access to the phone number or email address used for verification</li>
</ul>

<div class="note-box">
  <p><strong>Note:</strong> You may need to switch between Keep and your mobile wallet during setup to view and enter your card details.</p>
</div>

<h4>Add your card on iPhone</h4>

<ol>
  <li>Open Apple Wallet.</li>
  <li>Tap the + icon.</li>
  <li>Tap Debit or Credit Card, then tap Continue.</li>
  <li>Tap Enter Card Details Manually.</li>
  <li>In a browser, sign in to Keep and open the card you want to add.</li>
  <li>Select Show details to view the card number, expiration date, and CVC.</li>
  <li>Return to Apple Wallet and enter the card details.</li>
  <li>Follow the prompts to verify the card by SMS or email.</li>
  <li>Enter the verification code when prompted.</li>
</ol>

<p>Your card is now ready to use for contactless payments.</p>

<h4>Add your card on Android</h4>

<ol>
  <li>Open Google Wallet.</li>
  <li>Tap Add to Wallet.</li>
  <li>Tap Payment card, then tap New credit or debit card.</li>
  <li>In a browser, sign in to Keep and open the card you want to add.</li>
  <li>Select Show details to view the card number, expiration date, and CVC.</li>
  <li>Return to Google Wallet and enter the card details.</li>
  <li>Review and accept the terms.</li>
  <li>Choose a verification method if prompted.</li>
  <li>Enter the verification code when prompted.</li>
</ol>

<p>Your card is now ready to use.</p>

<h4>Troubleshooting</h4>

<p><strong>I did not receive a verification code</strong></p>

<ul>
  <li>Confirm that you have access to the phone number or email address used for verification.</li>
  <li>Wait a few minutes, then request a new code.</li>
  <li>Check your spam or junk folder if the code was sent by email.</li>
</ul>

<p><strong>My card details are not being accepted</strong></p>

<ul>
  <li>Re-enter the card number, expiration date, and CVC exactly as shown in Keep.</li>
  <li>Make sure you are adding the correct card.</li>
  <li>If the problem continues, contact support.</li>
</ul>

<p><strong>I cannot find my card details</strong></p>

<ol>
  <li>Sign in to Keep.</li>
  <li>Open the card you want to add.</li>
  <li>Select Show details.</li>
</ol>

<p><strong>Still need help?</strong></p>

<p>Contact Keep Support.</p>

<h4 class="related">Related articles</h4>

<ul>
  <li>Getting started with Keep cards</li>
  <li>How to view your Keep card details</li>
  <li>Troubleshooting digital wallet setup</li>
  <li>Supported wallets and mobile payment options</li>
</ul>

</section>
</div>

<p class="footer-note">
  This is an independent documentation sample created for portfolio purposes. It is based on publicly available information, reasonable product assumptions, and technical writing best practices. It is not affiliated with or endorsed by Keep. Image placement, UI labels, and related links are representational.
</p>

</main>
