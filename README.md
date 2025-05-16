# Relatório de Falhas | i-Educar

Este repositório contém o relatório de falhas identificado durante a atividade de testes funcionais (sistema caixa-preta) aplicada no sistema i-Educar.

## Descrição

Durante a execução dos testes, foram encontradas duas inconsistências na validação do campo de carga horária de servidores, relacionadas aos limites aceitos pelo sistema no momento do cadastro e da edição dos registros. Este repositório reúne a documentação das falhas encontradas, com as evidências de tela e o detalhamento do problema.

## Falhas Identificadas

1. Permissão para cadastrar carga horária com o valor `00:00`.
2. Permissão para editar a carga horária de um servidor para valores superiores a `99:59`, permitindo, por exemplo, `100:39`.

O detalhamento completo de cada falha, incluindo os passos para reprodução e o impacto, está disponível [aqui](/relatorio-falhas.md).

## Histórico de versões
| Versão | Data       | Descrição | Autor     |
| ------ | ---------- | --------- | --------- |
| `1.0` | 16/05/2025  | Estruturação Inicial | [Júlia Takaki](https://github.com/juliatakaki) |
