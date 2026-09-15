# QA API Testing — Postman

## Sobre o projeto

Este repositório apresenta um **portfólio técnico de testes de API**, desenvolvido com foco na demonstração de práticas e competências aplicadas à atividade de QA.

O projeto utiliza o **Postman** para execução, validação e automação de testes sobre uma API pública, contemplando desde a definição dos cenários até o registro dos resultados e respectivas evidências.

A proposta é demonstrar não apenas a utilização da ferramenta, mas principalmente a aplicação de uma **abordagem de qualidade orientada à análise, validação, identificação de riscos e evidências**.

---

## Objetivo

Demonstrar a aplicação prática de conhecimentos relacionados a testes de API, incluindo:

* Análise do comportamento esperado da API;
* Identificação de cenários de teste;
* Elaboração de cenários positivos e negativos;
* Execução de requisições HTTP;
* Validação de códigos de status;
* Análise de respostas JSON;
* Validação de campos, tipos e valores;
* Verificação de regras e comportamentos esperados;
* Automação de validações utilizando scripts do Postman;
* Registro e análise dos resultados;
* Organização de evidências de teste.

---

## Abordagem de QA

O projeto será desenvolvido considerando o seguinte fluxo:

```text
Análise
   ↓
Planejamento
   ↓
Cenários de Teste
   ↓
Execução
   ↓
Validação
   ↓
Evidências
   ↓
Resultados
   ↓
Análise
```

A intenção é reproduzir, em um ambiente controlado e público, uma abordagem próxima à utilizada em atividades reais de QA.

Cada cenário será analisado considerando:

* Objetivo;
* Pré-condições;
* Dados de entrada;
* Requisição;
* Resultado esperado;
* Validações;
* Resultado obtido;
* Evidência;
* Status.

---

## Escopo

O projeto contemplará testes relacionados ao consumo de uma API pública, incluindo, conforme aplicável:

### Testes funcionais

Validação do comportamento esperado das funcionalidades disponibilizadas pela API.

### Testes positivos

Utilização de dados e parâmetros válidos, verificando se a API retorna os resultados esperados.

### Testes negativos

Utilização de dados inválidos, inexistentes ou incompletos, avaliando o comportamento da API diante de condições inesperadas.

### Testes de validação

Verificação de:

* Status HTTP;
* Estrutura da resposta;
* Campos obrigatórios;
* Tipos de dados;
* Valores retornados;
* Mensagens de resposta;
* Regras esperadas.

### Testes automatizados

Utilização dos recursos de testes do Postman para automatizar validações das respostas obtidas.

---

## Ferramentas e tecnologias

| Tecnologia  | Utilização                             |
| ----------- | -------------------------------------- |
| Postman     | Execução e automação dos testes de API |
| HTTP / REST | Comunicação com a API                  |
| JSON        | Análise das respostas                  |
| JavaScript  | Scripts de validação no Postman        |
| Git         | Versionamento                          |
| GitHub      | Repositório e documentação do projeto  |

---

## Arquitetura do repositório

```text
qa-api-testing-postman/
│
├── README.md
│
├── docs/
│   ├── estrategia-de-testes.md
│   ├── cenarios-de-teste.md
│   └── resultados.md
│
├── postman/
│   ├── collections/
│   └── environments/
│
├── evidencias/
│
└── .gitignore
```

### `docs/`

Documentação relacionada ao processo de testes.

**estrategia-de-testes.md**

Define a abordagem utilizada no projeto, escopo, tipos de teste e critérios considerados.

**cenarios-de-teste.md**

Contém os cenários elaborados para as funcionalidades analisadas.

**resultados.md**

Apresenta os resultados das execuções e a análise dos testes realizados.

### `postman/`

Armazena os artefatos relacionados ao Postman.

**collections/**

Collections utilizadas para organizar as requisições e testes.

**environments/**

Configurações de ambiente utilizadas durante as execuções, sem exposição de credenciais ou informações sensíveis.

### `evidencias/`

Armazena evidências relacionadas às execuções dos cenários de teste.

As evidências serão organizadas de forma rastreável, relacionando cada arquivo ao respectivo caso de teste.

---

## Rastreabilidade

A organização do projeto busca manter a rastreabilidade entre:

```text
Cenário de Teste
      ↓
Requisição
      ↓
Validação
      ↓
Resultado
      ↓
Evidência
```

Essa estrutura permite relacionar o que foi planejado com o que foi efetivamente executado e observado.

---

## Segurança

Informações sensíveis, como:

* API Keys;
* Tokens;
* Senhas;
* Credenciais;
* Variáveis privadas;

não serão armazenadas diretamente no repositório público.

As configurações necessárias para execução serão mantidas por meio de variáveis de ambiente ou mecanismos apropriados do Postman.

---

## Status do projeto

**Em desenvolvimento**

A estrutura inicial do projeto foi definida. Os cenários, requisições, validações, evidências e resultados serão incorporados conforme a execução das etapas de teste.

---

## Objetivo profissional

Este repositório faz parte do meu portfólio técnico e tem como objetivo apresentar, de forma prática e documentada, minha experiência e abordagem profissional em atividades de **Quality Assurance**, com foco em testes de API.

O projeto busca demonstrar a capacidade de:

> **Analisar → Planejar → Testar → Validar → Documentar → Evidenciar**

mais do que simplesmente demonstrar o uso de uma ferramenta.
