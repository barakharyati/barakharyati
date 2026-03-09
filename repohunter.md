---
layout: default
title: RepoHunter
permalink: /repohunter
seo_title: "RepoHunter – AI Security Research Tool by Barak Haryati"
description: "RepoHunter is an AI-powered security research tool created by Barak Haryati to identify CI/CD and software supply chain vulnerabilities in GitHub workflows and open-source ecosystems."
keywords: "RepoHunter, Barak Haryati, AI security research tool, CI/CD security, GitHub Actions security, software supply chain security, Pwn Request, pull_request_target, Shai-Hulud, workflow exploitation, pipeline misconfiguration, open source security research, JFrog"
og_image: "https://barak.haryati.io/assets/repohunter-ai-security-tool.png"
og_description: "RepoHunter is an AI-powered security research tool by Barak Haryati for identifying CI/CD workflow vulnerabilities and software supply chain risks at scale."
---

<section class="rh-hero">
  <div class="rh-hero-content">
    <div class="rh-hero-text">
      <h1>RepoHunter</h1>
      <p class="rh-subtitle">AI-powered security research tool by <strong>Barak Haryati</strong></p>
      <p class="rh-intro">RepoHunter is an AI-powered security research tool created by Barak Haryati, Senior Director of Product Security at JFrog. It is designed to analyze CI/CD pipelines and GitHub workflows to identify critical supply chain and automation security risks at scale.</p>
      <div class="rh-cta-row">
        <a href="https://jfrog.com/blog/jfrog-ai-bot-stopped-shai-hulud-3/" class="rh-btn rh-btn-primary" target="_blank" rel="noopener">Read the Research</a>
        <a href="https://www.linkedin.com/in/barakharyati" class="rh-btn rh-btn-secondary" target="_blank" rel="noopener">LinkedIn</a>
        <a href="/" class="rh-btn rh-btn-secondary">Back to Profile</a>
      </div>
    </div>
    <div class="rh-hero-image">
      <img src="assets/repohunter-ai-security-tool.png" alt="RepoHunter AI-powered CI/CD security research tool by Barak Haryati">
    </div>
  </div>
</section>

<div class="rh-content">

<section class="rh-section">
  <h2>What RepoHunter Does</h2>
  <p>RepoHunter automates the discovery of exploitable CI/CD workflow misconfigurations across open-source repositories. It focuses on identifying dangerous patterns in GitHub Actions and related automation pipelines where untrusted input intersects with elevated permissions, secret access, or release processes.</p>
  <div class="rh-capabilities-grid">
    <div class="rh-capability">
      <h3>Workflow Analysis</h3>
      <p>Crawls public repositories and their CI/CD configurations to map the exposed attack surface, including <code>pull_request_target</code>, <code>workflow_run</code>, and <code>issue_comment</code> triggers.</p>
    </div>
    <div class="rh-capability">
      <h3>Pattern Detection</h3>
      <p>Identifies vulnerable workflow patterns where untrusted input — such as PR metadata, branch names, or fork code — intersects with elevated permissions or secret access.</p>
    </div>
    <div class="rh-capability">
      <h3>AI-Assisted Validation</h3>
      <p>Validates exploitability using AI and generates real-world exploitation scenarios, reducing false positives and prioritizing genuine supply chain risks.</p>
    </div>
    <div class="rh-capability">
      <h3>Responsible Disclosure</h3>
      <p>Produces detailed vulnerability reports with evidence, proof-of-concept demonstrations, and actionable remediation guidance for maintainers.</p>
    </div>
  </div>
</section>

<section class="rh-section">
  <h2>Why It Matters</h2>
  <p>Continuous Integration workflows have become the new battleground for software supply chain attacks. Incidents like the Shai-Hulud worm and the Nx project compromise — where 83,000 secrets were leaked through a single CI misconfiguration — proved that a seemingly normal pull request can compromise an entire software ecosystem.</p>
  <p>The shift to trusted publishing models, such as npm's OIDC-based approach, moved the root of trust to CI/CD. But if CI/CD itself is compromised, the entire chain collapses. RepoHunter was built by Barak Haryati to proactively detect these risks before attackers operationalize them — hunting CI takeover vulnerabilities at scale, rather than waiting for the next supply chain incident.</p>
  <div class="rh-risk-areas">
    <span class="tool-tag">CI/CD Workflow Abuse</span>
    <span class="tool-tag">GitHub Actions Exploitation</span>
    <span class="tool-tag">Software Supply Chain Exposure</span>
    <span class="tool-tag">Repository Takeover</span>
    <span class="tool-tag">Secret Exfiltration</span>
    <span class="tool-tag">Downstream Ecosystem Impact</span>
    <span class="tool-tag">Artifact Poisoning</span>
    <span class="tool-tag">Open Source Security</span>
  </div>
</section>

