# 🗒 Anotações 

## O que é CloudFormation?
É um serviço da AWS que permite criar e gerenciar recursos de forma automatizada usando templates em YAML ou JSON.

## O que é uma Stack?
É um conjunto de recursos definidos em um template e gerenciados como uma unidade.

## Estrutura de um template YAML
- `AWSTemplateFormatVersion`: versão do formato
- `Description`: descrição da Stack
- `Resources`: onde os recursos são declarados

## Recursos simulados neste projeto
- Bucket S3 (`AWS::S3::Bucket`)
- Instância EC2 (`AWS::EC2::Instance`)
- Grupo de segurança (`AWS::EC2::SecurityGroup`)

## Insights
- CloudFormation facilita a padronização e automação da infraestrutura.
- Criar templates em YAML ajuda a entender a lógica declarativa da AWS.
