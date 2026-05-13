# Africoin Services
```mermaid

---
config:
  theme: normal
  layout: dagre
---
flowchart LR
    start["Africoin"]
    
    website(["Website"])
    studio(["Tokenisation Studio"])
    regulator_dashboard(["Regulator Dashboard"])
    admin_dashboard(["Admin Dashboard"])
    gallery(["Gallery"])
    ai_services(["Agent Services"])
    wallet(["Wallet"])
    faucet(["Faucet"])
    exchange(["Exchange"])

    start --> website & studio & regulator_dashboard & admin_dashboard & gallery & ai_services & wallet & faucet & exchange

```
