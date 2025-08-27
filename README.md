```mermaid

flowchart TD
  A([Inicio])
  A --> B{Faça uma escolha}
  B --> C[OP1]
  B --> E[OP2]
  B --> D[OP3]

```

```mermaid
graph TD;
  A[Inicio] --> B{Nota >6};
  B --> |SIM| C[Aprovado];
  C --> |NÂO| D[Reprovado];
```

```mermaid
gantt
  title Exemplo de Gráfico de Gantt
  dateFormat YYYY-MM-DD
  section 1° Bimestre
  1° Bimestre ✅ Finalizado : a1, 2025-02-02, 60d
  2° Bimestre ✅ Finalizado : a2, after a1, 60d
  section 2° Bimestre
  3° Bimestre ⌛ Em andamento:a3, 2025-08-02, 60d
  4° Bimestre ➡️ Em andamento:a4, after a3, 60d
  
```

