# Teste de Estresse - PAA (Plano de Ação Anual)

Este repositório contém os testes de performance realizados com o Apache JMeter no ambiente de teste (SIT) da aplicação PAA.

## Ambiente testado

[http://paa.sit.internal-quattrus.com/](http://map.sit.internal-quattrus.com/editor)

## Estrutura do repositório

- `Scripts/` → Contém os arquivos `.jmx` utilizados para simulação de carga e estresse.
- `Imagens/` → Prints dos testes, configurações e evidências visuais.
- `README.md` → Este arquivo de documentação.

## Objetivo dos testes

Avaliar a performance e estabilidade da aplicação Stratega sob diferentes cargas de usuários simultâneos, simulando:

- Carga moderada (ex: 50 usuários)
- Estresse elevado (ex: 200 usuários)
- Carga contínua por 30 minutos

## Ferramentas utilizadas

- [Apache JMeter](https://jmeter.apache.org/) v5.6.3
- BlazeMeter v 6.6.7
- Navegador Google Chrome
- Windows 10

## Autor

Gabriella Braz — Analista de QA Jr  
📧 E-mail: gabriella.braz@quattrus.com
