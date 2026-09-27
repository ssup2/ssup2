# Hi there, I'm Jungsub Shin 👋

I've spent 10+ years across the whole infrastructure stack — starting from ARM hypervisors and computing virtualization, through Kubernetes platform engineering, to cloud architecture on AWS.

<p>
  <a href="https://www.linkedin.com/in/jungsub-shin-933b82119/"><img src="https://img.icons8.com/fluency/96/linkedin.png" height="40" alt="LinkedIn"/></a>&nbsp;
  <a href="https://ssup2.github.io/blog-software/"><img src="https://img.icons8.com/fluency/96/blogger.png" height="40" alt="Blog"/></a>&nbsp;
  <a href="mailto:supsup5642@gmail.com"><img src="https://img.icons8.com/fluency/96/gmail.png" height="40" alt="Email"/></a>
</p>

## 💼 Career

| Company | Role | Summary |
|---|---|---|
| **Karrot**<br>2024.12 - Present | Site Reliability Engineer | • Migrated ~1,000 EKS nodes from Cluster Autoscaler to Karpenter with zero downtime<br>• Introduced autoscaling for job-dedicated node groups, removing manual capacity management<br>• Built & operated ~60 GPU nodes for ML model serving across teams<br>• Deployed Dagster on EKS as an internal data pipeline platform (~1,000 runs/day) |
| **Amazon Web Services**<br>2022.09 - 2024.12 | Solutions Architect | • Provided architectural guidance for Digital Native Business customers, focusing on Amazon EKS and EMR on EKS<br>• Troubleshot intermittent EKS network issues and drove Karpenter adoption for customer platforms |
| **Kakao**<br>2019.06 - 2022.09 | Software Engineer | • Developed & operated DKOS, the in-house Kubernetes platform (5,000+ clusters, 60,000+ nodes)<br>• Led the migration of ~60% of Kakao services to DKOS<br>• Developed network-node-manager to automatically detect and resolve network issues |
| **cafe24**<br>2018.12 - 2019.06 | Software Engineer | • Analyzed & operated infra services (DB, cache, message queue) on Kubernetes |
| **TmaxSoft**<br>2016.02 - 2018.12 | Senior Researcher | • Developed Prozone, an on-premise cloud solution unifying VM and container lifecycle management<br>• Built a lightweight monitoring agent collecting performance metrics from VMs and containers |
| **KETI**<br>2012.12 - 2014.01 | Researcher | • Integrated a CoAP protocol stack into the Android framework for IoT communication |
| **Samsung Electronics**<br>2012.08 - 2014.02 | Software Membership | • Built an FTL (Flash Translation Layer) simulator hardware platform, from circuit design to PCB artwork |

## 🚀 Open Source Projects I Lead

