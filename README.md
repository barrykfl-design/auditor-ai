🛡️ Auditor AI: The Audit & Analyzer (Enterprise-Grade DLP Audit Tool | 100% Local | Zero Data Leakage)
🛡️ Auditor AI：审计与分析工具（企业级 DLP 审计工具 | 100% 本地化 | 零数据泄露）

Auditor AI is a production-grade, AI-powered Data Loss Prevention (DLP) tool built for cybersecurity teams / Internal auditor who cannot risk sending sensitive internal data to cloud-based LLMs. It scans Windows file shares, analyzes permissions via local LLMs, and generates audit-ready reports - all within your air-gapped environment.

🚀 Key Value Proposition
"What stays in your network, stays in your network."
We eliminate the #1 risk of AI security tools: uploading confidential directory structures and permission logs to third-party APIs.

✨ Core Features
🔒 100% Privacy & Air-Gapped Design
Zero External Calls: No data ever leaves your machine. No OpenAI, no telemetry, no tracking.
Universal Compatibility: Native support for LM Studio, Ollama, and Llama.cpp.
Offline Ready: Designed for regulated industries and high-security internal networks.

🧠 AI-Driven Risk Intelligence
Automated Risk Scoring: Instant classification (High/Medium/Low) based on folder structures.
Contextual Analysis: Understands why a permission is dangerous (e.g., Ransomware susceptibility).
Prioritized Remediation: Actionable steps for IT teams, ranked by critical impact.

<img width="477" height="270" alt="image" src="https://github.com/user-attachments/assets/dacb02a4-e92c-4f8e-9202-d3881efbfeff" />


📊 Audit-Ready Deliverables  
Full Permissions CSV: Granular, line-by-line NTFS audit for SIEM/SOAR integration.  
Interactive HTML Dashboard: Visual executive summary for rapid threat response.  
AI Word Report: Professional, pre-formatted document for compliance sign-off.  
<img width="1666" height="488" alt="image" src="https://github.com/user-attachments/assets/86ac210d-f4df-4fa5-aab4-4f9147f8f7f7" />


⚠️ Critical Pain Points Solved  
The Auditor AI Solution 100% local execution. No third-party API exposure.  
High Costs	Open-source foundation. No expensive enterprise licensing.  
Manual Audits	Automated AI analysis replaces weeks of manual CSV reviews.  
Compliance Gaps	Built specifically to meet GDPR, HIPAA, and ISO 27001 standards.  

🔍 Audit & Risk Coverage Matrix  
Risk Category	Audit Capability	Inherent Risk  
Open Write Shares	Detects broad groups (Authenticated Users) with write access.	🔴 HIGH  
Open Read Shares	Identifies exfiltration vectors for sensitive documents.	🔴 HIGH  
Sensitive Data Exposure	Maps PII/Intellectual Property to open groups.	🔴 HIGH  
NTFS Misconfig	Audits ACE entries and inheritance violations.	🔴 HIGH  
Mixed Content	Detects co-located apps and data config files.	🟡 MEDIUM  

🛠️ Quick Start Guide  
1. Prerequisites
OS: Windows (Native NTFS Scanning)  
LLM Runtime: LM Studio or Ollama running a model (e.g., Llama 3, Mistral, or Phi).  
<img width="1203" height="213" alt="image" src="https://github.com/user-attachments/assets/77fcc0be-dd06-4776-9dc2-e9e0d8ce5d9c" />  

2. Installation  
We used LM Studio and using "google/gemma-3-4b" LLM free tier by default. For the Auditor-AI tool, just download the "Auditor-AI.exe" and then run directly.  

3. Input Scan  
Input the share folder you would like to scan:  
<img width="367" height="107" alt="image" src="https://github.com/user-attachments/assets/71d8ed73-f8a1-43cf-920c-6cf263fb6900" />  
  
4. Configuration
<img width="662" height="296" alt="image" src="https://github.com/user-attachments/assets/3fe7f2ae-25f7-4963-b55b-26b9279f98a7" />  

5. Execute Scan  
Press the Scan button. Three files will be generated at the same folder 1) Dashboard 2) ACL CSV 3) AI-Report.
<img width="257" height="71" alt="image" src="https://github.com/user-attachments/assets/22b62774-2dec-4a7d-b9f4-4399085cd707" />  

📄 License
Distributed under the MIT License. See LICENSE for more information.
