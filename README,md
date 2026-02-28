# 💰 Agente Financeiro Conversacional - MVP

Projeto de um assistente inteligente para gestão de finanças pessoais via chat, eliminando planilhas complexas e formulários manuais.

## 🚀 Visão Geral

Este projeto utiliza Inteligência Artificial para permitir que usuários controlem seus gastos através de linguagem natural (texto ou voz), focando em praticidade e educação financeira.

---

## 🧠 Engenharia de Prompts (Core)

Para o funcionamento do assistente, utilize os prompts abaixo nos motores de IA (Gemini, GPT-4 ou Botpress):

### 1. Estratégia de Produto (PM Prompt)

Este prompt deve ser usado para gerar o roadmap e a lógica de negócios inicial.

> **Prompt:** "Atue como um Especialista em Produto (PM). Com base no problema de que apps de finanças são complexos, detalhe um plano de MVP para um Agente Financeiro Conversacional. O plano deve incluir: User Flow, Arquitetura No-code sugerida e Tom de Voz (acolhedor)."

### 2. Processamento de Linguagem Natural (NLP Prompt)

Configure este prompt na API que processará as mensagens do usuário.

> **Prompt:** "Você é o cérebro de um app de finanças. Identifique: Valor, Categoria e Descrição.
> - Categorias: \[Alimentação, Transporte, Lazer, Fixo, Outros].
> - Exemplo: 'Gastei 40 com sushi' -> `{"valor": 40.00, "cat": "Alimentação", "desc": "sushi"}`.
> - Se faltar o valor, peça-o gentilmente. Sempre dê uma micro-dica de economia após registrar um gasto de 'Lazer'."

### 3. Interface e Experiência (UI/UX Prompt)

Use este prompt em ferramentas como \[v0.dev](https://v0.dev) ou \[DALL-E 3](https://openai.com) para prototipar as telas.

> **Prompt:** "Crie o design de uma interface de chat mobile para finanças. Estilo Glassmorphism, tons de azul e verde. Destaque bolhas de chat limpas e cards visuais para metas financeiras (estilo termômetro), sem tabelas complexas."

---

## 🛠️ Stack Recomendada (Custo Zero)

*   **Interface:** \[Telegram Bot](https://t.me) (Gratuito)
*   **Orquestração:** \[Botpress](https://botpress.com) ou \[n8n](https://n8n.io)
*   **IA/Cérebro:** \[Gemini API](https://ai.google.dev) (Plano Free)
*   **Banco de Dados:** \[Supabase](https://supabase.com)

---

## 📈 Funcionalidades do MVP

1.  **Registro Natural:** "Paguei 20 reais no café agora".
2.  **Auto-Categorização:** Classificação via IA sem intervenção humana.
3.  **Metas Flexíveis:** "Quero economizar 500 reais para viajar".
4.  **Agente Consultor:** Insights baseados na regra 50/30/20.
