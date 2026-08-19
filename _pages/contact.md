---
layout: default
title: "Contact"
permalink: /contact/
description: "Get in touch with Lukas Michalek — Research Scientist, Bao Group & nano@Stanford."
---

<section class="hero-sm on-navy" style="background:var(--navy-900); color:var(--on-navy);">
  <div class="wrap">
    <span class="eyebrow">Contact</span>
    <h1 style="color:#fff;">Let's talk.</h1>
    <p class="hero-lede">Whether you're a prospective student, a potential collaborator, or just have a question about the work — I'd like to hear from you.</p>
  </div>
</section>

<section class="section">
  <div class="wrap contact-layout">
    <div>
      <h2 class="mt-0">Get in touch</h2>

      <div class="contact-item">
        <span class="ic">&#9993;</span>
        <div>
          <div class="label">Email</div>
          <div class="val"><a href="mailto:{{ site.email }}">{{ site.email }}</a></div>
        </div>
      </div>

      <div class="contact-item">
        <span class="ic">&#127970;</span>
        <div>
          <div class="label">Affiliation</div>
          <div class="val">{{ site.author.bio }}</div>
        </div>
      </div>

      <div class="contact-item">
        <span class="ic">&#128205;</span>
        <div>
          <div class="label">Location</div>
          <div class="val">{{ site.author.location }}</div>
        </div>
      </div>

      <div class="contact-item">
        <span class="ic">&#128279;</span>
        <div>
          <div class="label">Elsewhere</div>
          <div class="val">
            <div class="social-row">
              {% for link in site.author.links %}
                {% unless link.label == "Email" %}
                <a href="{{ link.url }}" target="_blank" rel="noopener">{{ link.label }}</a>
                {% endunless %}
              {% endfor %}
            </div>
          </div>
        </div>
      </div>

      <a class="btn btn-primary" style="margin-top:8px;" href="mailto:{{ site.email }}">Email me &rarr;</a>
    </div>

    <div class="about-callout" style="margin-top:0;">
      <h3>Prospective students &amp; collaborators</h3>
      <p>If you're interested in nanoscale metrology of soft matter or soft electronic materials — as a student, a collaborator, or an industry partner with a measurement challenge — email is the fastest way to reach me. A brief note on your background and what you're working on is the best way to start the conversation.</p>
    </div>
  </div>
</section>
