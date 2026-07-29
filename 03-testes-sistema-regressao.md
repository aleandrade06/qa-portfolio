# Projeto 3 — Testes de sistema e regressão

## Visão geral

Estudo acadêmico de testes para formulários e regras de negócio, reunindo mapeamento de cenários, modelagem BDD, testes negativos e regressão.

## Funcionalidades avaliadas

- Dados de entrega
- Método de comunicação
- Data de entrega
- Modalidade de envio
- Salvamento e redirecionamento

## Casos críticos mapeados

O planejamento registra cinco casos prioritários classificados como P1:

| Caso | Validação principal |
|---|---|
| Dados de entrega | Preenchimento e obrigatoriedade |
| Comunicação | Seleção de opções válidas |
| Data de entrega | Formato e regra de data |
| Modalidade de envio | Regra de seleção |
| Salvar | Persistência e redirecionamento |

## Cobertura negativa e de regressão

- Envio do formulário com campos obrigatórios vazios
- Data inválida
- Seleções mutuamente exclusivas
- Valor fora do intervalo permitido
- Texto acima do limite de caracteres
- Fluxo de tela ou redirecionamento incorreto
- Ausência de resposta após salvar

## Exemplo de cenário BDD

```gherkin
Funcionalidade: Cadastro de informações de entrega

Cenário: Impedir o envio sem dados obrigatórios
  Dado que o usuário acessou o formulário de entrega
  E não preencheu os campos obrigatórios
  Quando tenta salvar as informações
  Então o sistema deve impedir o envio
  E informar quais campos precisam ser preenchidos
```

## Evidência apresentada

Este estudo de caso consolida o mapeamento de requisitos, os casos críticos, a cobertura negativa, a abordagem de regressão e um exemplo de modelagem BDD.

## Competências demonstradas

- Análise de regras de negócio
- Priorização por criticidade
- Testes positivos, negativos e de limite
- Planejamento de regressão
- BDD e documentação de defeitos
- Foco em mensagens úteis para o usuário

## Natureza do projeto

Projeto acadêmico desenvolvido durante a formação em Quality Assurance.

[Voltar ao portfólio](./README.md)
