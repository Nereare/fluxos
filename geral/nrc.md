---
title: Não Responde
parent: Geral
nav_order: 1
last_modified_date: 2025-11-05 12:58:00 -0300
---

# Não Responde a Chamados

{: .warning }
**Não** espere resposta da busca ativa para dar alta. Dê alta e, se paciente fôr encontrado, a reverta.

```mermaid
graph LR
  A([Não Responde]) -- Triagem --> B{DT<br>ou<br>Vermelho}
  B -- Sim --> C(Não assumir) --> C1(Sinalizar Apoio)
  B -- Não --> D(Chamar **03** vezes<br>no painel)
  D -- NRC --> E(Anotar e **liberar**<br>NRC em FA)
  E --> F(Alta da FA por evasão)
  F --> G(Sinalizar Apoio para<br>Busca Ativa)
```

## Observações

- **Sempre** anotar tentativas de chamado em FA e liberar.
- Usar CID-10 `Z00.0` ou `Z35.2` na HD.
- Preencher com `Não` o campo de Reavaliação.
- Em paciente sendo encontrado, reverta alta e siga atendimento seja por nova FA de 1º Atendimento, seja por Reavaliação.