- **[kpexec](https://github.com/ssup2/kpexec)** : A kubectl plugin that runs commands in a container with high privileges for debugging; registered and maintained in [krew](https://github.com/kubernetes-sigs/krew-index) as `pexec`
- **[kakao/network-node-manager](https://github.com/kakao/network-node-manager)** : A Kubernetes controller that manages per-node network configuration, created and open-sourced at Kakao

## 🌱 Open Source Contributions

- **[kubernetes-sigs/karpenter](https://github.com/kubernetes-sigs/karpenter)** : Fix topology spread scheduling by filtering domains by NodePool compatibility ([#3181](https://github.com/kubernetes-sigs/karpenter/pull/3181), open)
- **[dagster-io/dagster](https://github.com/dagster-io/dagster)** : Automatically tag every run with its code location, plus docs ([#32715](https://github.com/dagster-io/dagster/pull/32715), [#33158](https://github.com/dagster-io/dagster/pull/33158))
- **[NVIDIA/k8s-device-plugin](https://github.com/NVIDIA/k8s-device-plugin)** : Support hostNetwork mode per component in the Helm chart ([#1365](https://github.com/NVIDIA/k8s-device-plugin/pull/1365))
- **[aws-samples/hardeneks](https://github.com/aws-samples/hardeneks)** : Improve rule output and exception handling ([#40](https://github.com/aws-samples/hardeneks/pull/40), [#41](https://github.com/aws-samples/hardeneks/pull/41))
- **[helm/charts](https://github.com/helm/charts)** : RabbitMQ full-cluster recovery policy, MariaDB docs fix ([#13027](https://github.com/helm/charts/pull/13027), [#11124](https://github.com/helm/charts/pull/11124))
- **[killme2008/xmemcached](https://github.com/killme2008/xmemcached)** : Add a session comparator to order memcached sessions by address ([#99](https://github.com/killme2008/xmemcached/pull/99))
- **[vitessio/vitess](https://github.com/vitessio/vitess)** : Set MySQL flavor via MYSQL_FLAVOR in the Helm chart ([#4473](https://github.com/vitessio/vitess/pull/4473))
- **[lxc/lxc](https://github.com/lxc/lxc)** : Fix leftover network interfaces on start failure, OCI template improvements ([#2559](https://github.com/lxc/lxc/pull/2559), [#2629](https://github.com/lxc/lxc/pull/2629), [#2657](https://github.com/lxc/lxc/pull/2657), [#2719](https://github.com/lxc/lxc/pull/2719))

## 🎤 Presentations

- **AWS Summit Seoul** : Data Processing on Containers: Woowa Brothers' Data Platform Innovation ([Korean](https://youtu.be/T2mtIkQ1vbA?si=vIsUxzaSal2F7a6z))
- **Kakao ifKakao** : Programming K8s Controller ([Korean](https://tv.kakao.com/channel/3693125/cliplink/414072325))

## ✍️ Articles

- **Karrot Blog** : Our Journey to Autoscaling EKS Node Groups for Job Workloads ([English](https://medium.com/daangn/our-journey-to-autoscaling-eks-node-groups-for-job-workloads-e8a6a7ed845e) / [Korean](https://medium.com/daangn/job-%EC%9B%8C%ED%81%AC%EB%A1%9C%EB%93%9C%EB%A5%BC-%EC%9C%84%ED%95%9C-eks-node-group-%EC%98%A4%ED%86%A0%EC%8A%A4%EC%BC%80%EC%9D%BC%EB%A7%81-%EB%8F%84%EC%9E%85%EA%B8%B0-a6a28376d153))
- **Karrot Blog** : Our Journey to Using Host Network in Kubernetes Pods ([English](https://medium.com/daangn/our-journey-to-using-host-network-in-kubernetes-pods-c87e19b63c78) / [Korean](https://medium.com/daangn/%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4-%ED%8C%8C%EB%93%9C%EC%97%90-host-network-%EB%8F%84%EC%9E%85%EA%B8%B0-99b4c02ca490))
- **AWS Korea Blog** : Woowa Brothers' Data Platform Built Around Data on EKS ([Korean](https://aws.amazon.com/ko/blogs/tech/woowa-brothers-amazon-data-on-eks-data-platform/))
- **AWS Korea Blog** : Comparing Spark Application Submission Methods on Amazon EKS ([Korean](https://aws.amazon.com/ko/blogs/tech/amazon-eks-spark-submission-comparison/))
- **AWS Korea Blog** : Reducing Cross-AZ Traffic Costs on Amazon EKS with Topology Aware Hints ([Korean](https://aws.amazon.com/ko/blogs/tech/amazon-eks-reduce-cross-az-traffic-costs-with-topology-aware-hints/))
- **Kakao Blog** : Introducing network-node-manager ([Korean](https://tech.kakao.com/2021/03/03/network-node-manager/))
- **Kakao Blog** : K8s cgroupfs Analysis and Selection ([Korean](https://tech.kakao.com/2020/06/29/cgroup-driver/))

