---
title: Unity Catalog — visão geral
---

# Unity Catalog — visão geral

## O que é
O [[Unity Catalog]] é a camada de governança central do Databricks para dados e outros ativos.  
Ele ajuda a centralizar [[Governança de dados]], controle de acesso, descoberta de dados, [[Auditoria]] e [[Lineage]].

## Como explicar em entrevista
> “Eu vejo o Unity Catalog como a camada central de governança do Databricks. Ele padroniza permissões, descoberta, ownership e rastreabilidade dos dados. Na prática, ele ajuda a tirar a governança do nível de [[Workspace]] isolado e levar para um modelo centralizado.”

## Principais benefícios
- governança centralizada
- controle de acesso unificado
- [[Lineage]] automático
- melhor descoberta de ativos
- separação mais clara entre administração, engenharia e consumo

## Resposta curta para entrevista
> “O Unity Catalog serve para centralizar a governança no Databricks: permissões, metadados, lineage e acesso a dados estruturados e [[Dados não tabulares]].”

## Quando ele faz mais diferença
- ambientes com múltiplos times
- plataformas com vários [[Workspace|workspaces]]
- necessidade de [[Auditoria]] e rastreabilidade
- governança mais forte sobre tabelas, views, [[Volume|volumes]] e modelos

## Veja também
- [[Unity Catalog — arquitetura e hierarquia]]
- [[Unity Catalog — permissões e segurança]]
- [[Unity Catalog — lineage]]
