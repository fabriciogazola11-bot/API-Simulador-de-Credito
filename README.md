# API de Gerenciamento de Tarefas

## Descrição

Este projeto é uma API REST desenvolvida com Spring Boot para gerenciamento simples de tarefas em memória.

A aplicação permite:

- Listar tarefas cadastradas;
- Adicionar novas tarefas;
- Remover todas as tarefas cadastradas.

Os dados são armazenados apenas durante a execução da aplicação, sem utilização de banco de dados.

---

## Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Web
- Jackson (JSON)
- Maven

---

## Estrutura do Projeto
src/
└── main/
├── java/
│ └── com/
│ └── eloscred/
│ └── Simulador/
│ └── controller/
│ └── ApiController.java
└── resources/

## Melhorias Futuras
Utilização de banco de dados;
Atualização de tarefas;
Exclusão individual de tarefas;
Identificador único (ID) para cada tarefa;
Documentação com Swagger/OpenAPI;
Persistência dos dados.

## Autor

Projeto desenvolvido por Fabricio, como estudo de APIs REST utilizando Spring Boot.


### Análise do projeto

**Objetivo:** Criar uma API simples para gerenciamento de tarefas.

**Pontos positivos:**
- Uso correto de `@RestController`;
- Endpoints REST básicos implementados;
- Utilização do `ObjectMapper` para serialização JSON;
- Código simples e fácil de entender.

**Possíveis melhorias:**
1. Retornar diretamente `List<String>` em vez de converter manualmente para JSON.
2. Criar uma classe `Task` com `id` e `descricao`.
3. Utilizar banco de dados para persistência.
4. Adicionar tratamento de erros e validações.
5. Implementar testes unitários.

**Nível do projeto:** Iniciante → Intermediário (Spring Boot REST API básica).

**Confiabilidade da análise:** 98%.
