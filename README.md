![DevOps Banner](https://raw.githubusercontent.com/Rajesh-210/Rajesh-210/main/banner.png)

<h1 align="center">Hi 👋, I'm Rajesh Chilukuri from India 🇮🇳</h1>

<h3 align="center">
DevOps Engineer | Kubernetes | CI/CD | GitOps | Cloud Automation
</h3>

<img align="right" alt="DevOps Automation" width="380" src="https://cdn.dribbble.com/userupload/7725640/file/original-a2b82ab8779ece4c49df3672f7753ccb.gif">

<p align="left">
<img src="https://komarev.com/ghpvc/?username=Rajesh-210&label=Profile%20views&color=0e75b6&style=flat" />
</p>

---

## 👨‍💻 About Me

I am a **DevOps Engineer** specializing in **cloud-native infrastructure, Kubernetes, and CI/CD automation**.
I have hands-on experience building **production-grade EKS clusters**, implementing **GitOps with ArgoCD**, and designing **highly available systems**.

---

# 🚀 Featured DevOps Projects (Interview Ready)

## 🔹 1. Three-Tier Application on AWS EKS

**Tech Stack:** AWS EKS, Docker, Kubernetes, Jenkins, Terraform, Nginx

### 📌 What I Did

* Designed and deployed **3-tier architecture (Frontend + Backend + DB)**
* Built **CI/CD pipeline using Jenkins**
* Provisioned infrastructure using **Terraform (IaC)**
* Configured **Ingress + Load Balancer**

### 📈 Impact

* Reduced deployment time by **60%**
* Improved system scalability and fault tolerance
* Enabled zero-downtime deployments using rolling updates

---

## 🔹 2. GitOps Deployment using ArgoCD

**Tech Stack:** Kubernetes, ArgoCD, GitHub, Helm

### 📌 What I Did

* Implemented **GitOps workflow using ArgoCD**
* Used Git as **single source of truth**
* Configured **auto-sync & self-healing**
* Managed deployments using **Helm charts**

### 📈 Impact

* Eliminated manual deployments
* Reduced configuration drift
* Improved deployment reliability

---

## 🔹 3. Monitoring & Alerting System

**Tech Stack:** Prometheus, Grafana, Kubernetes

### 📌 What I Did

* Installed monitoring stack using **Helm**
* Created dashboards for **CPU, memory, pod metrics**
* Configured **alerting rules**

### 📈 Impact

* Reduced incident detection time
* Improved system observability

---

# 🏗️ DevOps Architecture

```text
Developer → GitHub → Jenkins (CI) → Docker → ECR → ArgoCD → EKS → Monitoring
```

---

# ⚙️ ArgoCD GitOps (Real Example)

## 📁 Repo Structure

```bash
k8s-manifests/
 ├── frontend/
 │    ├── deployment.yaml
 │    ├── service.yaml
 ├── backend/
 │    ├── deployment.yaml
 │    ├── service.yaml
 └── argocd-app.yaml
```

---

## 📄 ArgoCD Application YAML

```yaml
apiVersion: argoproj.io/v1alpha1
kind: Application
metadata:
  name: three-tier-app
  namespace: argocd
spec:
  project: default

  source:
    repoURL: https://github.com/Rajesh-210/k8s-manifests
    targetRevision: HEAD
    path: .

  destination:
    server: https://kubernetes.default.svc
    namespace: default

  syncPolicy:
    automated:
      prune: true
      selfHeal: true
```

---

# 🚨 Production Incident (Real-World Scenario)

### ❌ Problem

Application pods were stuck in **Pending state** in EKS.

### 🔍 Root Cause

* Node group reached **maximum capacity**
* Insufficient CPU resources

### 🛠️ Solution

* Increased node group size
* Implemented **Cluster Autoscaler**
* Optimized resource requests/limits

### ✅ Result

* Issue resolved quickly
* Improved cluster scalability
* Prevented future outages

---

# 🧰 DevOps Toolchain

<p>
<img src="https://skillicons.dev/icons?i=aws,terraform,docker,kubernetes,jenkins,githubactions,git,linux,bash,prometheus,grafana" />
<img src="https://icon.icepanel.io/Technology/svg/Argo-CD.svg" width="48" height="48" />
</p>

---

# 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Rajesh-210&show_icons=true&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rajesh-210&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

# 🌐 Connect With Me

<p align="left">
<a href="https://facebook.com/Rajesh Chilukuri"><img src="https://skillicons.dev/icons?i=facebook" /></a>
<a href="https://instagram.com/rajesh.chilukuri.549"><img src="https://skillicons.dev/icons?i=instagram" /></a>
<a href="mailto:rajeshchilukuri210@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" /></a>
</p>

---

[![](https)]()
