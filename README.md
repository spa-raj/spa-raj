### Hi, I'm Sparsh 👋

**Backend & Platform Engineer** · Java / Spring Boot · Kafka · Kubernetes (CKAD) · AWS EKS · Terraform · Go

I build backend systems and the platforms they run on: Spring Boot microservices, Kafka event streams, and Kubernetes on AWS, all provisioned as code. CNCF **OpenCost** contributor (LFX Mentorship '25), MS in Computer Science (4.0 GPA). Lately also building with LLMs and RAG.

📍 Bengaluru · open to Backend, Platform and AI engineering roles · [sparshraj.me](https://sparshraj.me)

---

### 🔨 What I've built

**[VibeVault](https://github.com/spa-raj/vibevault)** · 6 Spring Boot 4 / Java 21 microservices on AWS EKS
- Choreography-based **Saga over Kafka** (KRaft) with idempotent consumers; Razorpay payments with HMAC-verified webhooks; OAuth2 auth server (Spring Security)
- Moved 2M-product search from MySQL `LIKE` (100% failure at 15 concurrent users) to **OpenSearch**: 99.3% success at 27 ms p50 under k6 load
- [6 Terraform modules](https://github.com/spa-raj/vibevault-infra) (VPC, EKS, RDS, ECR, Secrets Manager + KMS, OpenSearch), Helm per service, Kong gateway, GitHub Actions with OIDC (no static AWS keys) · 114 PRs, 55 E2E tests

**[OpenCost](https://github.com/opencost/opencost)** (CNCF Sandbox) · LFX Mentorship, Fall 2025 · Go
- Built the foundation of **KubeModel** (Data Model 2.0): UID tracking across 61+ metrics and 30+ Prometheus queries, so recreated pods no longer get misattributed cost
- 14 merged PRs across opencost, [opencost-integration-tests](https://github.com/opencost/opencost-integration-tests) and opencost-website · wrote [Introducing KubeModel](https://opencost.io/blog/introducing-kubemodel) · poster at Open Source Summit India 2026 (Mumbai)

**[PDF Whisperer](https://github.com/spa-raj/pdf-whisperer)** · RAG over PDFs with cross-encoder reranking and page citations · [live demo on Hugging Face](https://huggingface.co/spaces/spa-raj/pdf-whisperer)

**[CartIQ](https://github.com/spa-raj/cartIQ-backend)** · AI shopping assistant: Spring Boot + Confluent Kafka/Flink + Gemini RAG on Google Cloud (Confluent hackathon)

**[Family Lock](https://github.com/spa-raj/family-lock)** · Android device-owner app: forced family DNS, VPN/bypass blocking, no off switch

---

### 🧰 Stack

**Backend** · Java, Spring Boot, Spring Security, Go, Python, Kafka, MySQL, PostgreSQL, MongoDB, Redis, OpenSearch\
**Platform** · Kubernetes, Helm, Docker, Terraform, AWS (EKS, RDS, ECR, KMS), GCP, GitHub Actions, Prometheus\
**AI** · RAG, LangChain, ChromaDB, rerankers, Gemini / OpenAI APIs

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://linkedin.com/in/spa-raj) [![Website](https://img.shields.io/badge/sparshraj.me-222?logo=googlechrome&logoColor=white)](https://sparshraj.me) [![X](https://img.shields.io/badge/X-000?logo=x&logoColor=white)](https://x.com/spar_raj) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:sparsh.raj30@gmail.com)
