# Hackathon Vivo 2026.1 - Chatbot de Atendimento

## 📋 Descrição do Projeto

Projeto desenvolvido durante a Hackathon da Vivo 2026.1, focused em criar um chatbot inteligente para atendimento ao cliente, especializado em produtos e serviços Vivo.

## 🎯 Objetivo

Desenvolver um assistente virtual capaz de guiar clientes de forma clara, educada e objetiva, ajudando a tirar dúvidas sobre produtos e serviços da Vivo, especialmente:

- Combo Vivo Fibra + Pós
- Benefícios dos pacotes
- App Vivo e funcionalidades
- Faturas e pagamentos
- Suporte técnico básico
- Vivo Travel e uso no exterior

## 🏗️ Arquitetura

O projeto utiliza a plataforma **n8n** para automação e orquestração do fluxo do chatbot, integrando:

- **AI Agent**: Agente inteligente baseado em LangChain
- **OpenAI Chat Model**: Modelo de linguagem para processamento das interações
- **Window Buffer Memory**: Sistema de memória para contexto da conversa
- **Chat Trigger**: Interface de chat via webhook

## 📁 Estrutura do Projeto

```
├── README.md                     # Documentação do projeto
├── Prompt-hackathon.txt          # Prompt detalhado com regras de atendimento
├── Chat bot atendimento Vivo.json # Fluxo do n8n com configuração do chatbot
├── Apresentação-hackathon2026-vivo 1.pptx # Apresentação do projeto
└── WhatsApp Image 2026-03-26 at 18.10.24.jpeg # Imagem de referência
```

## 🤖 Funcionalidades do Chatbot

### Atendimento Especializado
- **Combo Fibra + Pós**: Explicações sobre benefícios e funcionamento
- **Suporte Técnico**: Orientações para problemas básicos de conexão
- **Financeiro**: Ajuda com faturas, segunda via e negociação
- **Vivo Travel**: Informações sobre uso internacional
- **Encaminhamento**: Direcionamento para canais oficiais quando necessário

### Princípios de Atendimento
1. Linguagem simples e clara
2. Tom cordial e humano
3. Respostas objetivas e práticas
4. Sempre orientando para a solução
5. Transparência quando houver limitações

## 🚀 Como Funciona

1. **Trigger**: Cliente envia mensagem via chat
2. **Processamento**: AI Agent analisa a solicitação usando o prompt personalizado
3. **Resposta**: Gera resposta contextualizada seguindo as diretrizes da Vivo
4. **Memória**: Mantém contexto da conversa para interações contínuas

## 📊 Canais de Atendimento Suportados

O chatbot direciona clientes para os canais oficiais da Vivo:
- App Vivo
- WhatsApp Vivo: (11) 99915-1515
- Central de Relacionamento: 10315 (fixos) / 8486 (móvel)
- Pessoa com deficiência: 142
- Ouvidoria (quando necessário)

## 🔧 Tecnologias Utilizadas

- **n8n**: Plataforma de automação e workflow
- **LangChain**: Framework para aplicações de linguagem
- **OpenAI**: Modelo de linguagem GPT
- **Webhooks**: Integração via HTTP

## 📈 Benefícios

- ⚡ **Respostas rápidas** 24/7
- 🎯 **Atendimento especializado** nos produtos Vivo
- 💬 **Interface amigável** e intuitiva
- 🔄 **Escalabilidade** para alto volume
- 📱 **Integração** com canais existentes

## 👥 Equipe

Projeto desenvolvido durante a Hackathon Vivo 2026.1 como parte da competição de inovação.

## 📝 Considerações

O chatbot foi projetado para complementar o atendimento humano, não substituí-lo completamente. Ele serve como primeiro nível de suporte, resolvendo dúvidas comuns e direcionando casos complexos para os canais especializados.