# ShellHacks-2025-
# FraudDetector

A lightweight PCI DSS compliance and audit dashboard built with **Python + Flask**.  
It ingests payment, authentication, and storage logs, runs rule checks mapped to PCI DSS requirements (Req 1, 3, 7, 8, 10), and visualizes results in a traffic-light dashboard:  

- ✅ **Compliant**  
- ⚠️ **At Risk**  
- ❌ **Non-Compliant**  

GRC professionals can view findings with remediation tips and export a PCI Mini Audit Report (Markdown or optional PDF).  

---

## Features  
- Ingests CSV/JSON logs (transactions, authentication, storage events)  
- Rule engine mapped to **PCI DSS requirements**  
- Dashboard with compliance status, KPI tiles, and findings table  
- One-click export of PCI Mini Audit Report (Markdown, PDF optional)  
- Simple, hackathon-ready MVP (72-hour build)  

---

## Getting Started  

### Prerequisites  
- Python 3.9+  
- pip  
- (Optional) wkhtmltopdf installed if you want PDF reports  

### Setup  

Clone the repository and install dependencies:  
```bash
git clone https://github.com/yourusername/FraudDetector.git
cd FraudDetector
pip install -r requirements.txt
