# Projeto 1 — Login multiperfil e compatibilidade

## Visão geral

Estudo acadêmico de planejamento e modelagem de testes para um fluxo de autenticação utilizado por dois perfis: alunos e funcionários.

O objetivo foi verificar validações, autenticação e redirecionamento, considerando diferenças de perfil, navegador e dispositivo.

## Escopo

- Login de aluno
- Login de funcionário
- Validação de campos de texto
- Credenciais válidas e inválidas
- Mensagens apresentadas ao usuário
- Redirecionamento após autenticação
- Compatibilidade entre navegadores e dispositivos

## Cobertura planejada

O material acadêmico contém 12 registros de teste, classificados entre prioridades P1 e P2.

| Dimensão | Cobertura |
|---|---|
| Perfis | Aluno e funcionário |
| Navegadores | Google Chrome, Mozilla Firefox e Internet Explorer |
| Dispositivos | Android e iOS |
| Tipo principal | Funcional positivo |
| Modelagem | BDD |
| Automação | Cenários identificados como candidatos |

## Exemplo de cenário BDD

```gherkin
Funcionalidade: Autenticação de usuário

Cenário: Login válido de aluno
  Dado que o aluno está na página de autenticação
  E possui credenciais válidas
  Quando informa os dados obrigatórios
  E confirma o acesso
  Então o sistema deve autenticar o usuário
  E direcioná-lo para a área correspondente ao perfil de aluno
```

## Riscos observados

- Usuário autenticado no perfil incorreto
- Mensagem de validação pouco clara
- Comportamento diferente entre navegadores
- Falha de redirecionamento após o login
- Campos aceitando formatos não previstos

## Competências demonstradas

- Separação de cenários por persona
- Priorização orientada a risco
- Escrita de cenários BDD
- Planejamento de compatibilidade
- Identificação de candidatos à automação
- Visão integrada entre suporte, usuário e qualidade

## Natureza do projeto

Projeto acadêmico desenvolvido durante a formação em Quality Assurance.

[Voltar ao portfólio](./README.md)

