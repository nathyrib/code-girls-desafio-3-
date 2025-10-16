# Desafio 3 - Simulação de Stack com AWS CloudFormation

Nesse desafio, foram solicitadas anotações das aulas e a criação de projetos práticos para facilitar a absorção do conteúdo. O objetivo desse repositório é aplicar os conceitos aprendidos sobre AWS CloudFormation, por meio da criação de uma Stack simulada que representa a infraestrutura básica de um ambiente na nuvem.

---

## 🎯 Objetivo

- Aplicar os conceitos aprendidos nas aulas em um cenário prático
- Simular a criação de uma Stack com recursos da AWS
- Documentar o processo como material de apoio para estudos futuros

---

## ✨ Cenário 

Neste projeto, foi criado um template que simula a criação de três recursos principais:

- Um bucket S3 para armazenamento
- Uma instância EC2 para processamento
- Um grupo de segurança para acesso via SSH

---

## 🗂 Arquivo `template.yaml`

O template define os seguintes recursos:

- `AWS::S3::Bucket`
- `AWS::EC2::Instance`
- `AWS::EC2::SecurityGroup`

É possível visualizar o conteúdo completo no arquivo `template.yaml` deste repositório.

---

## 🗒 Anotações

As anotações sobre o desafio, conceitos aprendidos e estrutura do template estão disponíveis no arquivo `anotacoes.md`.

---

## 📁 Diagrama da Stack 


---

## 📝 Aprendizados

- O que é uma Stack e como ela funciona
- Como estruturar templates em YAML
- Função da seção `Resources` e como declarar serviços da AWS
- Como CloudFormation pode automatizar a criação de infraestrutura
