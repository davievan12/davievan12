## Oi, eu sou o Davi

Construo e mantenho sistemas de **IA aplicada** rodando em produção — a maioria pra automatizar o meu próprio negócio de e-commerce (três lojas). Assistentes conversacionais, pipelines de conteúdo com LLM, integrações entre APIs e sistemas, análise de dados. Coisa que está no ar todo dia, não projeto de gaveta.

Foco em **LLMs (Claude, GPT), engenharia de prompt, RAG, integração de APIs e Python**.

### Sobre os repositórios aqui

Quase tudo isso eu desenvolvi e rodei direto numa VPS, versionando em **git local** — nunca tinha usado o GitHub pra esses projetos. Subi agora pra montar um portfólio organizado, então o histórico público é recente, mas o código é o que já está em produção. O `balcao` é a exceção: construí ele agora, como referência de uma arquitetura RAG completa.

### O que tem pra ver

- **[balcao](https://github.com/davievan12/balcao)** — atendente virtual com RAG (FastAPI + Claude). Lê a base de conhecimento da loja, responde citando a fonte e admite quando não sabe. Tem Docker e testes.
- **[sevet-platform](https://github.com/davievan12/sevet-platform)** — monorepo de inteligência de marketing: um assistente que usa *tool calling* pra cruzar dados de Shopify, Meta Ads, Google Ads e GA4, bots e relatórios automáticos.
- **[mordaca-agent](https://github.com/davievan12/mordaca-agent)** — assistente conversacional com o Claude rodando como processo persistente (pra cortar cold-start) e leitura multimodal de criativos.
- **[shopify-blog-v2](https://github.com/davievan12/shopify-blog-v2)** — pipeline que gera artigo de blog com LLM e só publica depois de passar numa bateria de validação automática. Python.
- **[mordaca-poster](https://github.com/davievan12/mordaca-poster)** — o Claude "assiste" frames de um Reel e escreve a legenda; agenda o post via integração própria. Python.
- **[meta-analise](https://github.com/davievan12/meta-analise)** — cron que analisa os criativos de Meta Ads com o Claude e posta no Discord. Python.

### Stack

Python · Node.js · FastAPI · Claude / Anthropic SDK · OpenAI · RAG · Docker · APIs REST · PM2 · SQLite

Contato: sevetcompany@gmail.com
