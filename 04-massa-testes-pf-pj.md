# Projeto 4 — Massa de testes para cadastro PF e PJ

## Visão geral

Estudo acadêmico voltado à preparação de massa e à documentação da execução de cadastros de Pessoa Física e Pessoa Jurídica.

## Objetivo

Garantir que os dois tipos de usuário possam concluir o cadastro com os campos, formatos e resultados esperados para cada perfil.

## Estrutura do teste

| Elemento | Conteúdo |
|---|---|
| Pré-condição | Usuário na tela de cadastro |
| Massa | Dados artificiais adequados ao tipo de pessoa |
| Ação | Preenchimento e confirmação |
| Resultado esperado | Conta criada e confirmação apresentada |
| Pós-condição | Redirecionamento para a área correspondente |

## Cobertura

### Pessoa Física

- Nome
- Documento em formato válido
- Dados de contato
- Endereço
- Credenciais

### Pessoa Jurídica

- Razão social e nome empresarial
- Documento empresarial em formato válido
- Responsável e dados de contato
- Endereço
- Credenciais

## Cuidados adotados

- Separação da massa por tipo de cadastro
- Uso de dados artificiais na apresentação pública
- Registro do resultado esperado
- Verificação da confirmação e do redirecionamento
- Documentação rastreável entre massa, ação e resultado

## Evidências do repositório

- [Casos de teste manuais](./03-manual-tests/)
- [Massa de testes](./05-test-data/)

## Competências demonstradas

- Preparação de massa de testes
- Validação de formatos e obrigatoriedade
- Organização de pré-condições e pós-condições
- Rastreabilidade da execução
- Atenção à privacidade dos dados

## Natureza do projeto

Projeto acadêmico desenvolvido durante a formação em Quality Assurance.

[Voltar ao portfólio](./README.md)

