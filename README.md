# CI-DEMO
Este repositório contém um arquivo de configuração simples para GitHub Actions, usado como exemplo de pipeline de integração contínua (CI).

## Arquivo de Workflow
O workflow está definido em um arquivo YAML (.github/workflows/ci-test.yml) 

## name: CI Test  
Define o nome do workflow, que será exibido na aba Actions do GitHub.

## on: [push]  
O workflow é acionado sempre que houver um push para o repositório.

## jobs.test  
Cria um job chamado test que será executado em um ambiente Ubuntu.

## steps  
Lista de etapas que o job executa:

Mensagem 1 → imprime no console: "Iniciando pipeline"

Mensagem 2 → imprime no console: "Pipeline Finalisado"

## Como funciona?
Ao realizar um push para o repositório, o GitHub Actions inicia automaticamente o workflow.

O job test é executado em uma máquina virtual Ubuntu.

As mensagens configuradas são exibidas no log da execução.

✅ Objetivo
Este arquivo serve como teste inicial para validar:

Estrutura básica de um workflow no GitHub Actions.

Execução de comandos simples em etapas sequenciais.
