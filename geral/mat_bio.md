---
title: Acidente c/ Material Biológico
parent: Geral
nav_order: 15
last_modified_date: 2025-11-09 15:18:00 -0300
---

# Acidentes Com Material Biológico

{: .info-title }
> Atenção
>
> Se o paciente sofreu um acidente de trabalho **sem** exposição a material biológico, este não é o fluxo correto. Veja [fluxo específico](work_injury).

## Antes de resultado de TR-HIV

```mermaid
graph LR
  A([Acidente Pérfuro]) --> B(Coleta sangue) & C(Abertura de FA no PS)
  B & C --> D(Entregar Amostras<br>Lab 4º andar)
  D --> E(Atendimento inicial)
  E --> F[Aguardar<br>TR-HIV]
```

## Após resultado de TR-HIV

```mermaid
graph LR
  A([TR Pronto]) --> B{TR-HIV}
  B -- **NÃO** reagente --> C(PEP **não**<br>indicado)
  C --> D[Alta do<br>seguimento]
  B -- **REAGENTE** --> E(PEP **indicado**)
  E --> F(Enc SEESMT) & G(Enc MI)
  F & G --> H(Alta **PS**)
  H --> I(Seguimento MI<br>continua amb)
```
