---
title: Home
layout: default
---

<!-- Inline CSS: temporary but forces the hero to appear instantly -->
<style>
/* Hide default theme header */
.page-header, .jumbotron, .site-head, .page-head, .hero-banner { display:none !important; }
.site-content { margin-top: 0 !important; }

/* Hero forced styling */
#hero-wrapper.hero {
  position: relative;
  display: grid;
  grid-template-columns: 200px 1fr;
  gap: 24px;
  align-items: center;
  padding: 48px 20px;
  color: #fff;
  overflow: hidden;
  z-index: 10;
  background: linear-gradient(180deg, #0b6b7a, #128b63);
}

/* optional background image (ensure /assets/hero-bg.jpg exists) */
#hero-wrapper .hero-bg {
  position: absolute; inset:0;
  background-image: url('/assets/hero-bg.jpg');
  background-size: cover; background-position:center;
  opacity: 0.14; z-index:0; filter: saturate(.95) blur(.7px);
}

/* profile column */
#hero-wrapper .profile { position: relative; z-index: 2; display:flex; flex-direction:column; align-items:center; text-align:center; }
#hero-wrapper .profile img { width:150px; height:150px; border-radius:50%; object-fit:cover; border:5px solid rgba(255,255,255,0.12); box-shadow:0 8px 22px rgba(0,0,0,0.35); }

/* about column */
#hero-wrapper .about { position: relative; z-index: 2; padding-right: 8px; max-width: 980px; }
#hero-wrapper .about .lead { font-size:1rem; margin:0 0 10px; color: rgba(255,255,255,0.95); }

/* buttons & small layout */
.btn-cta { background:#0e8aa8; color:white; padding:8px 12px; border-radius:8px; text-decoration:none; font-weight:600; margin-right:8px; }
.btn-ghost { background:transparent; color:#eaf6fb; padding:7px 10px; border-radius:8px; border:1px solid rgba(255,255,255,0.12); text-decoration:none; font-weight:600; }

/* responsive */
@media (max-width:880px) {
  #hero-wrapper.hero { grid-template-columns: 1fr; padding:28px 14px; text-align:center; }
  #hero-wrapper .profile { margin:0 auto 12px; }
}
</style>

<div id="hero-wrapper" class="hero">

  <div class="hero-bg" aria-hidden="true"></div>

  <div class="profile">
    <img src="/assets/profile.jpg" alt="Dr. Sandra Gran">
    <div class="meta">
      <h1>Dr. Sandra Gran</h1>
      <p class="role">Marine Biologist • Data Scientist • NIVA</p>

      <div class="socials" style="display:flex;gap:8px;margin-top:10px;">
        <a href="https://www.linkedin.com/in/sandragrans/" target="_blank" rel="noopener">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&style=flat-square&logoColor=white" alt="LinkedIn">
        </a>
        <a href="https://github.com/sandragran" target="_blank" rel="noopener">
          <img src="https://img.shields.io/badge/GitHub-181717?logo=github&style=flat-square&logoColor=white" alt="GitHub">
        </a>
        <a href="mailto:sandra.granstad@gmail.com">
          <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&style=flat-square&logoColor=white" alt="Email">
        </a>
      </div>
    </div>
  </div>

  <div class="about">
    <p class="lead"><strong>Marine Biologist & Data Scientist</strong> (PhD, Univ. of Oslo). I work on coastal monitoring, phytoplankton ecology and marine biogeochemistry. Skilled in R & Python, integrating in-situ and satellite datasets for operational oceanography.</p>

    <div class="cta">
      <a class="btn-cta" href="/assets/CV_Sandra_Gran.pdf" target="_blank" rel="noopener">Download CV</a>
      <a class="btn-ghost" href="projects.md">Explore projects</a>
    </div>

    <div class="info-grid" style="display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:12px;">
      <div>
        <h4 style="color:#e9fbff;margin:0 0 6px;">Interests</h4>
        <ul style="margin:0;padding-left:18px;color:rgba(255,255,255,0.95);">
          <li>Phytoplankton & protists</li>
          <li>Satellite ocean color</li>
          <li>Biogeochemical cycles</li>
        </ul>
      </div>
      <div>
        <h4 style="color:#e9fbff;margin:0 0 6px;">Education</h4>
        <ul style="margin:0;padding-left:18px;color:rgba(255,255,255,0.95);">
          <li>PhD in Marine Molecular Biology — UiO</li>
          <li>Postdoc & Research Scientist — NIVA</li>
        </ul>
      </div>
    </div>
  </div>

</div>

<!-- small spacer -->
<div style="height:18px"></div>

# 👋 Hi — I’m **Sandra Gran (PhD.)**

**Marine Biologist & Data Scientist** (PhD, University of Oslo)  
Research Scientist at **NIVA (Norway)** — coastal monitoring, phytoplankton ecology, marine biogeochemistry.

[About](about.md) · [Projects](projects.md) · [Mini-Projects](miniprojects.md) · [Skills](skills.md) · [Publications](publications.md) · [Contact](contact.md)

---

## 🔬 Current focus
- Coastal & fjord ecosystem monitoring  
- Phytoplankton indicators & eDNA metabarcoding  
- Integrating in-situ data with satellite products (Copernicus / Sentinel-3)  
- Nature-inclusive offshore energy (NiD4OCEAN)

---

<!-- rebuild trigger -->
