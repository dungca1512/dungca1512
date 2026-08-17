<p align="center">
  <img src="assets/homelab-banner.jpeg" alt="Cozy homelab — Proxmox, TrueNAS, Portainer, Pi-hole, Grafana, Uptime Kuma" width="100%">
</p>

# Hi there, I'm Dung 👋

## AI/ML Systems Architect | Infrastructure & MLOps | Language Technology

<img align="right" width="360" src="assets/lofi-coding.gif" alt="Developer coding with headphones on">

I own AI infrastructure end-to-end — from cloud provisioning to production ML serving. CLI-first, cost-conscious, and framework-driven in every decision.

📄 [CV](https://portfolio-dungca.ai-innovation-homelab.org/CV_CongAnhDung.pdf) · 🌐 [Portfolio](https://portfolio-dungca.ai-innovation-homelab.org) · ✍️ [Blog](https://blog-dungca.ai-innovation-homelab.org) · 🤗 [Hugging Face](https://huggingface.co/dungca)

### What I Build

- **Production ML Serving**  
  ASR (faster-whisper/CTranslate2), TTS, pronunciation scoring (wav2vec2 CTC + GOP), and embedding (Qwen3) services for users across VN, JP, and KR — including a self-hosted OpenAI-compatible `/v1/embeddings` endpoint that replaced the paid API.
- **Cloud & Kubernetes Infrastructure**  
  Terraform/Ansible provisioning, Docker/Compose/Swarm, and Kubernetes on GKE, DigitalOcean, and bare-metal kubeadm — with ArgoCD GitOps, MetalLB, and Cloudflare Tunnel.
- **Infrastructure as Code, All the Way Home**  
  Even the Raspberry Pi that serves my LAN is a single idempotent Ansible playbook: rebuildable from a bare OS, DNS latency cut **199 ms → 27 ms**, operated through Slack ChatOps on a Cloudflare Worker.
- **Cost Engineering**  
  Size hardware from benchmarks, not vendor slides: a measured **p95 of 1.86 s at 20 concurrent users** (~8% GPU utilization, ~2 GB VRAM) showed a commodity CUDA GPU was enough where an H100 plan would have cost ~$2,475/mo — and ruled out CPU-only serving with a ~1 req/s throughput wall.

### Selected Projects

- [homelab](https://github.com/dungca1512/homelab) — 3-node Kubernetes v1.31 built by hand with `kubeadm`, GitOps via ArgoCD App-of-Apps, Prometheus + Loki, ~2,400 lines of engineering notes
- [ai-gateway](https://github.com/dungca1512/ai-gateway) — reactive multi-provider LLM gateway (Spring WebFlux + FastAPI worker), provisioned on GKE Autopilot with Terraform
- [whisper-finetune-ja](https://github.com/dungca1512/whisper-finetune-ja) — Japanese ASR fine-tuning with a full CI/CT/CD loop; [3 models on Hugging Face](https://huggingface.co/dungca), LoRA variant at 40+ downloads
- [newspulse-reco-engine](https://github.com/dungca1512/newspulse-reco-engine) — Kafka/Spark streaming news platform (Scala)
- [research-agent](https://github.com/dungca1512/research-agent) — LangChain + LangGraph research workflows
- *Raspberry Pi homelab (private)* — Ansible IaC, AdGuard Home DNS with DoH, Slack ChatOps, ansible-lint/yamllint/gitleaks CI gates, GPG-encrypted backups

### Tech Stack

#### Infrastructure & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

#### Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A800?style=for-the-badge&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

#### Cloud
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/OCI-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

#### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

#### AI/ML & Serving
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

### Research Interests

- Cost-efficient ML model serving and GPU utilization
- Production LLM reliability and orchestration at scale
- GitOps and reproducible infrastructure for ML platforms
- Southeast Asian & East Asian language processing

### Currently Learning

- AWS Solutions Architect Associate (SAA-C03) — in progress
- Advanced GitOps patterns (ArgoCD App-of-Apps) and observability at scale
- Efficient model serving and protocol design for AI gateways
- Treating home infrastructure like production: Ansible IaC, ChatOps, and recovery runbooks

### Let's Connect

- Email: **dungca1512@gmail.com**
- GitHub: **[dungca1512](https://github.com/dungca1512)**
- LinkedIn: **[dungca](https://www.linkedin.com/in/dungca/)**

---

*Building practical bridges between frontier AI research and production-grade infrastructure.*
