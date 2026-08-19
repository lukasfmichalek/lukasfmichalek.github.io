---
layout: default
title: "About"
permalink: /about/
description: "Dr. Lukas Michalek — Research Scientist, Bao Group & nano@Stanford, Stanford University."
---

<section class="hero-sm on-navy" style="background:var(--navy-900); color:var(--on-navy);">
  <div class="wrap">
    <h1 style="color:#fff;">Lukas Michalek</h1>
    <p class="hero-lede">Research Scientist &middot; Bao Group &amp; nano@Stanford &middot; Stanford University</p>
  </div>
</section>

<section class="section">
  <div class="wrap about-layout">
    <div class="about-body">
      <p class="callout">{{ site.author.bio }}</p>

      <h3 style="margin-top:36px;">Why</h3>
      <p>Soft electronic and soft-matter materials — stretchable conductors, conjugated polymer blends, interpenetrating networks — are heterogeneous by nature, and most characterization tools were built for hard, crystalline solids. Applying them uncritically to soft matter produces artifacts, not insight. Closing that gap is the problem this work is aimed at.</p>

      <h3>What</h3>
      <p>The work develops and applies nanoscale measurement methods — principally atomic force microscopy (AFM) and AFM-IR (photothermal induced resonance) — to understand structure, mechanics, and chemistry at polymer interfaces and in soft electronic devices, in collaboration with the Bao Group and nano@Stanford.</p>

      <h3>How</h3>
      <p>The approach is measurement-first: pushing instruments to their limits, building quantitative models that connect raw signals to material properties, and working closely with synthesis and device partners so that metrology stays connected to real materials questions.</p>

      <div class="about-callout">
        <h3>Background</h3>
        <p>Training in materials science and polymer chemistry, with research spanning photochemistry and polymer surface grafting (Barner-Kowollik group, QUT / Karlsruhe) before moving into nanoscale metrology of soft electronic materials at Stanford. Full record of affiliations and co-authors is on <a href="https://scholar.google.com/citations?user=Bzq4YZ0AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a> and <a href="https://orcid.org/0000-0002-2257-5038" target="_blank" rel="noopener">ORCID</a>.</p>
      </div>
    </div>

    <aside>
      <div class="about-photo">
        <img src="{{ site.author.avatar | relative_url }}" alt="Portrait of Lukas Michalek">
      </div>
      <dl class="about-side">
        <dt>Position</dt>
        <dd>Research Scientist &mdash; Bao Group &amp; nano@Stanford</dd>
        <dt>Affiliation</dt>
        <dd>Stanford University</dd>
        <dt>Location</dt>
        <dd>{{ site.author.location }}</dd>
        <dt>Find me on</dt>
        <dd>
          <div class="social-row">
            {% for link in site.author.links %}
              {% unless link.label == "Email" %}
              <a href="{{ link.url }}" target="_blank" rel="noopener">{{ link.label }}</a>
              {% endunless %}
            {% endfor %}
          </div>
        </dd>
      </dl>
    </aside>
  </div>
</section>
