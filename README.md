# Adam Tamenne

**Application Security Engineer** | DAST · ASPM · SAST/SCA Triage · DevSecOps

I help organizations operationalize application security tooling. That means deploying scanners, tuning findings, eliminating false positives, integrating security into CI/CD pipelines, and making results actionable for development teams. I work across DAST (Invicti), SAST (Semgrep, Checkmarx), SCA (Snyk, Dependabot), and ASPM platforms daily.

Berkeley MICS · CySA+ · Austin, TX

## Projects

These repos walk through an AppSec engagement lifecycle, from threat modeling through incident response.

### Assess
**[threat-modeling](https://github.com/adamtamenne/threat-modeling)** — STRIDE-based threat models with data flow diagrams and mitigations across four architectures. Every engagement starts here: understand the system before you scan it.

### Scan & Enforce
**[devsecops-pipeline-demo](https://github.com/adamtamenne/devsecops-pipeline-demo)** — Five-stage GitHub Actions security pipeline (Gitleaks, Semgrep, Snyk, Trivy, ZAP) with:
- [Custom Semgrep rules](https://github.com/adamtamenne/devsecops-pipeline-demo/tree/main/security/semgrep-rules) that catch patterns default rulesets miss
- [Configurable policy gates](https://github.com/adamtamenne/devsecops-pipeline-demo/blob/main/security-policy.yml) with a three-phase rollout (observe, gate critical, enforce)
- [SBOM generation and container signing](https://github.com/adamtamenne/devsecops-pipeline-demo/blob/main/.github/workflows/stage-container-scan.yml) for SLSA Level 2 supply chain integrity
- [Findings triage guide](https://github.com/adamtamenne/devsecops-pipeline-demo/blob/main/docs/findings-triage.md) for prioritizing results by real risk

### Exploit & Validate
**[owasp-top10-exploitation](https://github.com/adamtamenne/owasp-top10-exploitation)** — Manual exploitation and remediation of all 10 OWASP Top 10 categories using Burp Suite. Each finding includes the exact request/response, a screenshot proving exploitability, and the remediation code.

### Normalize
**[appsec-sandbox](https://github.com/adamtamenne/appsec-sandbox)** — Automated analysis pipeline that orchestrates SAST, SCA, secrets, and DAST scanning against containerized targets with cross-tool finding normalization and deduplication.

### Harden
**[aws-security-controls](https://github.com/adamtamenne/aws-security-controls)** — Terraform modules implementing AWS security controls aligned to SCS-C02 exam domains.

### Respond
**[aws-incident-response-scripts](https://github.com/adamtamenne/aws-incident-response-scripts)** — Automated scripts for AWS security incident response.

## Tools

**DAST:** Invicti, Acunetix, OWASP ZAP, Burp Suite
**SAST/SCA:** Semgrep, Checkmarx, Snyk, Dependabot, Trivy
**ASPM:** Invicti ASPM, centralized triage across scanner types
**Infrastructure:** Kubernetes (Helm, k3s, AKS), Docker, AWS, Azure, Terraform
**CI/CD:** GitHub Actions, Azure DevOps, pipeline security integration
**Observability:** Dynatrace

## Certifications

**M.S. Information & Cybersecurity** — UC Berkeley
**CompTIA CySA+** — Cybersecurity Analyst
**AWS Security Specialty** — In progress

## Connect

tamennea@gmail.com · [LinkedIn](https://www.linkedin.com/in/adamtamenne)
