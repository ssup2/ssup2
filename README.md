# Hi there, I'm Jungsub Shin 👋

I performed cloud software engineering in computing virtualization (Hypervisor, VM, Container, Kubernetes). Currently, I am extending my cloud experience through the SRE role.

📍 Gyeonggi-do, South Korea

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jungsub-shin-933b82119/)
[![Email](https://img.shields.io/badge/Email-supsup5642%40naver.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:supsup5642@naver.com)
[![Blog](https://img.shields.io/badge/Blog-ssup2.github.io-4B32C3?style=flat&logo=hugo&logoColor=white)](https://ssup2.github.io/blog-software/)

## 💼 Career

| Period | Company | Role |
| --- | --- | --- |
| 2024.12 – Present | **Karrot (당근)** | Site Reliability Engineer |
| 2022.09 – 2024.12 | **Amazon Web Services (AWS)** | Solutions Architect |
| 2019.06 – 2022.09 | **Kakao** | Software Engineer |
| 2018.12 – 2019.06 | **cafe24** | Software Engineer |
| 2016.02 – 2018.12 | **TmaxSoft** | Senior Researcher |
| 2012.12 – 2014.01 | **KETI (Korea Electronics Technology Institute)** | Researcher |
| 2012.08 – 2014.02 | **Samsung Electronics** | Member of Software Membership |

### Karrot (당근) — Site Reliability Engineer <sub>2024.12 – Present</sub>

Responsible for the reliability and security of Kubernetes clusters and the end-to-end stability of services at scale.

- Migrated ~1,000 EKS nodes from Cluster Autoscaler to Karpenter with zero downtime, cutting pod pending time by up to 90%
- Introduced autoscaling for job-dedicated EKS node groups using bin-packing and disruption protection, reducing pod pending time by ~49% and workflow runtime by ~47% while removing manual capacity management (featured on the company tech blog)
- Optimized job pod provisioning by eliminating pod IP allocation delays, reducing creation time by up to 75%
- Built and operated ~60 GPU nodes on EKS, providing the shared platform for ML model serving across teams
- Deployed Dagster on EKS as an internal data pipeline platform, supporting ~1,000 pipeline runs per day

<details>
<summary><b>Previous Roles</b></summary>
<br>

**Amazon Web Services (AWS) — Solutions Architect** <sub>2022.09 – 2024.12</sub>

Served as an Account Solutions Architect for Digital Native Business (DNB) customers, providing technical guidance and cloud architecture design on AWS.

- Provided architectural guidance and hands-on support for Amazon EKS and EMR on EKS workloads
- Troubleshot and mitigated [intermittent network issues in Amazon EKS](https://github.com/ssup2-playground/eks-sgpp-network-issue_project), contributing to service reliability improvements
- Enhanced customers' EKS-based deployment and batch processing platforms by adopting Karpenter for dynamic node provisioning
- Supported the migration from MongoDB to Amazon DocumentDB, achieving 50% cost reduction

**Kakao — Software Engineer** <sub>2019.06 – 2022.09</sub>

Developed and operated an in-house Kubernetes platform. TF Leader.

- Developed and operated DKOS (Daum Kakao Kubernetes Platform), managing over 5,000 clusters and 60,000 nodes serving large-scale Kakao services
- Led the migration of ~60% of Kakao's services to DKOS, significantly improving deployment speed and infrastructure scalability
- Re-architected backend systems into an event-driven architecture, improving service decoupling, scalability, and throughput
- Developed [network-node-manager](https://github.com/kakao/network-node-manager), a controller that automatically detects and resolves network-related issues
- Created Grafana dashboards for real-time monitoring of Kubernetes clusters and network health

**cafe24 — Software Engineer** <sub>2018.12 – 2019.06</sub>

- Analyzed and operated infra services (DB, Cache, Message Queue) running in Kubernetes environments

**TmaxSoft — Senior Researcher** <sub>2016.02 – 2018.12</sub>

Performed R&D related to computing virtualization technologies (Hypervisor, VM, Container).

- Developed "Prozone", an on-premise cloud solution enabling unified lifecycle management for virtual machines and containers
- Designed and implemented a lightweight monitoring agent to collect performance metrics from VMs and containers

**KETI (Korea Electronics Technology Institute) — Researcher** <sub>2012.12 – 2014.01</sub>

- Integrated a CoAP protocol stack into the Android framework, enabling seamless and efficient communication with IoT devices

**Samsung Electronics — Member of Software Membership** <sub>2012.08 – 2014.02</sub>

- Designed and developed the FTL (Flash Translation Layer) Simulator hardware platform, handling circuit design, PCB artwork, and soldering

</details>

## 🎓 Education

| Period | Institution | Degree |
| --- | --- | --- |
| 2014.03 – 2016.02 | (UST) University of Science and Technology, Korea | M.S., Computer Software — ARM Hypervisor Research |
| 2007.03 – 2014.02 | Kookmin University | B.S., Electrical Engineering |

## 🚀 Projects

| Project | Description |
| --- | --- |
| [kpexec](https://github.com/ssup2/kpexec) | Kubernetes CLI that runs commands in a container with high privileges |
| [network-node-manager](https://github.com/kakao/network-node-manager) | Kubernetes controller that manages the network configuration of nodes |
| [Ssup2 Blog](https://ssup2.github.io/blog-software/) | Deep-dive notes on Kubernetes, networking, Linux, and distributed systems |

## ✍️ Writing & Talks

- **AWS Korea Blog** — Data platforms on EKS, Spark applications, cross-AZ communication cost optimization
- **Kakao Tech Blog** — network-node-manager, Kubernetes cgroup internals
- **Speaker** — AWS Summit Seoul, if(kakao)

<details>
<summary>📜 <b>Certifications</b></summary>
<br>

| Certification | Issued |
| --- | --- |
| AWS Certified DevOps Engineer – Professional | 2023.12 |
| AWS Certified SysOps Administrator – Associate | 2023.08 |
| AWS Certified Data Analytics – Specialty | 2023.07 |
| AWS Certified Solutions Architect – Professional | 2023.04 |
| AWS Certified Developer – Associate | 2023.02 |
| AWS Certified Solutions Architect – Associate | 2022.10 |
| CKS: Certified Kubernetes Security Specialist | 2022.05 |
| CKAD: Certified Kubernetes Application Developer | 2022.04 |
| CKA: Certified Kubernetes Administrator | 2020.07 |
| Engineer Information Processing (정보처리기사) | 2019.08 |

</details>

<details>
<summary>🏆 <b>Awards</b></summary>
<br>

| Award | Date |
| --- | --- |
| TmaxCloud Technology Innovation Award | 2017.01 |
| Samsung Exynos Young Developer Contest — *CoAP In Android* | 2014.03 |
| Hyundai MnSoft × Kookmin Univ. UIT SMART App Festival — *Ssok Player* | 2011.06 |

</details>

<details>
<summary>📚 <b>Publications & Patents</b></summary>
<br>

- **Paper** — *Event Routing Scheme to Improve I/O Latency of SMP VM* (2015)
- **Paper** — *CoAP In Android: Implementation of CoAP Communication Between Android Platform and IoT Platform* (2014)
- **Patent** — *Event Router and Routing Method for Symmetric Multiprocessor Virtual Machine Using Queue* (US 20160364260, 2016)

</details>

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ssup2&show_icons=true&theme=default&hide_border=true&rank_icon=github)
