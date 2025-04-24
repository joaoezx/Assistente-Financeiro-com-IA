# 💰 Assistente Financeiro com IA

Um aplicativo pessoal para te ajudar a organizar suas tarefas e decisões financeiras, usando **NestJS**, **Angular** e **serviços da AWS** como DynamoDB, Lambda, S3, SQS e IA via Amazon Bedrock e Comprehend.

---

## Funcionalidades

- Criar e gerenciar tarefas financeiras
- Análise de descrição via IA (classificação/sugestões)
- Notificações de vencimento por e-mail (via SNS)
- Exportar relatórios em JSON ou CSV (armazenados no S3)
- Processamento assíncrono com AWS SQS
- Deploy com Serverless Framework (usando o Free Tier)

---

## Tecnologias

### Back-end (NestJS + AWS)
- Node.js + TypeScript
- NestJS (REST API)
- DynamoDB
- Lambda, S3, SNS, SQS, CloudWatch
- Jest (testes unitários)

### Front-end (Angular)
- Angular 17+
- Bootstrap
- HttpClient para consumo da API

---

## Estrutura do Projeto

```bash
/
├── backend/       # API NestJS
│   └── src/
├── frontend/      # Aplicação Angular
│   └── src/
├── serverless/    # Infraestrutura AWS (serverless.yml etc)
├── README.md
└── .gitignore
