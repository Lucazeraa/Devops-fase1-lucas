# Projeto DevOps Fase 1 - PUCRS

## Descrição do Projeto
Este projeto tem como objetivo demonstrar na prática conceitos de DevOps, como Integração Contínua (CI) e Infraestrutura como Código (IaC). A aplicação exemplo é uma API Node.js simples.

## Objetivos
- Automatizar o processo de build e testes com GitHub Actions.
- Criar scripts de infraestrutura com Terraform.
- Documentar todo o processo de configuração e automação inicial.

## Requisitos
- Node.js (v18+)
- AWS CLI configurado
- Terraform instalado

## Plano de Integração Contínua
Utilizamos o GitHub Actions para executar o pipeline de CI sempre que há push ou pull request na branch `main`.

As etapas do pipeline são:
1. Clonar o repositório
2. Instalar dependências
3. Rodar testes

## Infraestrutura Necessária
A infraestrutura é composta por:
- 1 instância EC2 (Ubuntu) para rodar a aplicação
- Provisionamento via Terraform
