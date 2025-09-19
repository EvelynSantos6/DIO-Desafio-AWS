# 🚀 Desafio AWS Step Functions - DIO  

## 📌 Descrição  
Este repositório contém a documentação do laboratório proposto pela **Digital Innovation One (DIO)**, com foco na consolidação de **workflows automatizados utilizando AWS Step Functions**.  
O objetivo é registrar **anotações, insights e aprendizados** adquiridos durante a prática, servindo como material de apoio para estudos futuros.  

---

Cada etapa corresponde a um **estado** definido na linguagem **Amazon States Language (ASL)**.

---

## 🚀 Benefícios

- **Escalabilidade**: permite processar múltiplas execuções simultaneamente.  
- **Baixo acoplamento**: cada etapa funciona de forma independente.  
- **Monitoramento**: integração com **CloudWatch** para logs e métricas.  
- **Confiabilidade**: suporte nativo a **retry** e tratamento de falhas.

---

## 🔧 Tecnologias Utilizadas

- **AWS S3** – armazenamento de dados  
- **AWS Lambda** – execução serverless  
- **AWS Step Functions** – orquestração de tarefas  
- **Amazon SNS** – envio de notificações  

---

## ▶️ Como Testar o Workflow

1. Criar um bucket no **S3** para receber os dados.  
2. Implementar uma função **Lambda** para processar os dados.  
3. Configurar o **Step Functions** com as etapas do fluxo.  
4. Criar outro bucket ou banco de dados para armazenar os resultados.  
5. Configurar notificação via **SNS** para alertar quando o processamento terminar.

---

## 📌 Próximos Passos

- Implementar **processamento paralelo** para múltiplos arquivos.  
- Integrar com **DynamoDB** para armazenamento estruturado.  
- Adicionar **testes automatizados** para cada etapa do fluxo.  

---

📸 Capturas de tela do laboratório estão na pasta `/images`.
