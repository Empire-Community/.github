# Guia de Comunicação e Discussões — Empire Community

Para manter o fluxo de desenvolvimento ágil, produtivo e organizado, a **Empire Community** adota três canais complementares com finalidades bem definidas:

---

## 🧭 Onde Falar o Quê?

```
                      ┌───────────────────────────────────────────────┐
                      │          Qual é a sua necessidade?            │
                      └──────────────────────┬────────────────────────┘
                                             │
            ┌────────────────────────────────┼────────────────────────────────┐
            ▼                                ▼                                ▼
  [ Conversa Rápida ]             [ Ideias / Q&A Assíncrono ]        [ Trabalho Acionável ]
  - Dúvida momentânea             - Brainstorming de mecânicas       - Relato de bug reproduzível
  - Bate-papo da comunidade       - Dúvida técnica aprofundada       - Tarefa de desenvolvimento
  - Suporte ao vivo com o bot     - Vitrine de criações (Show & Tell)- Proposta formal de RFC
  - Feedback em call de voz       - Discussão de arquitetura         - Mudança de código
            │                                │                                │
            ▼                                ▼                                ▼
     💬 DISCORD                   💡 GITHUB DISCUSSIONS               📌 GITHUB ISSUES
```

---

## 1. 💬 Discord (Tempo Real & Comunidade Viva)
* **Link:** [discord.gg/KgtyNg9U6H](https://discord.gg/KgtyNg9U6H)
* **Finalidade:** Comunicação síncrona, atendimento rápido a usuários, anúncios de eventos, calls e suporte em tempo real para comandos do EmpireMuse ou servidores de jogos.
* **Quando usar:**
  - Conversar com outros membros da comunidade.
  - Tirar dúvidas rápidas de configuração que não exigem documentação perene.
  - Notificar sobre instabilidade temporária.

---

## 2. 💡 GitHub Discussions (Fórum Aberto & Q&A Indexável)
* **Link:** [github.com/orgs/Empire-Community/discussions](https://github.com/orgs/Empire-Community/discussions)
* **Finalidade:** Comunicação assíncrona, debates estruturados e base de conhecimento permanente indexada por motores de busca.
* **Categorias Oficiais:**
  - **💡 Ideas**: Propostas conceituais para novos bots, mecânicas de jogos no EmpireHub, novas features para o site.
  - **❓ Q&A**: Dúvidas técnicas sobre como usar APIs, SDKs da Engine ou configuração de ambiente. Respostas podem ser marcadas como "Solução".
  - **🎉 Show and Tell**: Apresentação de jogos criados com o SDK, servidores usando EmpireMuse, customizações e integrações.
  - **📋 RFCs**: Debates abertos sobre evolução de arquitetura antes de virarem tarefas fechadas.
  - **📢 Announcements**: Atualizações de versão e novidades oficiais divulgadas pelos mantenedores.

---

## 3. 📌 GitHub Issues (Engenharia & Backlog de Tarefas)
* **Finalidade:** Rastreamento formal de trabalho técnico acionável. Uma Issue deve representar algo que precisa ser corrigido, escrito ou implementado via Pull Request.
* **Tipos Padronizados:**
  - `🐛 Bug Report`: Falhas, exceções no terminal (`ERR-XXXXXX`), erros de execução com passos de reprodução.
  - `💡 Feature Request`: Funcionalidade já debatida e aprovada que precisa ser implementada.
  - `📝 Documentation`: Atualizações em documentações, guias ou referências de código.
  - `📐 RFC Issue`: Issue para acompanhar o ciclo de desenvolvimento de uma especificação técnica aprovada.

---

## ⚖️ Boas Práticas nas Discussões
1. **Respeito mútuo:** Todas as interações estão sujeitas ao nosso [Código de Conduta](CODE_OF_CONDUCT.md).
2. **Evite duplicatas:** Use a barra de pesquisa antes de abrir uma nova discussão ou issue.
3. **Marque soluções:** Em tópicos da categoria Q&A, o autor da pergunta ou mantenedores devem sempre marcar a melhor resposta como solução aceita para ajudar futuros desenvolvedores.
