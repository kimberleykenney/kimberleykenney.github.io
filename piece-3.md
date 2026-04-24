---
layout: default
title: Piece 3 — Internal Documentation Recommendations Memo
permalink: /piece-3/
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
  .article-page {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    box-shadow: 0 10px 30px rgba(17, 24, 39, 0.05);
  }

  .summary-card {
    border-radius: 18px;
    padding: 24px 26px;
    margin: 28px 0 48px;
  }

  .summary-card p {
    margin: 0 0 10px;
  }

  .summary-card p:last-child {
    margin-bottom: 0;
  }

  .card-title {
    text-transform: uppercase;
    letter-spacing: 0.1em;
    font-size: 0.75rem;
    color: #6b7280;
    font-weight: 700;
    margin-bottom: 14px;
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

  .article-page h3 {
    font-size: 2rem;
    line-height: 1.18;
    margin-top: 0;
    margin-bottom: 16px;
  }

  .memo-divider {
    border-top: 1px solid #e5e7eb;
    padding-top: 18px;
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

  h2.section-break {
    border-top: 1px solid #e5e7eb;
    padding-top: 40px;
    margin-top: 64px;
  }

  .article-page ol > li {
    margin-bottom: 18px;
  }

  @media (max-width: 900px) {
    .article-page {
      padding: 32px 36px;
    }
  }

  @media (max-width: 640px) {
    .page {
      padding: 44px 20px 72px;
    }

    h1 {
      font-size: 2.1rem;
    }

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

<h1>Piece 3 — Internal Documentation Recommendations Memo</h1>

<p class="lede">
  This sample evaluates the current Keep card setup documentation and demonstrates how an internal memo can identify structural gaps and recommend a clearer documentation model for onboarding and support.
</p>

<section class="summary-card">
  <div class="card-title">Project Overview</div>
  <p><strong>Document type:</strong> Internal documentation recommendations memo</p>
  <p><strong>Scenario:</strong> Fragmented card setup documentation across public help-center sections</p>
  <p><strong>Challenge:</strong> Recommend a clearer documentation model that supports onboarding, discoverability, and task completion</p>
  <p><strong>Skills demonstrated:</strong> Content strategy, information architecture, documentation planning</p>
  <p><strong>Primary audience:</strong> Product, support, and documentation stakeholders responsible for card-related user education</p>
</section>

<h2 class="section-break">Recommendations Memo</h2>

<div class="article-wrap">
<section class="article-page">

<h3>Recommendations for improving Keep card setup documentation</h3>

<h4 class="memo-divider">Summary</h4>

<p>
  The current Keep card setup documentation includes useful task-based articles, but the experience is fragmented across multiple sections and does not provide a clear starting point for newly approved users.
</p>

<p>
  In the Cards area, users can find core setup content such as physical card ordering, activation, digital wallet setup, and card detail viewing. Related setup and support topics, however, are distributed elsewhere. Spending limits appear under Managing Your Card, while virtual card ordering and declined-transaction content appear under Issues & Troubleshooting.
</p>

<p>I recommend restructuring the card documentation around a three-layer model:</p>

<ul>
  <li>a getting-started entry point for new users</li>
  <li>task-based procedural articles for core setup actions</li>
  <li>companion troubleshooting content for high-friction tasks</li>
</ul>

<p>
  This model would improve discoverability, support task completion, and better separate admin setup decisions from cardholder task execution.
</p>

<h4 class="memo-divider">Current-state observations</h4>

<ol>
  <li>
    <strong>The setup flow is split across sections</strong>
    <p>The current Cards landing page includes the setup tasks users would expect, but they are not grouped around the actual setup journey.</p>
    <p>For example, physical card ordering, activation, digital wallet setup, and card detail viewing appear under Getting Started, while virtual card ordering is listed under Issues & Troubleshooting and spending limits appear under Managing Your Card. A user trying to complete initial setup may need to move between multiple sections to finish one flow.</p>
  </li>

  <li>
    <strong>The current model is task-based, but not onboarding-oriented</strong>
    <p>The existing articles function as standalone procedural content. That is useful, but it does not answer the broader onboarding question: “I’ve been approved — what do I do first?”</p>
  </li>

  <li>
    <strong>Admin and cardholder tasks are blended</strong>
    <p>Some tasks are clearly admin-led, such as adding users, assigning roles, ordering cards, and setting limits. Others are more likely to be completed by the cardholder, such as activation, viewing card details, and adding a card to a digital wallet. The current structure does not clearly distinguish those audiences within the setup experience.</p>
  </li>

  <li>
    <strong>Related guidance exists, but it is not unified</strong>
    <p>Keep’s public Admin Guide includes steps for creating cards, setting spending limits, adding users, and assigning roles. It also links to resources such as virtual card ordering, physical card ordering, digital wallet setup, card details, and spending limits. The content needed for a more complete setup experience exists, but it is split across the Cards section, Account Management topics, and the Admin Guide rather than being presented as a unified setup model.</p>
  </li>
</ol>

<h4 class="memo-divider">Recommended documentation model</h4>

<p>I recommend organizing the card setup documentation into three layers.</p>

<ol>
  <li>
    <strong>Getting-started documentation</strong>
    <p>A single entry-point article for newly approved users that explains:</p>
    <ul>
      <li>who the article is for</li>
      <li>the recommended setup order</li>
      <li>when to choose a virtual card, a physical card, or both</li>
      <li>which detailed article to open next</li>
    </ul>
    <p><strong>Recommended article:</strong></p>
    <p>Getting started with Keep cards</p>
  </li>

  <li>
    <strong>Task-based procedural documentation</strong>
    <p>Use detailed how-to articles for the core setup tasks.</p>
    <p><strong>Recommended article set:</strong></p>
    <ul>
      <li>How to Create a Virtual Keep Card</li>
      <li>How to Order a Physical Keep Card</li>
      <li>How to Activate Your Keep Card</li>
      <li>How to Add Your Keep Card to a Digital Wallet</li>
      <li>How to View Your Keep Card Details</li>
      <li>How to Add Team Members to Your Keep Account</li>
      <li>How to Set Spending Limits on Keep Cards</li>
    </ul>
  </li>

  <li>
    <strong>Support and troubleshooting documentation</strong>
    <p>Create companion troubleshooting content for high-friction or high-support tasks.</p>
    <p><strong>Recommended article set:</strong></p>
    <ul>
      <li>Troubleshooting Digital Wallet Setup</li>
      <li>Why a Keep Card Transaction Was Declined</li>
      <li>Troubleshooting Card Verification Issues</li>
      <li>How to Replace a Lost or Stolen Keep Card</li>
    </ul>
  </li>
</ol>

<h4 class="memo-divider">Priority recommendations</h4>

<p><strong>Priority 1: Create a getting-started article</strong></p>

<p>
  The highest-priority gap is the absence of a clear entry point in the Cards documentation for newly approved users.
</p>

<p><strong>Priority 2: Reposition virtual card creation within setup content</strong></p>

<p>
  Virtual card ordering is currently listed under Issues & Troubleshooting, even though it functions as a setup task rather than a troubleshooting topic.
</p>

<p><strong>Priority 3: Connect admin setup topics more directly to the Cards experience</strong></p>

<p>
  Because adding users, assigning roles, and setting spending limits already exist in the public Admin Guide and related account documentation, they should be linked more directly into the card setup journey for admins.
</p>

<p><strong>Priority 4: Add companion troubleshooting content for high-friction tasks</strong></p>

<p>
  Digital wallet setup and declined transactions would benefit from clearer companion troubleshooting content that supports the main procedural articles without overloading them.
</p>

<h4 class="memo-divider">Expected impact</h4>

<p>A more coherent card documentation structure would likely improve:</p>

<ul>
  <li>first-time setup for newly approved users</li>
  <li>clarity around virtual versus physical card setup</li>
  <li>discoverability of admin tasks such as adding users and setting limits</li>
  <li>navigation between setup, management, and troubleshooting content</li>
  <li>support readiness for wallet and transaction issues</li>
</ul>

<h4 class="memo-divider">Recommendation and next steps</h4>

<p>
  The strongest next step is to treat card setup as a guided documentation flow rather than a collection of standalone articles.
</p>

<p>
  Start by creating the getting-started entry point, reposition virtual card setup within the setup journey, and connect admin-related topics more directly to the Cards experience. Then add focused troubleshooting companions for the highest-friction tasks.
</p>

<ul>
  <li>Create the getting-started article as the main entry point for card setup</li>
  <li>Confirm the minimum required article set for virtual cards, physical cards, and admin-led team setup</li>
  <li>Reposition or cross-link virtual card creation into the setup flow</li>
  <li>Add troubleshooting companions for wallet setup and declined transactions</li>
  <li>Review cross-linking across the Cards section, Admin Guide, and Account Management content to support a clearer user journey</li>
</ul>

</section>
</div>

<p class="footer-note">
  This is an independent documentation sample created for portfolio purposes. It is based on publicly available information and reasonable product assumptions. It is not affiliated with or endorsed by Keep.
</p>

</main>
