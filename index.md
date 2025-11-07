---
title: Home
layout: default
---

<style>
/* RESET DEFAULT HEADER */
.page-header, .site-header, .jumbotron, .page-head {display:none !important;}
.site-content {margin-top:0 !important;}

/* HERO SECTION */
#hero-wrapper.hero {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 30px;
  width: 100%;
  min-height: 420px;
  padding: 60px 10%;
  background: linear-gradient(135deg, #0a7a7a, #127f63);
  color: white;
  overflow: hidden;
}

/* BACKGROUND IMAGE */
#hero-wrapper .hero-bg {
  position: absolute;
  inset: 0;
  background-image: url('/assets/hero-bg.jpg');
  background-size: cover;
  background-position: center;
  opacity: 0.15;
  z-index: 0;
}

/* PROFILE */
#hero-wrapper .profile {
  position: relative;
  z-index: 1;
  text-align: center;
}
#hero-wrapper .profile img {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid rgba(255,255,255,0.4);
  box-shadow: 0 8px 20px rgba(0,0,0,0.35);
}
#hero-wrapper .meta h1 {
  margin: 10px 0 4px;
  font-size: 1.8rem;
}
#hero-wrapper .role {
  font-size: 1.05rem;
  opacity: 0.9;
}

/* SOCIAL ICONS */
.socials {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  margin-top: 8px;
}
.socials img {
  height: 22px;
  transition: transform 0.2s ease;
}
.socials img:hover {
  transform: scale(1.1);
}

/* ABOUT SECTION */
#hero-wrapper .about {
  position: relative;
  z-index: 1;
  flex: 1;
  min-width: 280px;
}
#hero-wrapper .lead {
  font-size: 1.05rem;
  color: rgba(255,255,255,0.95);
  margin-bottom: 14px;
}
.cta {
  margin-bottom: 16px;
}
.btn-cta {
  background: #0e8aa8;
  color: white;
  padding: 8px 14px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  margin-right: 8px;
}
.btn-ghost {
  background: transparent;
  color: #eaf6fb;
  padding: 8px 14px;
  border-radius: 8px;
  border: 1px solid rgba(255,255,255,0.3);
  text-decoration: none;
  font-weight: 600;
}

/* INFO GRID */
.info-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 20px;
}
.info-grid h4 {
  color: #eaf6fb;
  margin-bottom: 6px;
}
.info-grid ul {
  padding-left: 18px;
  margin: 0;
  color: rgba(255,255,255,0.9);
}

/* RESPONSIVE */
@media (max-width: 860px) {
  #hero-wrapper.hero {
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 40px 20px;
  }
  .about {max-width: 600px;}
}
</style>

<div id="hero-wrapper" class="hero">

  <div class="hero-bg" aria-hidden="true"></div>

  <div class="profile">
    <img src="/assets/profile.jpg" alt="Dr. Sandra Gran">
    <div class="meta">
      <h1>Dr. Sandra Gran</h1>
      <p class="role">Marine Biologist • Data Scientist • NIVA</p>
      <div class="socials">
        <a href="https://www.linkedin.com/in/sandragrans/" target="_blank" rel="noopener">
          <img src="https://img.icons8.com/ios-filled/50/ffffff/linkedin.png" alt="LinkedIn">
        </a>
        <a href="https://github.com/sandragran" target="_blank" rel="noopener">
          <img src="https://img.icons8.com/ios-filled/50/ffffff/github.png" alt="GitHub">
        </a>
        <a href="mailto:sandra.granstad@gmail.com">
          <img src="https://img.icons8.com/ios-filled/50/ffffff/new-post.png" alt="Email">
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

    <div class="info-grid">
      <div>
        <h4>Interests</h4>
        <ul>
          <li>Phytoplankton & protists</li>
          <li>Satellite ocean color</li>
          <li>Biogeochemical cycles</li>
        </ul>
      </div>
      <div>
        <h4>Education</h4>
        <ul>
          <li>PhD in Marine Molecular Biology — UiO</li>
          <li>Postdoc & Research Scientist — NIVA</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<!-- small spacer -->
<div style="height:24px"></div>

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
