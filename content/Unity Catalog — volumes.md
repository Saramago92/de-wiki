---
title: Unity Catalog — volumes
---

# Unity Catalog — volumes

## O que são
[[Volume|Volumes]] são objetos do [[Unity Catalog]] voltados para governança de [[Dados não tabulares]].

## Quando citar em entrevista
Quando falarem sobre arquivos como:
- JSON bruto
- PDFs
- imagens
- checkpoints
- arquivos de estágio
- artefatos auxiliares

## Como eu explicaria
> “Tabelas governam dados tabulares. Volumes governam arquivos. Então, se eu preciso controlar acesso a arquivos não tabulares dentro do ecossistema Databricks, volumes são a escolha correta.”

## Exemplo prático
- landing de arquivos JSON de eventos
- área de stage para ingestão
- arquivos usados por ciência de dados
- logs e checkpoints operacionais

## Ponto forte para entrevista
Mostrar que você sabe que governança não é só tabela.  
Arquivos também precisam de controle, e o Unity Catalog cobre isso com volumes.

## Veja também
- [[Volume]]
- [[Dados não tabulares]]
- [[Unity Catalog — permissões e segurança]]
