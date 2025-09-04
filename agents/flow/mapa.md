# Flujo de trabajo (GPTs)

```mermaid
flowchart LR
  U[Tú] --> D[Rafael Dudamel\nCoordinador]
  subgraph Repos
    R[Repo código: o-frontend]
    M[(Mirror público: o-frontend-docs\nagents/**)]
  end
  D -->|Handoff| W[Winston Churchill\nDB lectura]
  W -->|tabla/CSV| DR[Dennis Ritchie\nFrontend (patch)]
  W --> NM[Nelson Mandela\nSeguridad/Docs]
  D -->|Plan| IM[Imhotep Odoo JSON-RPC]
  IM --> LD[Leonardo da Vinci\nDiseño]
  DR --> A[Aplicas patch\nPruebas + commit]
  NM --> A
  R -->|subtree split| M
  M --> D
  M --> W
```
