Agente de IA com ChatGPT para Controle Financeiro (n8n)

Este projeto implementa um Agente de IA para controle de despesas pessoais e empresariais, utilizando n8n + LangChain + LLM (via Groq), com integração a Google Sheets e API de cotação do Bitcoin.

O agente recebe mensagens via chat (Telegram, WhatsApp ou formulário), interpreta automaticamente os gastos informados e registra tudo de forma estruturada em uma planilha.

Funcionalidades

- Recebe mensagens de gastos via chat

- Extrai automaticamente:

Data

Descrição do item

Valor

Moeda

Fornecedor

Tipo de despesa (pessoal ou empresarial)

₿ Converte valores em Bitcoin (BTC → BRL) em tempo real

- Registra os dados automaticamente em Google Sheets

- Mantém memória curta das últimas interações

- Responde com confirmação clara e objetiva
