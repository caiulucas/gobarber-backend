## Patterns
- Repository - Criar repositórios para lidar com as funções de um modelo

## DATA
- DTO: Data Transfer Object

## Routes
- Receber uma requisição, chamar outro arquivo, devolver resposta

## SOLID
- Single Responsability
- Linskov Substitution
- Dependency Inversion

## Resumo

Tudo que transforma dado, deixamos na rota
Tudo o que é lógica, colocamos num service

O service tem que ter uma única responsabilidade (Um método)

## MIGRATIONS
- Você só pode alterar uma migration se ela não foi enviada ainda pro sistema de
controle de versão. Se não, criar obrigatóriamente outra migration

## Testes Automatizados

Garante que a aplicação continue funcionando independente do número de novas
funcionalidades e do número de devs no time.

1. Testes unitários

Testam funcionalidades específicas da nossa aplicação (precisam ser funções puras).

JAMAIS: Chama à API, possui efeito colateral.

2. Testes de integração

Testam uma funcionalidade completa, passando por várias camadas da aplicação.

Route -> Controller -> Serviço -> Repositório -> ...

3. Testes E2E

Testes que simulam a ação do usuário dentro da nossa aplicação.

1. Clique no input de email
2. Preencha caiolucas@gmail.com
3. Clique no Input de senha
4. Preencha 123456
5. Clique no botão "Logar"
6. Espero que a página tenha enviado o usuário para o dashboard

## TDD (Test Driven Development)

- Quando ele se cadastrar na aplicação, ele deve receber um email de boas vindas;
