# 📚 Software Architecture & Engineering — Prompt Library

Uma biblioteca de prompts prontos para uso, organizados por categoria, para ajudar arquitetos e engenheiros de software a obter respostas mais precisas e contextualizadas de modelos de linguagem (LLMs) como ChatGPT, Claude, Gemini e outros.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## Como usar

1. Navegue até a categoria desejada na tabela abaixo.
2. Abra o arquivo do prompt correspondente.
3. Copie o conteúdo e cole no seu assistente de IA favorito.
4. **Preencha todas as variáveis entre `[ ]`** com o contexto do seu projeto.
5. Envie e itere com perguntas de aprofundamento.

---

## 🗂️ Índice de Prompts

| # | Categoria | Prompt | Link |
|---|-----------|--------|------|
| 1.1 | 🏗️ Arquitetura | Definição de Arquitetura Inicial | [→ abrir](prompts/01-arquitetura/01-definicao-arquitetura.md) |
| 1.2 | 🏗️ Arquitetura | Comparação de Abordagens | [→ abrir](prompts/01-arquitetura/02-comparacao-abordagens.md) |
| 1.3 | 🏗️ Arquitetura | Revisão de Arquitetura Existente | [→ abrir](prompts/01-arquitetura/03-revisao-arquitetura.md) |
| 2.1 | 🧩 Patterns | Aplicação de Design Patterns | [→ abrir](prompts/02-patterns/01-aplicacao-patterns.md) |
| 2.2 | 🧩 Patterns | Refatoração com SOLID | [→ abrir](prompts/02-patterns/02-refatoracao-solid.md) |
| 3.1 | 🔷 DDD | Event Storming / Mapeamento de Domínio | [→ abrir](prompts/03-ddd/01-event-storming.md) |
| 3.2 | 🔷 DDD | Modelagem de Entidades e Agregados | [→ abrir](prompts/03-ddd/02-modelagem-agregados.md) |
| 4.1 | 🔗 Integração | Design de API REST | [→ abrir](prompts/04-integracao/01-design-api-rest.md) |
| 4.2 | 🔗 Integração | Arquitetura Event-Driven | [→ abrir](prompts/04-integracao/02-event-driven.md) |
| 5.1 | 🚀 DevOps | Pipeline CI/CD | [→ abrir](prompts/05-devops/01-pipeline-cicd.md) |
| 5.2 | 🚀 DevOps | Infraestrutura como Código | [→ abrir](prompts/05-devops/02-iac.md) |
| 6.1 | 🔐 Segurança | Threat Modeling (STRIDE) | [→ abrir](prompts/06-seguranca/01-threat-modeling.md) |
| 7.1 | 📄 Documentação | ADR (Architecture Decision Record) | [→ abrir](prompts/07-documentacao/01-adr.md) |
| 7.2 | 📄 Documentação | Onboarding Técnico | [→ abrir](prompts/07-documentacao/02-onboarding.md) |
| 8.1 | 📊 Performance | Análise de Performance | [→ abrir](prompts/08-performance/01-analise-performance.md) |
| 8.2 | 📊 Performance | Estratégia de Observabilidade | [→ abrir](prompts/08-performance/02-observabilidade.md) |

---

## 💡 Dicas de uso

- **Sempre preencha as variáveis entre `[ ]`** — quanto mais contexto você fornecer, melhor será a resposta do modelo.
- **Combine prompts**: por exemplo, use o `1.1` para definir a arquitetura → `7.1` para documentar a decisão como ADR → `5.1` para montar o pipeline.
- **Itere**: após receber uma resposta, aprofunde com perguntas como *"Detalhe o componente X"* ou *"Quais são os trade-offs se eu usar Y em vez de Z?"*.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para adicionar um novo prompt ou melhorar os existentes:

1. Faça um **fork** deste repositório.
2. Crie uma branch descritiva: `git checkout -b feat/novo-prompt-xyz`.
3. Adicione ou edite o arquivo de prompt na categoria correta (ou crie uma nova pasta seguindo o padrão de nomenclatura).
4. Abra um **Pull Request** com uma breve descrição do prompt e do contexto em que ele é útil.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).
