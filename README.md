<!-- PROFILE HEADER -->
<h1 align="center">Hi, I'm Kalpit Swami 👋</h1>
<p align="center">
  <b>Cloud & DevOps Engineer</b> - building production-grade AWS infrastructure with <b>Terraform</b>, <b>Kubernetes</b>, and <b>GitHub Actions CI/CD</b>.
  <br/>
  <b>AWS Certified Solutions Architect - Associate</b> · <b>AWS JAM Winner</b> · <b>4.0 GPA</b>
</p>

<p align="center">
  <a href="https://www.kalpitswami.com">🌐 Portfolio</a> •
  <a href="https://www.linkedin.com/in/kalpitswami">LinkedIn</a> •
  <a href="mailto:kalpit.swami@gmail.com">Email</a> •
  <a href="https://medium.com/@kalpit.swami">Medium</a>
</p>

<!-- GITHUB STATS -->
<p align="center">
  <img 
    src="https://github-readme-stats.vercel.app/api?username=kalpit10&show_icons=true&hide_title=true&hide_rank=true&bg_color=00000000&theme=transparent&hide=contribs,prs" 
    height="160"
  />
  <img 
    src="https://github-readme-streak-stats.herokuapp.com/?user=kalpit10&theme=transparent&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" 
    height="160"
  />
</p>

<p align="center">
  <img 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=kalpit10&layout=compact&hide_title=true&bg_color=00000000&theme=transparent&langs_count=8" 
    height="160"
  />
</p>

---

## 🚀 What I Do

- Architect **secure, multi-environment AWS infrastructure** with modular Terraform
- Build **CI/CD pipelines** with GitHub Actions and OIDC federated authentication — no long-lived access keys
- Deploy **containerized microservices** on Amazon EKS with IRSA, ALB Ingress, and HPA
- Apply **least-privilege IAM, secrets management, and layered network security** by default

Recently completed a Government of Ontario co-op where I automated infrastructure provisioning across 21 sites with Ansible.

---

## 🌟 Featured Projects

### **1) Cloud-Native E-Commerce Deployment on AWS**
Production-grade microservices platform on EKS with full IaC and automated deployments.

- Provisioned multi-environment AWS infra using **modular Terraform** (VPC, EKS, ECR, Secrets Manager) with S3 remote state and DynamoDB locking
- Built **GitHub Actions CI/CD with OIDC authentication** and environment detection — auto-pushing container images to ECR for dev and prod
- Deployed microservices on **Amazon EKS with IRSA secrets injection**, ALB Ingress routing, and HPA for CPU-based auto-scaling
- Designed layered VPC with public/private subnets across two AZs, isolating worker nodes behind NAT Gateway

🔗 [Infrastructure Repo](https://github.com/kalpit10/Capstone-Infra-Team4) · [WebApp Repo](https://github.com/kalpit10/Capstone-WebApp)

---

### **2) Production-Ready 3-Tier AWS Infrastructure with Terraform & CI/CD**
End-to-end automated 3-tier architecture with security and observability built in.

- Built modular **Terraform 3-tier architecture** (ALB, ASG, RDS MySQL) with S3 remote state, DynamoDB locking, and security group chaining for least-privilege traffic flow
- Integrated **GitHub Actions CI/CD with OIDC authentication** and a manual approval gate — running fmt/validate/plan on PRs and gated apply on merge
- Secured workloads with **AWS Secrets Manager**, IMDSv2 enforcement, scoped IAM instance profiles, and Bastion host SSH access
- Implemented **CloudWatch observability** with the CloudWatch Agent and dashboards tracking EC2 CPU, memory, and disk metrics

🔗 [Repo](https://github.com/kalpit10/3-Tier-Web-Architecture-Terraform-)

---

### **3) Serverless Portfolio (S3 + CloudFront + OIDC)**
Live React portfolio deployed via secure, keyless CI/CD.

- Deployed React portfolio with **AWS S3, CloudFront, and ACM SSL** on a custom domain
- Automated deployments via **GitHub Actions with OIDC federated authentication** — eliminated all long-lived AWS access keys
- Scoped IAM role with least-privilege S3 permissions for the deploy pipeline

🔗 [Live Site](https://www.kalpitswami.com)

---

### **4) Resumaid - Resume Builder & ATS Scanner (MERN + Security)**
Security-focused full-stack web app aligned with OWASP Top 10.

- Developed a MERN stack web app to build resumes and perform ATS keyword analysis
- Implemented **AES-256-CBC encryption, MFA, bcrypt hashing, and JWT authentication**
- Designed and deployed as Dockerized microservices

🔗 [Repo](https://github.com/kalpit10/Resumaid)

---

## 🧰 Tech Toolbox

<p align="center"><strong>Cloud & IaC</strong></p>
<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
</p>

<p align="center"><strong>AWS Services</strong></p>
<p align="center">
  <img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"/>
  <img src="https://img.shields.io/badge/VPC-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/EKS-5A2EE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/ECR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/ALB-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Auto Scaling-FF4F00?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"/>
  <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
  <img src="https://img.shields.io/badge/CloudFront-8C4FFF?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/CloudWatch-FF4F00?style=for-the-badge&logo=amazoncloudwatch&logoColor=white"/>
  <img src="https://img.shields.io/badge/IAM-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Secrets Manager-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>

<p align="center"><strong>DevOps & Containers</strong></p>
<p align="center">
  <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

<p align="center"><strong>Scripting & OS</strong></p>
<p align="center">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

<p align="center"><strong>Web Development</strong></p>
<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
</p>

---

## 🎓 Education

- **PG Certificate – Cloud Architecture & Administration**, Seneca Polytechnic *(May 2025 – Apr 2026)* - **4.0 GPA, High Honors**
- **PG Certificate – Cybersecurity & Threat Management**, Seneca Polytechnic *(Sep 2024 – Apr 2025)* - **4.0 GPA, High Honors**
- **Bachelor of Computer Applications (BCA)**, Guru Gobind Singh Indraprastha University, New Delhi *(2020 – 2023)* - **3.8 GPA**

---

## 🏅 Certifications & Awards

- **AWS Certified Solutions Architect – Associate** (SAA-C03) - 2026
- **2x AWS JAM Podium Finalist 🏆 (1st & 2nd)** - Team Competition
- **4x President's Honour List** - Academic excellence in Cloud Architecture & Cybersecurity
