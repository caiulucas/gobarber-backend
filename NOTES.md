## Patterns
- Repository - Criar repositórios para lidar com as funções de um modelo

## DATA
- DTO: Data Transfer Object

## Routes
- Receber uma requisição, chamar outro arquivo, devolver resposta

## SOLID
- Single Responsability
- Dependency Inversion

## Resumo

Tudo que transforma dado, deixamos na rota
Tudo o que é lógica, colocamos num service

O service tem que ter uma única responsabilidade (Um método)

## MIGRATIONS
-Você só pode alterar uma migration se ela não foi enviada ainda pro sistema de
controle de versão. Se não, criar obrigatóriamente outra migration
