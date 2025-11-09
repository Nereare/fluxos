---
title: Não Responde
parent: Geral
nav_order: 1
last_modified_date: 2025-11-05 12:58:00 -0300
---

# Não Responde a Chamados

```mermaid
graph TD
  A([Não Responde]) -- Triagem --> B{DT<br>ou<br>Vermelho}
  B -- Sim --> C(Não assumir)
  B -- Não --> D(Anotar e **liberar**<br>NRC em FA)
  D --> E(Alta da FA por evasão)
  E --> F(Sinalizar Apoio para<br>Busca Ativa)
```
