# **Weeks 7–8 — Module 4: AI Governance, Compliance & Policy‑as‑Code**

This is Module 4 of 5 of the [12‑week Security Architect Program](https://github.com/epatter1/AI_Data_Security_Architect_Program/blob/main/12_week_overview.md)

### Focus areas
* #### Build an enterprise AI governance framework aligned to ISO 42001 & NIST AI RMF
* #### Map AI systems to GDPR, HIPAA, and global regulatory requirements
* #### Implement policy‑as‑code (AWS SCPs, Azure Policy, GCP Org Policies)
* #### Create an AI risk register + use case intake workflow

#### Deliverables:
* AI Governance Framework Repo + Policy‑as‑Code Library + AI Risk Register: [Link to walkthrough](https://github.com/epatter1/Enterprise_Ready_Governance_Frameworks/blob/main/Walkthrough.md)

---

## **Technologies, Frameworks & Cloud Services Used**

### 🧠 **AI Governance, Compliance & Responsible AI**

<a href="NIST-AI-RMF">
  <img src="https://img.shields.io/badge/NIST-AI_RMF-blue" />
</a>
<a href="ISO-42001">
  <img src="https://img.shields.io/badge/ISO-42001-005C5C" />
</a>
<a href="GDPR">
  <img src="https://img.shields.io/badge/GDPR-Compliance-4B0082" />
</a>
<a href="HIPAA">
  <img src="https://img.shields.io/badge/HIPAA-Compliance-6A5ACD" />
</a>
<a href="Responsible-AI">
  <img src="https://img.shields.io/badge/Responsible_AI-Governance-green" />
</a>

---

### 🔐 **Security, Policy‑as‑Code & Risk Management**

<a href="AWS-SCP">
  <img src="https://img.shields.io/badge/AWS-Service_Control_Policies-232F3E?logo=amazonaws&logoColor=white" />
</a>
<a href="Azure-Policy">
  <img src="https://img.shields.io/badge/Azure-Policy-0078D4?logo=microsoftazure&logoColor=white" />
</a>
<a href="GCP-Org-Policies">
  <img src="https://img.shields.io/badge/GCP-Org_Policies-4285F4?logo=googlecloud&logoColor=white" />
</a>
<a href="Risk-Register">
  <img src="https://img.shields.io/badge/AI_Risk_Register-Templates-6A5ACD" />
</a>
<a href="STRIDE">
  <img src="https://img.shields.io/badge/Threat_Modeling-STRIDE-purple" />
</a>

---

## ☁️ **Cloud Platforms**

### **AWS**

<a href="AWS">
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white" />
</a>
<a href="IAM">
  <img src="https://img.shields.io/badge/IAM-Access_Control-FF9900?logo=amazonaws&logoColor=white" />
</a>
<a href="SCP">
  <img src="https://img.shields.io/badge/Service_Control_Policies-FF4F00?logo=amazonaws&logoColor=white" />
</a>

---

### **Azure**

<a href="Azure">
  <img src="https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white" />
</a>
<a href="Azure-Policy">
  <img src="https://img.shields.io/badge/Azure_Policy-0089D6?logo=microsoftazure&logoColor=white" />
</a>
<a href="Entra-ID">
  <img src="https://img.shields.io/badge/Entra_ID-Identity_Governance-0078D4?logo=microsoftazure&logoColor=white" />
</a>

---

### **GCP**

<a href="GCP">
  <img src="https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white" />
</a>
<a href="Org-Policies">
  <img src="https://img.shields.io/badge/Org_Policies-4285F4?logo=googlecloud&logoColor=white" />
</a>
<a href="IAM">
  <img src="https://img.shields.io/badge/IAM-Policy_Constraints-34A853?logo=googlecloud&logoColor=white" />
</a>

---

## 🛠️ **DevOps, Infrastructure & Tooling**

<a href="Terraform">
  <img src="https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white" />
</a>
<a href="OPA">
  <img src="https://img.shields.io/badge/Open_Policy_Agent-000000?logo=openpolicyagent&logoColor=white" />
</a>
<a href="Python">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
</a>
<a href="YAML">
  <img src="https://img.shields.io/badge/YAML-Config_Files-000000" />
</a>

---

## 📊 **Documentation & Visualization**

<a href="Markdown">
  <img src="https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white" />
</a>
<a href="Architecture-Diagrams">
  <img src="https://img.shields.io/badge/Architecture_Diagrams-4285F4" />
</a>
<a href="Governance-Framework">
  <img src="https://img.shields.io/badge/AI_Governance-Framework-green" />
</a>
<a href="Risk-Register">
  <img src="https://img.shields.io/badge/AI_Risk_Register-Templates-6A5ACD" />
</a>

---

# **WEEK 7 — AI Governance Framework + Compliance Mapping**

### **1. Set Up the Governance Framework Structure**
```
module4-ai-governance/
    governance-framework/
    compliance/
    policy-as-code/
    risk-register/
    diagrams/
    docs/
```

---

### **2. Build the AI Governance Framework**
Folder: `governance-framework/`

Includes:
- ISO 42001 alignment  
- NIST AI RMF mapping  
- Governance roles & responsibilities  
- Model lifecycle governance  
- Human‑in‑the‑loop requirements  

---

### **3. Map AI Systems to GDPR & HIPAA**
Folder: `compliance/`

You will:
- Identify personal data categories  
- Map AI workflows to GDPR Articles  
- Map PHI flows to HIPAA safeguards  
- Document data minimization + retention  

---

### **4. Create Governance Architecture Diagram**
Diagram: `diagrams/week7_governance_architecture.md`

```
┌──────────────────────────────────────────┐
│ AI Governance Framework                  │
│ ISO 42001 • NIST AI RMF                  │
└──────────────────────────────────────────┘
                    │
                    ▼
┌──────────────────────────────────────────┐
│ Compliance Layer (GDPR / HIPAA / SOC2)   │
└──────────────────────────────────────────┘
                    │
                    ▼
┌──────────────────────────────────────────┐
│ Policy-as-Code (AWS / Azure / GCP)       │
└──────────────────────────────────────────┘
```

---

# **WEEK 8 — Policy‑as‑Code + AI Risk Register**

### **1. Implement Policy‑as‑Code Across Clouds**
Folder: `policy-as-code/`

Includes:
- AWS Service Control Policies (SCPs)  
- Azure Policy definitions  
- GCP Organization Policies  

Examples:
- Block public AI endpoints  
- Enforce encryption  
- Restrict model deployment regions  
- Require private networking  

---

### **2. Build the AI Risk Register**
Folder: `risk-register/`

Includes:
- Risk scoring model  
- Use case intake form  
- Impact × likelihood matrix  
- Control recommendations  
- Compliance mapping  

---

### **3. Add Case Studies + Documentation**
Folder: `docs/case_studies/`

Examples:
- GDPR risk assessment for LLM‑based HR chatbot  
- HIPAA mapping for clinical AI model  
- SCP enforcement preventing unapproved AI deployments  

---

### **4. Create the Enterprise AI Governance Playbook**
File: `docs/ai_governance_playbook.md`

Sections:
- Governance principles  
- Risk management workflows  
- Policy‑as‑code enforcement  
- Compliance mapping  
- Use case intake + approval  
- Monitoring & continuous assurance  

---

## **End of Weeks 7–8 Deliverables**

### ✅ **AI Governance Framework Repository**
Includes:
- Governance framework aligned to ISO 42001 & NIST AI RMF  
- GDPR/HIPAA compliance mapping  
- Policy‑as‑code for AWS, Azure, GCP  
- AI risk register + intake workflow  
- Architecture diagrams  
- Case studies  

### ✅ **Enterprise AI Governance Playbook**
A polished, executive‑ready governance package for enterprise AI programs.
