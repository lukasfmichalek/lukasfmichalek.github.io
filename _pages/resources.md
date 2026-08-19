---
layout: default
title: "Resources"
permalink: /resources/
description: "Primers, records, and links for students and collaborators working in AFM and AFM-IR metrology of soft matter."
---

<section class="hero-sm on-navy" style="background:var(--navy-900); color:var(--on-navy);">
  <div class="wrap">
    <span class="eyebrow">Resources</span>
    <h1 style="color:#fff;">Learning materials &amp; records.</h1>
    <p class="hero-lede">A primer for students and collaborators entering nanoscale metrology, plus links to publication and profile records.</p>
  </div>
</section>

<section class="section">
  <div class="wrap">
    <div class="section-head">
      <h2>Primer</h2>
      <p>A practical, peer-reviewed starting point for anyone setting up nanomechanical AFM measurements on soft matter.</p>
    </div>
    <div class="res-grid">
      <div class="res-card" style="grid-column: 1 / -1;">
        <h3>A guide for nanomechanical characterization of soft matter via AFM: from mode selection to data reporting</h3>
        <p>E. Kim, A.L. Ramos Figueroa, M. Schrock, E. Zhang, Z. Bao, L. Michalek &middot; <em>STAR Protocols</em>, 2025 — mode selection, calibration, and data-reporting practice for quantitative AFM on soft materials.</p>
        <div class="res-meta">
          <span>Open access</span>
          <a class="btn-text" href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12166430/" target="_blank" rel="noopener">Read the protocol &rarr;</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section section-tinted">
  <div class="wrap">
    <div class="section-head">
      <h2>Profiles &amp; records</h2>
      <p>The most up-to-date publication lists, citation metrics, and code are kept on these external profiles rather than duplicated here.</p>
    </div>
    <div class="res-grid">
      {% for link in site.author.links %}
        {% unless link.label == "Email" %}
        <div class="res-card">
          <h3>{{ link.label }}</h3>
          <p>{% if link.label == "Google Scholar" %}Full publication list and citation metrics.{% elsif link.label == "ORCID" %}Persistent researcher identifier and verified publication record.{% elsif link.label == "LinkedIn" %}Professional background and affiliations.{% elsif link.label == "GitHub" %}Code and data-analysis pipelines as they are published.{% endif %}</p>
          <div class="res-meta">
            <span>&nbsp;</span>
            <a class="btn-text" href="{{ link.url }}" target="_blank" rel="noopener">Visit &rarr;</a>
          </div>
        </div>
        {% endunless %}
      {% endfor %}
    </div>
  </div>
</section>
