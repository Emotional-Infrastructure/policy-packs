# Policy Packs

Reusable YAML-based compliance policies for the **AI Governance Stack**.

These packs define enforcement rules for different risk states (`Normal`, `Restricted`, `Acute`) 
and can be loaded directly by the **Middleware Core** at runtime.

---

## 📦 Included Policies

- **policy-no-hate-speech.yaml** → Blocks hate speech and extremist content.  
- **policy-no-self-harm.yaml** → Blocks self-harm content, adds crisis resources.  
- **policy-no-financial-advice.yaml** → Restricts financial advice, adds disclaimers.  
- **policy-no-medical.yaml** → Restricts medical advice, adds healthcare disclaimers.  

---

## 🚀 Usage

### 1. Download Policy Packs
Clone this repo or download individual YAML files:
```bash
git clone https://github.com/Emotional-Infrastructure/policy-packs.git
cd policy-packs
