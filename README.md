[github_profile_readme_preview.html](https://github.com/user-attachments/files/28251918/github_profile_readme_preview.html)

<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500&family=Sora:wght@400;500;600&display=swap');

  .gh-wrap {
    font-family: 'Sora', var(--font-sans);
    color: var(--color-text-primary);
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-lg);
    padding: 2rem 2.5rem;
    max-width: 720px;
    margin: 0 auto;
  }
  .gh-wrap h1 { font-size: 22px; font-weight: 600; margin: 0 0 4px; }
  .gh-wrap .tagline { font-size: 14px; color: var(--color-text-secondary); margin: 0 0 1.5rem; }
  .gh-wrap hr { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 1.5rem 0; }
  .gh-wrap h2 { font-size: 15px; font-weight: 600; margin: 0 0 1rem; color: var(--color-text-primary); }
  .gh-wrap h3 { font-size: 14px; font-weight: 500; margin: 0 0 0.25rem; }
  .skill-grid { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 12px; margin-bottom: 0.5rem; }
  .skill-card {
    background: var(--color-background-secondary);
    border-radius: var(--border-radius-md);
    padding: 12px 14px;
  }
  .skill-card .label { font-size: 11px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 6px; }
  .skill-card .items { font-size: 13px; color: var(--color-text-primary); line-height: 1.8; }
  .project-card {
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-md);
    padding: 14px 16px;
    margin-bottom: 10px;
    background: var(--color-background-primary);
  }
  .project-title { font-size: 14px; font-weight: 600; color: #185FA5; margin-bottom: 4px; display: flex; align-items: center; gap: 6px; }
  .project-desc { font-size: 13px; color: var(--color-text-secondary); margin-bottom: 10px; line-height: 1.5; }
  .tags { display: flex; flex-wrap: wrap; gap: 6px; }
  .tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    background: var(--color-background-secondary);
    color: var(--color-text-secondary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: 4px;
    padding: 2px 8px;
  }
  .stats-bar {
    display: flex;
    gap: 12px;
    margin: 0.5rem 0;
  }
  .stat {
    background: var(--color-background-secondary);
    border-radius: var(--border-radius-md);
    padding: 12px 16px;
    flex: 1;
    text-align: center;
  }
  .stat .num { font-size: 20px; font-weight: 600; color: var(--color-text-primary); }
  .stat .lbl { font-size: 11px; color: var(--color-text-secondary); margin-top: 2px; }
  .connect-row { display: flex; gap: 10px; flex-wrap: wrap; margin-top: 0.75rem; }
  .connect-btn {
    display: inline-flex; align-items: center; gap: 6px;
    font-size: 13px; font-weight: 500;
    color: var(--color-text-secondary);
    background: var(--color-background-secondary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-md);
    padding: 8px 14px;
    text-decoration: none;
    cursor: pointer;
  }
  .connect-btn i { font-size: 16px; }
  .wip-badge {
    display: inline-block;
    background: #E6F1FB;
    color: #185FA5;
    font-size: 10px;
    font-weight: 600;
    border-radius: 4px;
    padding: 2px 7px;
    letter-spacing: 0.04em;
    margin-left: 6px;
  }
  .quote {
    font-size: 13px;
    color: var(--color-text-secondary);
    border-left: 2px solid var(--color-border-secondary);
    padding-left: 12px;
    margin-top: 1rem;
    font-style: italic;
  }
  .currently {
    background: var(--color-background-secondary);
    border-radius: var(--border-radius-md);
    padding: 14px 16px;
    font-size: 13px;
    color: var(--color-text-primary);
    line-height: 1.6;
  }
  .currently .dot { display: inline-block; width: 8px; height: 8px; border-radius: 50%; background: #3B6D11; margin-right: 8px; }
</style>

<div class="gh-wrap">
  <h1>Hi, I'm Medini 👋</h1>
  <p class="tagline">Backend Java Developer · Spring Boot & Microservices · REST APIs · Oracle/MySQL · Building systems that scale</p>

  <hr>

  <h2>🛠️ What I Work With</h2>
  <div class="skill-grid">
    <div class="skill-card">
      <div class="label">Languages & Frameworks</div>
      <div class="items">Java<br>Spring Boot<br>Spring Cloud<br>Spring Security</div>
    </div>
    <div class="skill-card">
      <div class="label">Architecture</div>
      <div class="items">Microservices<br>REST API Design<br>Event-Driven<br>API Gateway</div>
    </div>
    <div class="skill-card">
      <div class="label">Databases & Tools</div>
      <div class="items">Oracle · MySQL<br>SQL Optimization<br>Maven · Docker<br>Postman · Git</div>
    </div>
  </div>

  <hr>

  <h2>⚡ Currently Building</h2>
  <div class="currently">
    <span class="dot"></span>
    A microservices project exploring <strong>service discovery, API gateway patterns, and inter-service communication</strong> — the kind of stuff that's easy to get wrong and satisfying to get right.
    <span class="wip-badge">IN PROGRESS</span>
  </div>

  <hr>

  <h2>📌 Projects</h2>

  <div class="project-card">
    <div class="project-title"><i class="ti ti-code" aria-hidden="true"></i> Project Name — Short punchy tagline</div>
    <div class="project-desc">What it does and what's architecturally interesting about it. One or two sentences max. Make the reader want to click.</div>
    <div class="tags">
      <span class="tag">Java</span>
      <span class="tag">Spring Boot</span>
      <span class="tag">REST API</span>
      <span class="tag">MySQL</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-title"><i class="ti ti-server" aria-hidden="true"></i> Project Name — Short punchy tagline</div>
    <div class="project-desc">What problem it solves, what you learned, why it's worth looking at. Keep it honest — skip the buzzwords.</div>
    <div class="tags">
      <span class="tag">Java</span>
      <span class="tag">Microservices</span>
      <span class="tag">Spring Cloud</span>
      <span class="tag">Oracle</span>
    </div>
  </div>

  <hr>

  <h2>📫 Let's Connect</h2>
  <p style="font-size:13px; color:var(--color-text-secondary); margin: 0 0 0.75rem;">Open to Backend Java / Spring Boot / Microservices roles. If you're building something interesting — or just want to talk architecture — reach out.</p>

  <div class="connect-row">
    <div class="connect-btn"><i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn</div>
    <div class="connect-btn"><i class="ti ti-mail" aria-hidden="true"></i> Email</div>
    <div class="connect-btn"><i class="ti ti-brand-github" aria-hidden="true"></i> @medinimd</div>
  </div>

  <div class="quote">"Make it work, make it right, make it fast — in that order."</div>
</div>
