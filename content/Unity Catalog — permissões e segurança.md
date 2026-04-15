---
title: Unity Catalog — permissões e segurança
---

# Unity Catalog — permissões e segurança

## Conceito principal
O [[Unity Catalog]] trabalha com privilégios sobre objetos governáveis.  
As permissões podem ser concedidas a usuários, grupos ou [[Service Principal|service principals]].

## Ideia importante para entrevista
O modelo segue o [[Princípio do menor privilégio]].  
Ou seja: cada pessoa ou aplicação deve ter somente o acesso necessário.

## Pontos que valem mencionar
- [[Ownership]] de objetos
- [[Grant|grants]] em catálogos, schemas e tabelas
- herança de privilégios para baixo na hierarquia
- gestão por grupos, evitando grants usuário a usuário

## Como eu responderia
> “Em vez de distribuir acesso diretamente em cada tabela de forma desorganizada, eu prefiro estruturar por grupos e herança de permissões. Isso reduz erro operacional e melhora a governança.”

## Exemplo prático
- grupo `engenharia_dados`: pode criar e manter objetos em `telecom.bronze` e `telecom.silver`
- grupo `analytics`: pode ler objetos em `telecom.gold`
- grupo `ml_team`: acesso específico a certos dados e volumes

## Erro comum que vale citar
Dar permissão direto para usuário individual em larga escala.  
Em entrevista, é melhor mostrar que você prioriza grupos e padronização.

## Veja também
- [[Princípio do menor privilégio]]
- [[Grant]]
- [[Ownership]]
- [[Service Principal]]
