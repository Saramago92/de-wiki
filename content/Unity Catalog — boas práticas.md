---
title: Unity Catalog — boas práticas
---

# Unity Catalog — boas práticas

## 1. Usar grupos em vez de grants individuais
Facilita manutenção e reduz erros. Veja [[Grant]].

## 2. Aplicar [[Princípio do menor privilégio]]
Evita acessos desnecessários.

## 3. Padronizar nomenclatura
Exemplo:
- catálogos por domínio
- schemas por camada
- nomes de tabela claros

## 4. Preferir [[Tabela gerenciada|managed tables]] quando possível
Reduz complexidade operacional.

## 5. Separar responsabilidades
Quem administra governança não precisa ser o mesmo que desenvolve pipelines.

## 6. Organizar por domínio ou ambiente com critério
Evita catálogo virar bagunça.

## 7. Pensar em [[Auditoria]] e rastreabilidade
Governança não é só liberar acesso; é também saber quem usa e como usa.

## Resposta de entrevista
> “Eu tento usar Unity Catalog com foco em padronização, grupos, menor privilégio e organização por domínio ou camada. O objetivo não é só segurança, mas também escalabilidade operacional.”

## Veja também
- [[Unity Catalog — permissões e segurança]]
- [[Unity Catalog — arquitetura e hierarquia]]
