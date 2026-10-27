<div align="center">

# Adam Tamenne

**Application Security Engineer**

DAST · SAST/SCA · ASPM · DevSecOps · MITRE ATT&CK · Threat Modeling · CI/CD Security

[![CySA+](https://img.shields.io/badge/CompTIA-CySA%2B-c8202f?style=flat-square)](https://www.comptia.org/certifications/cybersecurity-analyst)
[![Berkeley](https://img.shields.io/badge/UC_Berkeley-MICS-003262?style=flat-square)](https://ischool.berkeley.edu/programs/mics)
[![AWS](https://img.shields.io/badge/AWS_Security_Specialty-In_Progress-FF9900?style=flat-square)](https://aws.amazon.com/certification/certified-security-specialty/)

I find vulnerabilities in web applications, validate exploitability, and drive remediation across development teams. I integrate security tooling into CI/CD pipelines, trace root causes through source code and logs, and build the processes that keep findings actionable at scale. I’m also working to connect AppSec findings to the broader attack lifecycle using MITRE ATT&CK, bridging the gap between what a scanner flags and how an attacker would actually chain it.

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
| **Scan (Node.js)** | [secure-microservices](https://github.com/adamtamenne/secure-microservices) | Intentionally vulnerable Node.js microservices with a five-stage security pipeline |
| **Respond** | [aws-incident-response-scripts](https://github.com/adamtamenne/aws-incident-response-scripts) | Automated scripts for AWS security incident response |
| **Detect** | [attack-lifecycle-mapping](https://github.com/adamtamenne/attack-lifecycle-mapping) | Maps common AppSec findings to MITRE ATT&CK techniques with detection strategies and response playbooks |


---

## Tools

| Category | Tools |
|----------|-------|
| DAST | Invicti, Acunetix, OWASP ZAP, Burp Suite |
| SAST/SCA | Semgrep, Checkmarx, Snyk, Dependabot, Trivy |
| ASPM | Invicti ASPM (centralized triage across scanner types) |
| Infrastructure | Kubernetes (Helm, k3s, AKS), Docker, AWS, Azure, Terraform |
| CI/CD | GitHub Actions, Azure DevOps |
| Observability | Dynatrace |
| Detection & Response | MITRE ATT&CK, log correlation, incident triage |

---

<div align="center">

tamennea@gmail.com · [LinkedIn](https://www.linkedin.com/in/adamtamenne)

</div>
