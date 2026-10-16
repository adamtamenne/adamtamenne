<div align="center">

# Adam Tamenne

**Application Security Engineer**

DAST · ASPM · SAST/SCA Triage · DevSecOps · Kubernetes · CI/CD Security

[![CySA+](https://img.shields.io/badge/CompTIA-CySA%2B-c8202f?style=flat-square)](https://www.comptia.org/certifications/cybersecurity-analyst)
[![Berkeley](https://img.shields.io/badge/UC_Berkeley-MICS-003262?style=flat-square)](https://ischool.berkeley.edu/programs/mics)
[![AWS](https://img.shields.io/badge/AWS_Security-In_Progress-FF9900?style=flat-square)](https://aws.amazon.com/certification/certified-security-specialty/)

I help organizations operationalize application security tooling: deploying scanners, tuning findings,<br>eliminating false positives, integrating security into CI/CD pipelines, and making results actionable.

</div>

---

## Projects

These repos walk through an AppSec engagement lifecycle, from threat modeling through incident response.

| Phase | Repo | What It Does |
|-------|------|-------------|
| **Assess** | [threat-modeling](https://github.com/adamtamenne/threat-modeling) | STRIDE threat models with data flow diagrams and mitigations across four architectures |
| **Scan & Enforce** | [devsecops-pipeline-demo](https://github.com/adamtamenne/devsecops-pipeline-demo) | Five-stage security pipeline with [custom Semgrep rules](https://github.com/adamtamenne/devsecops-pipeline-demo/tree/main/security/semgrep-rules), [policy gates](https://github.com/adamtamenne/devsecops-pipeline-demo/blob/main/security-policy.yml), [SBOM generation, and container signing](https://github.com/adamtamenne/devsecops-pipeline-demo/blob/main/.github/workflows/stage-container-scan.yml) |
| **Exploit & Validate** | [owasp-top10-exploitation](https://github.com/adamtamenne/owasp-top10-exploitation) | Manual exploitation of all OWASP Top 10 categories with Burp Suite, screenshots, and remediation code |
| **Normalize** | [appsec-sandbox](https://github.com/adamtamenne/appsec-sandbox) | Multi-scanner orchestration with cross-tool finding normalization and deduplication |
| **Harden** | [aws-security-controls](https://github.com/adamtamenne/aws-security-controls) | Terraform modules implementing AWS security controls aligned to SCS-C02 |
| **Respond** | [aws-incident-response-scripts](https://github.com/adamtamenne/aws-incident-response-scripts) | Automated scripts for AWS security incident response |

---

## Tools

| Category | Tools |
|----------|-------|
| **DAST** | Invicti, Acunetix, OWASP ZAP, Burp Suite |
| **SAST/SCA** | Semgrep, Checkmarx, Snyk, Dependabot, Trivy |
| **ASPM** | Invicti ASPM (centralized triage across scanner types) |
| **Infrastructure** | Kubernetes (Helm, k3s, AKS), Docker, AWS, Azure, Terraform |
| **CI/CD** | GitHub Actions, Azure DevOps |
| **Observability** | Dynatrace |

---

<div align="center">

tamennea@gmail.com · [LinkedIn](https://www.linkedin.com/in/adamtamenne)

</div>
