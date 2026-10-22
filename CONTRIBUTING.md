# Guia de Contribuição e Collaborative Coding — Empire Community

Agradecemos o seu interesse em colaborar com a **Empire Community**! Este documento orienta as boas práticas, fluxos de trabalho e padrões técnicos aplicados em todos os repositórios da organização.

---

## 1. Princípios de Engenharia

1. **Qualidade e Estabilidade Primeiro**: A branch principal (`main`) deve estar sempre funcional e com testes/build verdes.
2. **Mudanças Atômicas e Rastreáveis**: Cada Pull Request deve ter um propósito claro e objetivo único.
3. **Segurança Ativa**: Jamais realize commit de segredos, chaves de API, senhas ou arquivos `.env`. Utilize templates `.env.example`.
4. **Respeito aos Mantenedores e Colaboradores**: Revise o código de forma construtiva e empática.

---

## 2. Estratégia de Branches (GitHub Flow)

- A branch `main` é a branch canônica e protegida.
- Sempre crie sua branch de trabalho a partir da `main` atualizada.
- Convenção de nomenclatura de branches:
  - `feat/nome-da-feature` — Novas funcionalidades
  - `fix/nome-do-bug` — Correções de erros
  - `docs/atualizacao-documentacao` — Documentação e diagramas
  - `refactor/simplificacao-modulo` — Refatorações estruturais sem alteração de comportamento
  - `test/novos-testes-unitarios` — Criação ou expansão de testes
  - `chore/manutencao-dependencias` — Atualizações de dependências e tooling
  - `ci/atualizacao-pipeline` — Pipelines de automação e workflows

---

## 3. Padrão de Commits (Conventional Commits)

Utilizamos o padrão [Conventional Commits v1.0.0](https://www.conventionalcommits.org/pt-br/v1.0.0/). Isso permite a geração automatizada de Changelogs, rastreamento de versões e análise semântica em CI.

### Formato Obrigatório:
```text
<tipo>(<escopo-opcional>): <descrição em minúsculas e no imperativo>

[corpo opcional detalhando as motivações da mudança]

[rodapé opcional: refs #123 / Closes #456]
```

### Exemplos:
- `feat(auth): implementar suporte a login com Discord OAuth2 PKCE`
- `fix(audio): corrigir buffer overflow no relay lavalink`
- `docs(contributing): incluir secao de boas praticas de CI/CD`
- `ci(github): adicionar workflow para semantic pr check`

---

## 4. Ciclo de Vida de um Pull Request (PR)

1. **Abra uma Issue antes (quando aplicável)** para discutir propostas de funcionalidades maiores ou problemas complexos.
2. **Escreva testes** unitários ou de integração que validem o comportamento esperado.
3. **Execute linters e formatadores** locais antes de abrir o PR (ex.: `ruff` para Python, `eslint`/`biome`/`prettier` para JS/TS).
4. **Preencha o modelo de Pull Request**: Explique o que foi alterado, os testes realizados e relacione com as issues resolvidas (`Closes #123`).
5. **Aguarde a aprovação do CI e Revisores**: Todas as conversas abertas na revisão de código devem ser respondidas e marcadas como resolvidas antes do merge.
6. **Estratégia de Merge**: Preferencialmente via *Squash and Merge* ou *Rebase and Merge*, mantendo o histórico da branch `main` linear e compreensível.

---

## 5. Governança com Agentes de IA

Colaborações apoiadas por agentes autônomos ou copilotos de IA são muito bem-vindas na Empire Community, desde que cumpram os mesmos critérios rigorosos de testes, integridade de segurança, aderência aos padrões de código e respeito ao escopo da tarefa solicitada.

---

## 6. Dúvidas e Suporte

Caso precise de esclarecimentos antes de submeter uma contribuição, junte-se ao nosso servidor do Discord:
➡️ **[Discord da Comunidade Empire](https://discord.gg/KgtyNg9U6H)**
