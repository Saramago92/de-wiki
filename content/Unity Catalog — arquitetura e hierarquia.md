---
title: Unity Catalog — arquitetura e hierarquia
---

# Unity Catalog — arquitetura e hierarquia

## Hierarquia principal
A hierarquia lógica mais importante é:

- [[Metastore]]
- [[Catalog]]
- [[Schema]]
- tabelas, views, [[Volume|volumes]], modelos e outros objetos

## Como explicar isso em entrevista
> “O metastore é o topo da governança. Dentro dele eu organizo catálogos, depois schemas, e dentro deles os objetos de dados. Isso facilita segmentar ambientes, domínios e responsabilidades.”

## Exemplo prático
- metastore: governança central da empresa
- catalog: `finance`, `marketing`, `telecom`
- schema: `bronze`, `silver`, `gold`
- tabelas: `clientes`, `faturas`, `eventos_rede`

## Exemplo de nome completo
`telecom.silver.eventos_rede_limpos`

## Boa resposta de entrevista
> “Eu costumo pensar no catalog como uma fronteira de domínio ou ambiente, no schema como uma camada lógica de organização, e nas tabelas e views como os ativos consumidos no dia a dia.”

## Veja também
- [[Metastore]]
- [[Catalog]]
- [[Schema]]
- [[Unity Catalog — boas práticas]]
