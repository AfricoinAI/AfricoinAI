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
    studio(["Tokenisation Studio"])
    gallery(["Gallery"])
    faucet(["Faucet"])
    exchange(["Exchange"])

    start --> website & studio & gallery & wallet & faucet & exchange

```
