# 🚀 Desafio AWS Step Functions - DIO  

## 📌 Descrição  
Este repositório contém a documentação do laboratório proposto pela **Digital Innovation One (DIO)**, com foco na consolidação de **workflows automatizados** utilizando **AWS Step Functions**.  

O objetivo é registrar anotações, insights e aprendizados adquiridos durante a prática, servindo como material de apoio para estudos futuros e referência em implementações reais.  

Cada etapa corresponde a um estado definido na **Amazon States Language (ASL)**, a linguagem declarativa utilizada para descrever workflows dentro do serviço.  

---

## 📖 O que são AWS Step Functions?  
O **AWS Step Functions** é um serviço da AWS que permite orquestrar múltiplos serviços em fluxos de trabalho serverless, facilitando a automação de processos.  

Segundo a [documentação oficial da AWS](https://docs.aws.amazon.com/step-functions/latest/dg/welcome.html), ele oferece:  
- **Coordenação de serviços**: conecta AWS Lambda, S3, DynamoDB, ECS, SNS e outros.  
- **Visibilidade e monitoramento**: acompanhamento em tempo real das execuções via console e CloudWatch.  
- **Confiabilidade**: suporte nativo a *retry*, tratamento de exceções e execução paralela.  
- **Escalabilidade**: projetado para lidar com milhares de execuções simultâneas.  

---

## 🎯 Objetivos de Aprendizagem  
Ao concluir este desafio, você será capaz de:  
- Aplicar os conceitos aprendidos em um ambiente prático;  
- Documentar processos técnicos de forma clara e estruturada;  
- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.  

---

## 🔧 Tecnologias Utilizadas  
- **AWS S3** – armazenamento de dados  
- **AWS Lambda** – execução serverless  
- **AWS Step Functions** – orquestração de tarefas  
- **Amazon SNS** – envio de notificações  
- *(Opcional)* **DynamoDB** – armazenamento estruturado de resultados  

---

## ▶️ Como Testar o Workflow  
1. Criar um bucket no **Amazon S3** para receber os dados.  
2. Implementar uma função **Lambda** para processar os dados.  
3. Configurar o **Step Functions** com as etapas do fluxo.  
4. Criar outro bucket ou banco de dados para armazenar os resultados.  
5. Configurar notificação via **SNS** para alertar quando o processamento terminar.  

---

## 🚀 Benefícios do Uso de Step Functions  
- **Escalabilidade**: processa várias execuções em paralelo.  
- **Baixo acoplamento**: cada etapa é independente.  
- **Monitoramento**: integração com CloudWatch.  
- **Resiliência**: tolerância a falhas e mecanismos de retry.  

---

## 📌 Próximos Passos  
- Implementar **processamento paralelo** para múltiplos arquivos.  
- Integrar com **DynamoDB** para armazenamento estruturado.  
- Adicionar **testes automatizados** para cada etapa do fluxo.  

---

## 📸 Evidências do Laboratório  
As capturas de tela estão organizadas na pasta `/images`.  
