# Africoin
```mermaid

---
config:
  theme: normal
  layout: dagre
---
flowchart TD
    start["Africoin"]
    
    website(["Company<br>Website"])
    click website "https://github.com/AfricoinAI/website" _blank

    studio(["Tokenisation<br>Studio"])
    click studio "https://github.com/AfricoinAI/tokenisation-studio" _blank

    regulator_dashboard(["Regulator<br>Dashboard"])

    admin_dashboard(["Admin<br>Dashboard"])

    workflows(["Workflow<br>Catalog"])

    gallery(["Gallery<br>Web App"])

    ai_services(["Agent<br>Services"])

    wallet(["Wallet<br>Mobile App"])

    faucet(["Faucet<br>Web App"])

    exchange(["RWA<br>Exchange"])

    start --> website & studio & regulator_dashboard & admin_dashboard & workflows & gallery & ai_services & wallet & faucet & exchange

```
