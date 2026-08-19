---
layout: default
title: "Methods"
permalink: /methods/
description: "The instruments and workflows behind the research — AFM, AFM-IR, and the data pipelines that turn raw signals into material properties."
---

<section class="hero-sm on-navy" style="background:var(--navy-900); color:var(--on-navy);">
  <div class="wrap">
    <span class="eyebrow">Methods &amp; platforms</span>
    <h1 style="color:#fff;">The instruments and workflows behind the science.</h1>
    <p class="hero-lede">A measurement-first approach: every project starts with a careful choice of technique, or combination of techniques, matched to the question at hand.</p>
  </div>
</section>

<section class="section">
  <div class="wrap">

    <div class="method-block">
      <div class="method-art">{% include art/scan.html %}</div>
      <div class="method-body">
        <span class="eyebrow">Primary platform</span>
        <h2 class="mt-0">Atomic Force Microscopy (AFM)</h2>
        <p>The workhorse technique. Tapping-mode, PeakForce QNM, and multi-frequency AFM are used for quantitative nanomechanical mapping of soft and polymeric materials, resolving modulus and viscoelastic contrast at length scales inaccessible to bulk methods.</p>
        <div class="accordion">
          <div class="accordion-label">Modes &amp; techniques</div>
          <details class="accordion-item" open>
            <summary>PeakForce Tapping + QNM</summary>
            <p>Quantitative nanomechanical mapping — modulus and adhesion contrast across polymer thin films, blends, and interpenetrating networks.</p>
          </details>
          <details class="accordion-item">
            <summary>Multi-Frequency AFM</summary>
            <p>Simultaneous multi-eigenmode excitation for viscoelastic (storage/loss) contrast without heavy reliance on contact-mechanics assumptions.</p>
          </details>
          <details class="accordion-item">
            <summary>Tapping / Amplitude Modulation (AM-AFM)</summary>
            <p>Topography and phase imaging for routine structural characterization of soft-matter surfaces and films.</p>
          </details>
        </div>
      </div>
    </div>

    <div class="method-block reverse">
      <div class="method-art">{% include art/wave.html %}</div>
      <div class="method-body">
        <span class="eyebrow">Chemical imaging</span>
        <h2 class="mt-0">AFM-IR (Photothermal Induced Resonance)</h2>
        <p>Our primary chemical-imaging platform, used to correlate nanomechanics with local chemical identity and to study photothermal heating of polymers directly at the tip.</p>
        <div class="accordion">
          <div class="accordion-label">Modes &amp; techniques</div>
          <details class="accordion-item" open>
            <summary>Contact-mode AFM-IR</summary>
            <p>Localized IR absorption spectra and chemical maps at spatial resolution well below the diffraction limit.</p>
          </details>
          <details class="accordion-item">
            <summary>Resonance-enhanced (tapping-mode) AFM-IR</summary>
            <p>Higher sensitivity chemical imaging for thin films and low-absorbance samples, used to resolve donor&ndash;acceptor phase separation in conjugated-polymer blends.</p>
          </details>
          <details class="accordion-item">
            <summary>Correlated AFM-IR + nanomechanics</summary>
            <p>Chemical and mechanical maps of the same field of view, connecting composition directly to local mechanical or thermal response — the approach behind our <a href="https://doi.org/10.1002/smll.202514518">localized thermomechanical AFM-IR</a> work.</p>
          </details>
        </div>
      </div>
    </div>

    <div class="method-block">
      <div class="method-art">{% include art/nanoscale.html %}</div>
      <div class="method-body">
        <span class="eyebrow">Complementary methods</span>
        <h2 class="mt-0">Beyond the probe</h2>
        <p>AFM and AFM-IR are the primary tools, but questions of bulk structure, transport, and device performance are addressed alongside collaborators using electron microscopy, scattering, and direct electrical characterization.</p>
        <div class="tag-row">
          <span class="tag">SEM / TEM</span>
          <span class="tag">X-ray scattering</span>
          <span class="tag">Electrical characterization</span>
        </div>
      </div>
    </div>

    <div class="method-block reverse">
      <div class="method-art">{% include art/layers.html %}</div>
      <div class="method-body">
        <span class="eyebrow">Computational pipeline</span>
        <h2 class="mt-0">Data analysis &amp; reporting</h2>
        <p>Raw AFM and AFM-IR data require careful, well-documented processing to yield quantitative, reproducible material properties — tip calibration, contact-mechanics inversion, and artifact correction, following community best practice.</p>
        <div class="accordion">
          <div class="accordion-label">Modes &amp; techniques</div>
          <details class="accordion-item" open>
            <summary>Tip calibration &amp; artifact correction</summary>
            <p>Thermal-noise spring-constant calibration and tip-radius tracking to keep quantitative maps comparable across sessions and samples.</p>
          </details>
          <details class="accordion-item">
            <summary>Reporting practice</summary>
            <p>Mode selection and data-reporting guidance summarized in our <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12166430/">STAR Protocols</a> guide for nanomechanical characterization of soft matter via AFM.</p>
          </details>
        </div>
      </div>
    </div>

  </div>
</section>
