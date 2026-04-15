---
title: Unity Catalog — perguntas e respostas
---

# Unity Catalog — perguntas e respostas

## 1. O que é o [[Unity Catalog]]?
É a camada de governança central do Databricks para dados e outros ativos, com foco em permissões, descoberta, [[Lineage]] e [[Auditoria]].

## 2. Qual a vantagem sobre um modelo mais antigo por [[Workspace]]?
Centraliza a governança e reduz a fragmentação de regras e metadados entre workspaces.

## 3. Como você organizaria os objetos?
Eu organizaria por domínio ou ambiente no nível de [[Catalog]], por camada lógica no [[Schema]], e deixaria tabelas e views como ativos de consumo e transformação.

## 4. Como controlaria acesso?
Por grupos, herança de privilégios e [[Princípio do menor privilégio]].

## 5. Quando usar [[Tabela gerenciada]] ou [[Tabela externa]]?
Managed quando quero simplicidade e governança mais nativa; external quando os dados já vivem fora e precisam ser registrados e controlados.

## 6. O que são [[Volume|volumes]]?
São objetos para governar [[Dados não tabulares]].

## 7. Por que [[Lineage]] é importante?
Porque melhora auditoria, análise de impacto e troubleshooting.

## 8. Qual erro evitar?
Criar governança excessivamente manual, sem padrão, concedendo acesso diretamente para usuários individuais.

## 9. Como soar mais sênior ao falar disso?
Saindo do nível de feature e falando de impacto: risco, escalabilidade operacional, padronização, rastreabilidade e governança.

## Veja também
- [[Unity Catalog — respostas fortes]]
- [[Unity Catalog — resumo final]]
