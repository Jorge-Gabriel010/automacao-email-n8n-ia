# 🤖 Automação Inteligente de E-mails com n8n e IA

Este projeto consiste num fluxo de automação desenvolvido no **n8n** que recebe mensagens de clientes, processa o conteúdo utilizando **Inteligência Artificial (Google Gemini)** e gera respostas profissionais personalizadas, enviando-as automaticamente via **Gmail**.

---

## 🚀 Fluxo de Trabalho (Workflow)

O fluxo é composto pelas seguintes etapas:

1. **Manual Trigger**: Nó de disparo para testes manuais do fluxo.
2. **Edit Fields (Set)**: Definição e estruturação dos dados de teste (Nome, E-mail, Assunto e Mensagem do cliente).
3. **Basic LLM Chain + Google Gemini**: Processamento dos dados de entrada através de engenharia de prompt para gerar uma resposta educada, objetiva e contextualizada.
4. **Gmail (Send Message)**: Envio automático da e-mail de resposta para o destinatário.

---

## 🛠️ Tecnologias Utilizadas

- **[n8n](https://n8n.io/)**: Plataforma de automação de workflows.
- **[Google Gemini AI](https://deepmind.google/technologies/gemini/)**: Modelo de linguagem de grande porte (LLM) para geração de texto.
- **[Gmail API](https://developers.google.com/gmail/api)**: Integração para envio automatizado de e-mails.

---

## 📋 Como Importar e Usar no Seu n8n

1. Faça o clone deste repositório ou descarregue o ficheiro na pasta `workflows/automacao-emails-ia.json`.
2. No seu painel do n8n, crie um novo workflow.
3. Clique no menu superior direito (`...`) e selecione **Import from File**.
4. Selecione o ficheiro `.json` descarregado.
5. Configure as credenciais de acesso para os nós do **Google Gemini** e do **Gmail**.
6. Execute o fluxo!