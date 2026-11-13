# Hi there, I'm Cuauhtémoc González Encinas 👋

<p align="left">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloud_Run-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Zero--Trust-0F172A?style=for-the-badge&logo=shield&logoColor=white" />
  <img src="https://img.shields.io/badge/IAM_&_Least_Privilege-0284C7?style=for-the-badge&logo=auth0&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

### 🛡️ About Me
I'm an **Information Technology & Cloud Security Specialist** with practical experience architecting, deploying, and securing serverless solutions on **Google Cloud Platform (GCP)**.

- 🏢 Currently modernizing industrial operations and deploying serverless applications at **Holcim**.
- 🔐 Architect of **B2B Architech**, a serverless Cloud Security Posture (CSPM) & FinOps platform on GCP with automated runtime verification and IAM least privilege.
- ⚡ Specialized in **Zero-Trust architectures**, IAM Least Privilege, centralized secrets management via **GCP Secret Manager**, cryptographic HMAC verification, event-driven automation (**Cloud Scheduler** + **Pub/Sub**), and GenAI governance (**Gemini API** Zero Data Retention).
- 📍 Hermosillo, Sonora, Mexico (Available for Remote / Hybrid roles).

---

### 🚀 Featured Production Projects

#### 1. [B2B Architech — Continuous Security Posture, FinOps & Autonomous Agents](https://b2barchitech.com)
*Serverless Architecture on GCP (Cloud Run, Secret Manager, Cloud Scheduler, Pub/Sub, Firestore, GCS)*
- **Runtime Posture Verification**: Live `/api/security/posture` auditing 10 security controls in real-time. Zero-Profiling public report with granular technical audit behind strict OIDC/JWT authorization.
- **Identity & Secret Security**: GCP Secret Manager as authoritative store (9 managed secrets, zero plaintext secrets in code or env vars). Dedicated least-privilege service account (`sentinel-crew-worker-sa`) with `roles/secretmanager.secretAccessor`, `roles/datastore.user`, and `roles/binaryauthorization.policyViewer`.
- **Perimeter Defense**: HMAC-SHA256 Signed URLs with 72h strict TTL, `timingSafeEqual` constant-time verification, path-traversal prevention, and brute-force IP rate limiting.
- **Event-Driven Agents & FinOps**: 6-hour scheduled cycles (`Cloud Scheduler` OIDC + `Pub/Sub`) running 11 real production probes (TTFB, Lighthouse/CrUX Web Vitals, Cloud Run revisions, Firestore IAM REST, Cloud Monitoring cost estimates) with Human-in-the-Loop (HITL) governance.
- **Automated Tech Radar → GitHub Issues**: Continuous polling of official Google Cloud Release Notes persisting approved findings to Firestore via IAM and automatically opening deduplicated engineering Issues via GitHub REST API.
- **GenAI Governance**: Gemini API integration with `store: false` policy (Zero Data Retention for corporate training) and automated PII redaction across distributed traces (**Cloud Trace**).

#### 2. [Cloud Posture Monitor — DevSecOps & IaC Lab](https://github.com/cuauhtemocge88/cloud-posture-monitor)
*Node.js, Docker Multi-Stage, Kubernetes (Helm), Terraform (AWS ECS Fargate), GitHub Actions OIDC, Trivy & Gitleaks*
- Open-source DevSecOps reference repository demonstrating container hardening, Infrastructure as Code, keyless CI/CD via OIDC, vulnerability scanning (Trivy), and secret detection (Gitleaks).

#### 3. [Holcim Planta Hermosillo · Operational Cloud Portal](https://holcim-portal-837199986061.us-central1.run.app/)
*Serverless PWA on Google Cloud Run*
- Digitalization of 100% of vehicular safety inspections, truck cycle times, coaching modules, and operational analytics in real time for industrial plant operations.

#### 4. [ArtTech-IA — Progressive Web App on Cloud Run](https://arttech-ai-676819743861.us-east1.run.app/)
*React, Vite, Node.js, Express, Service Workers, Google Cloud Run*
- Decoupled serverless web application containerized and deployed on GCP Cloud Run with offline resilience via Service Workers.

---

### 🛠️ Tech Stack & Tooling

| Domain | Technologies |
| :--- | :--- |
| **Cloud (GCP)** | Cloud Run, Secret Manager, Cloud Scheduler, Cloud Pub/Sub, Cloud Storage, Firestore, Cloud Logging, Cloud Trace, IAM |
| **Security** | Zero-Trust Architecture, IAM Least Privilege, OIDC, JWT, RBAC, HMAC-SHA256, Signed URLs, HSTS Preload |
| **Development** | Node.js, Express, JavaScript, TypeScript, React, Python, REST APIs, Git, Bash / Linux CLI |
| **Databases & DevOps** | Firestore, MySQL, Docker, Cloud Build, CI/CD, Serverless, GitHub API, TCP/IP Networking |

---

### 📫 Connect with Me
- 🌐 **Portfolio & Live Audit**: [b2barchitech.com](https://b2barchitech.com)
- 🛡️ **Runtime Posture API**: [b2barchitech.com/api/security/posture](https://b2barchitech.com/api/security/posture)
- 💼 **LinkedIn**: [linkedin.com/in/cuauhtemocge](https://www.linkedin.com/in/cuauhtemocge)
- ✉️ **Email**: [cuauhtemocge88@gmail.com](mailto:cuauhtemocge88@gmail.com)
