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
    studio(["Tokenisation<br>Studio"])
    gallery(["Gallery"])
    faucet(["Faucet"])
    exchange(["Exchange"])

    start --> website & wallet & studio & gallery & faucet & exchange

```
