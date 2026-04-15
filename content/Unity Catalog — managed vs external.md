---
title: Unity Catalog — managed vs external
---

# Unity Catalog — managed vs external

## [[Tabela gerenciada]]
São tabelas cujo armazenamento e otimizações são geridos pelo Databricks dentro do contexto governado pelo [[Unity Catalog]].

## [[Tabela externa]]
Apontam para dados que já existem em storage externo e são registrados no catálogo.

## Como explicar em entrevista
> “Se eu quero mais simplicidade operacional e maior alinhamento com a governança da plataforma, managed tables costumam ser a escolha preferencial. External tables fazem sentido quando os dados já existem fora e eu preciso governar o acesso sem necessariamente mover tudo.”

## Regra prática
- managed: melhor quando Databricks é o centro da operação
- external: melhor quando já existe storage externo compartilhado ou legado

## Resposta curta
> “Managed prioriza simplicidade e governança nativa; external atende melhor cenários de integração com dados que já existem fora do gerenciamento direto do Databricks.”

## Veja também
- [[Tabela gerenciada]]
- [[Tabela externa]]
- [[Delta Lake]]
