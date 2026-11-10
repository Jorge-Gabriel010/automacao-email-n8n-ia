# 🤖 Automação Inteligente de E-mails com n8n e IA

## 📌 Sobre o projeto

Este projeto consiste no desenvolvimento de um workflow de automação utilizando **n8n**, **Google Gemini AI** e **Gmail**.

A automação utiliza Inteligência Artificial para analisar mensagens de clientes e gerar respostas profissionais, personalizadas e contextualizadas, realizando posteriormente o envio por meio do Gmail.

O projeto foi desenvolvido como uma aplicação prática de automação de processos, integração entre ferramentas e Engenharia de Prompt.

## 🎯 Objetivo

Demonstrar como ferramentas de automação e Inteligência Artificial podem ser integradas para otimizar tarefas de atendimento ao cliente, reduzir atividades manuais e agilizar a comunicação por e-mail.

## ⚙️ Como funciona o workflow

O fluxo é composto pelas seguintes etapas:

1. **Manual Trigger:** inicia o workflow manualmente para execução de testes.
2. **Edit Fields (Set):** define os dados de entrada utilizados na simulação, como nome, e-mail, assunto e mensagem do cliente.
3. **Basic LLM Chain + Google Gemini:** processa as informações utilizando um prompt desenvolvido para gerar uma resposta educada, objetiva e contextualizada.
4. **Gmail (Send Message):** realiza o envio da resposta gerada pela Inteligência Artificial ao destinatário configurado.

## 🛠️ Tecnologias utilizadas

- **[n8n](https://n8n.io/):** plataforma de automação de workflows.
- **[Google Gemini AI](https://deepmind.google/technologies/gemini/):** modelo de Inteligência Artificial utilizado na geração de respostas.
- **[Gmail API](https://developers.google.com/gmail/api):** integração responsável pelo envio automatizado de e-mails.
- **Engenharia de Prompt:** estruturação de instruções para orientar a geração de respostas pela IA.

## 📥 Como importar e executar

1. Clone este repositório ou baixe o arquivo JSON localizado em `workflows/automacao-emails-ia.json`.
2. Acesse sua instância do n8n.
3. Crie um novo workflow.
4. Abra o menu de opções (`...`) e selecione **Import from File**.
5. Selecione o arquivo JSON baixado.
6. Configure as credenciais necessárias para o Google Gemini e o Gmail.
7. Confira os dados de entrada e o destinatário de teste.
8. Execute o workflow utilizando o **Manual Trigger**.

**Importante:** para executar a automação, é necessário configurar corretamente as credenciais dos serviços integrados.

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram trabalhados conceitos de:

- Automação de processos com n8n.
- Integração entre diferentes serviços e APIs.
- Aplicação de Inteligência Artificial em fluxos automatizados.
- Engenharia de Prompt.
- Processamento e estruturação de dados de entrada.
- Automação de comunicação por e-mail.

## 👨‍💻 Autor

**Jorge Gabriel**

Estudante de Ciência de Dados, interessado em Análise de Dados, Business Intelligence, tecnologia e automação.

- [GitHub](https://github.com/Jorge-Gabriel010)
- [LinkedIn](https://www.linkedin.com/in/jorge-gabriel-884a38413/)
- [Portfólio](https://Jorge-Gabriel010.github.io)
