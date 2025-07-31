# Teste de Estresse - PAA (Plano de Ação Anual)

Este repositório contém os testes de performance realizados com o Apache JMeter no ambiente de teste (SIT) da aplicação PAA.

## Ambiente testado

[http://paa.sit.internal-quattrus.com/](http://map.sit.internal-quattrus.com/editor)

## Estrutura do repositório

- `Scripts/` → Contém os arquivos `.jmx` utilizados para simulação de carga e estresse.
- `README.md` → Este arquivo de documentação.

## Objetivo dos testes

Avaliar a performance e estabilidade da aplicação Stratega sob diferentes cargas de usuários simultâneos, simulando:

## Teste 01

| Cenário                          |         |
| -------------------------------- | --------------------------------------------- |
| Teste leve com 1 usuário         | `Teste Navegação Simples - Usuário Único`     |
| Teste de carga moderada (ex: 30) | `Carga Moderada - 30 Usuários`                |
| Teste de estresse                | `Estresse - 200 Usuários Simultâneos`         |
| Teste contínuo                   | `Teste de Longa Duração - Navegação Contínua` |

## Teste 02

| Cenário                          |         |
| -------------------------------- | --------------------------------------------- |
| Teste de carga                   | `Carga Moderada - 50 Usuários`                |
| Teste de estresse                | `Estresse - 100 Usuários Simultâneos`         |

## Ferramentas utilizadas

- [Apache JMeter](https://jmeter.apache.org/) v5.6.3
- BlazeMeter v 6.6.7
- Navegador Google Chrome
- Windows 10

## Autor

Gabriella Braz — Analista de QA Jr  
📧 E-mail: gabriella.braz@quattrus.com
