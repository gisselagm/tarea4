``` mermaid
graph TD;
  A[Inici] --> B{Decisió}
  B -- Sí --> C[Acció]
  B -- No --> D[Altres accions]
  C --> E[Fins aquí]
  D --> E[Fins aquí]
```