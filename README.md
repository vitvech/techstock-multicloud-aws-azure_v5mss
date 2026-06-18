# 📌 Entrega Parcial (17/06/2026)

Esta entrega contempla o planejamento da arquitetura AWS do projeto TechStock Multi-Cloud, incluindo a definição da infraestrutura necessária, configuração dos principais serviços e levantamento de custos utilizando o AWS Pricing Calculator.

## Objetivos atendidos nesta etapa

- Definição da arquitetura AWS da aplicação TechStock;
- Planejamento da rede utilizando Amazon VPC;
- Configuração dos Security Groups;
- Provisionamento das instâncias EC2;
- Provisionamento do banco de dados Amazon RDS PostgreSQL;
- Configuração do AWS Secrets Manager;
- Planejamento da integração Multi-Cloud AWS + Azure;
- Definição da arquitetura de monitoramento;
- Levantamento e análise de custos da infraestrutura;
- Estruturação do projeto utilizando Terraform.

## Recursos previstos na arquitetura AWS

### Camada de Aplicação

- EC2 Backend (Node.js)
- EC2 Frontend (S3)
- EC2 Monitoring (Prometheus e Grafana)

### Camada de Dados

- Amazon RDS PostgreSQL

### Camada de Rede

- Amazon VPC
- NAT Gateway
- Application Load Balancer (ALB)
- VPN Site-to-Site AWS ↔ Azure

### Segurança

- Security Groups
- AWS Secrets Manager

---

### Arquitetura AWS

> Inserir imagem da arquitetura aqui

<img width="1535" height="1024" alt="WhatsApp Image 2026-06-16 at 09 01 26" src="https://github.com/user-attachments/assets/5251f075-fcee-4050-84d5-0b769c89ee87" />

### AWS Pricing Calculator

> Inserir imagem da estimativa de custos aqui

# 💰 Levantamento de Custos AWS

O levantamento de custos foi realizado utilizando o AWS Pricing Calculator considerando a arquitetura prevista para a entrega AWS.

## Serviços considerados

| Serviço | Função |
|----------|----------|
| Amazon EC2 | Backend, Frontend e Monitoring |
| Amazon RDS PostgreSQL | Banco de dados |
| AWS Secrets Manager | Gerenciamento de credenciais |
| Application Load Balancer | Balanceamento de tráfego |
| NAT Gateway | Saída segura das sub-redes privadas |
| Site-to-Site VPN | Comunicação entre AWS e Azure |

## Resultado da Estimativa

**Custo mensal estimado:** USD 162,37

A estimativa contempla todos os componentes necessários para suportar a arquitetura proposta no projeto, incluindo serviços de computação, banco de dados, segurança, balanceamento de carga e conectividade híbrida entre provedores de nuvem.

### Relatório de Custos

> Inserir PDF do levantamento de custos realizado na AWS Pricing Calculator.