<section class="rh-section">
  <h2>Research Impact</h2>
  <p>Using RepoHunter, Barak Haryati identified and responsibly disclosed critical CI/CD workflow vulnerabilities across 13 widely used open-source projects. These findings helped prevent potential Shai-Hulud 3 style supply chain attacks that could have impacted enterprise automation, AI infrastructure, developer toolchains, and global network systems.</p>
  <div class="rh-disclosures">
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">Ansible</span>
      <span class="rh-detail">Enterprise IT automation — organization-wide package compromise</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">P4Lang</span>
      <span class="rh-detail">Network switch language — SDN infrastructure risk</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">Petgraph</span>
      <span class="rh-detail">Rust graph library — downstream crate compromise</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">QGIS</span>
      <span class="rh-detail">Geospatial platform — government and research infrastructure</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">SDKMAN</span>
      <span class="rh-detail">JVM developer toolchain — Java ecosystem impact</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">TC39</span>
      <span class="rh-detail">JavaScript standards — language-level ecosystem risk</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">Telepresence</span>
      <span class="rh-detail">CNCF Kubernetes tool — cloud-native development</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">Typst</span>
      <span class="rh-detail">Typesetting language registry — academic and publishing</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">Xorbits Inference</span>
      <span class="rh-detail">AI model-serving framework — AI infrastructure</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity critical">Critical</span>
      <span class="rh-project">Eclipse Theia</span>
      <span class="rh-detail">Cloud IDE framework — developer environment</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity high">High</span>
      <span class="rh-project">Tencent/ncnn</span>
      <span class="rh-detail">Mobile AI framework — 1.4B+ user app ecosystem</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity high">High</span>
      <span class="rh-project">Ceph</span>
      <span class="rh-detail">Distributed storage — cloud provider infrastructure</span>
    </div>
    <div class="rh-disclosure-item">
      <span class="cve-severity medium">Medium</span>
      <span class="rh-project">Parse Server</span>
      <span class="rh-detail">Backend-as-a-Service — mobile and web applications</span>
    </div>
  </div>
</section>

<section class="rh-section">
  <h2>Publications &amp; Media</h2>
  <div class="rh-publications">
    <a href="https://jfrog.com/blog/jfrog-ai-bot-stopped-shai-hulud-3/" class="rh-pub-card" target="_blank" rel="noopener">
      <h3>How JFrog's AI-Research Bot Found OSS CI/CD Vulnerabilities to Prevent Shai Hulud 3.0</h3>
      <p>JFrog Blog — by Barak Haryati, March 2026</p>
    </a>
  </div>
</section>

<section class="rh-section">
  <h2>About the Creator</h2>
  <p>Barak Haryati is Senior Director of Product Security at JFrog, where he leads global teams across Application Security, Cloud Security, and Security Architecture. As a vulnerability researcher and active contributor to the open-source security community, he created RepoHunter to proactively hunt CI/CD supply chain risks before attackers can exploit them. His work spans responsible disclosure, security tooling, and AI-powered defense for software supply chains.</p>
  <div class="rh-cta-row">
    <a href="/" class="rh-btn rh-btn-secondary">View Full Profile</a>
    <a href="https://www.linkedin.com/in/barakharyati" class="rh-btn rh-btn-secondary" target="_blank" rel="noopener">LinkedIn</a>
    <a href="https://github.com/barakharyati" class="rh-btn rh-btn-secondary" target="_blank" rel="noopener">GitHub</a>
  </div>
</section>

<section class="rh-section">
  <h2>Media</h2>
  <div class="rh-media-grid">
    <figure class="rh-blog-figure">
      <img src="assets/repohunter-workflow.png" alt="RepoHunter Workflow — Ingestion, Identification, Validation, and Disclosure pipeline">
      <figcaption>RepoHunter Workflow</figcaption>
    </figure>
    <figure class="rh-blog-figure">
      <img src="assets/repohunter-dashboard.png" alt="RepoHunter Dashboard — vulnerability scanning results across open-source repositories">
      <figcaption>RepoHunter Dashboard</figcaption>
    </figure>
  </div>
</section>

</div>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "RepoHunter",
  "applicationCategory": "SecurityApplication",
  "operatingSystem": "Cross-platform",
  "creator": {
    "@type": "Person",
    "name": "Barak Haryati",
    "jobTitle": "Senior Director of Product Security",
    "worksFor": { "@type": "Organization", "name": "JFrog" },
    "url": "https://barak.haryati.io"
  },
  "description": "RepoHunter is an AI-powered security research tool created by Barak Haryati to identify CI/CD and software supply chain vulnerabilities in GitHub workflows and open-source ecosystems. It detects dangerous pull_request_target, workflow_run, and issue_comment patterns, validates exploitability using AI, and supports responsible disclosure.",
  "url": "https://barak.haryati.io/repohunter",
  "image": "https://barak.haryati.io/assets/repohunter-ai-security-tool.png",
  "keywords": "RepoHunter, Barak Haryati, CI/CD security, GitHub Actions security, software supply chain security, Pwn Request, pull_request_target, Shai-Hulud, open source security research, JFrog, workflow exploitation, pipeline misconfiguration, repository takeover, secret exfiltration"
}
</script>

<footer>
  <p>&copy; 2025 Barak Haryati &middot; Security Leader &middot; AppSec &middot; Cloud &middot; AI Security</p>
</footer>
