```mermaid

---
config:
  theme: redux
  layout: dagre
  look: handDrawn
---
flowchart LR
    start["Africoin"]
    
    website(["Website"])
    wallet(["Wallet"])
    dashboard(["Regulator Dashboard"])
    studio(["Tokenisation Studio"])
    gallery(["Gallery"])
    faucet(["Faucet"])
    exchange(["Exchange"])

    start --> website & studio & dashboard & gallery & wallet & faucet & exchange

```
