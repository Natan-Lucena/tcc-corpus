# Índice do corpus de critérios de code review

Data da coleta: 2026-10-02

## Etapa 1 — Skills do GitHub

| Repositório | URL | Arquivos salvos | Commit | Status |
|---|---|---|---|---|
| code-review-skill | https://github.com/awesome-skills/code-review-skill | 2 arquivos em `github-skills/code-review-skill/` (lista: `find` na pasta) | 4850184dfd | ok |
| agents | https://github.com/wshobson/agents | 747 arquivos em `github-skills/agents/` (lista: `find` na pasta) | 156b7a5e7a | ok |
| superpowers | https://github.com/obra/superpowers | 63 arquivos em `github-skills/superpowers/` (lista: `find` na pasta) | 8ca22dba9a | ok |
| agent-skills | https://github.com/addyosmani/agent-skills | 69 arquivos em `github-skills/agent-skills/` (lista: `find` na pasta) | 9d0c60d406 | ok |
| skills | https://github.com/getsentry/skills | 130 arquivos em `github-skills/skills/` (lista: `find` na pasta) | d18b7aa8ba | ok |
| awesome-reviewers | https://github.com/baz-scm/awesome-reviewers | 5427 arquivos em `github-skills/awesome-reviewers/` (lista: `find` na pasta) | 3cec9615fe | ok |
| code-review-agent | https://github.com/SomeStay07/code-review-agent | 2 arquivos em `github-skills/code-review-agent/` (lista: `find` na pasta) | 03d187558f | ok |
| claude-review-agents | https://github.com/eranw2000/claude-review-agents | 5 arquivos em `github-skills/claude-review-agents/` (lista: `find` na pasta) | d0948bf27f | ok |
| agent-reviewer-skills | https://github.com/kvsankar/agent-reviewer-skills | 81 arquivos em `github-skills/agent-reviewer-skills/` (lista: `find` na pasta) | 6dc11e6bd3 | ok |
| ai-skills | https://github.com/iliaal/ai-skills | 272 arquivos em `github-skills/ai-skills/` (lista: `find` na pasta) | 7b0520aa5d | ok |
| ai-code-review-prompts | https://github.com/soul-sol/ai-code-review-prompts | 6 arquivos em `github-skills/ai-code-review-prompts/` (lista: `find` na pasta) | ff21994c62 | ok |
| brooks-lint | https://github.com/hyhmrright/brooks-lint | 36 arquivos em `github-skills/brooks-lint/` (lista: `find` na pasta) | 7b0e527098 | ok |

Observações: arquivos copiados sem alteração; a procedência de cada repositório está em `github-skills/<repo>/.source.txt`. Em awesome-reviewers foram copiados os 5424 .md de `_reviewers/` (os .json foram ignorados).

## Etapa 2 — Fornecedores

| Fornecedor | Tipo | URL de origem | Arquivo salvo |
|---|---|---|---|
| Anthropic /code-review | prompt baixado | https://raw.githubusercontent.com/anthropics/claude-code/main/plugins/code-review/commands/code-review.md | fornecedores/anthropic__code-review.md |
| Anthropic /security-review | prompt baixado | https://raw.githubusercontent.com/anthropics/claude-code-security-review/main/.claude/commands/security-review.md | fornecedores/anthropic__security-review.md |
| OpenAI Codex | prompt baixado | https://raw.githubusercontent.com/openai/codex/main/codex-rs/core/gpt_5_codex_prompt.md | fornecedores/openai__gpt_5_codex_prompt.md |
| Qodo PR-Agent | prompt baixado | https://raw.githubusercontent.com/qodo-ai/pr-agent/main/pr_agent/settings/pr_reviewer_prompts.toml | fornecedores/qodo__pr_reviewer_prompts.toml |
| GitHub Copilot | só documentação | https://docs.github.com/en/copilot/tutorials/customize-code-review | — |
| Cursor Bugbot | só documentação | https://cursor.com/docs/bugbot | — |
| CodeRabbit | só documentação | https://docs.coderabbit.ai/guides/review-instructions | — |
| Qodo (produto atual) | só documentação | https://docs.qodo.ai/code-review | — |
| Greptile | só documentação | https://www.greptile.com/docs/code-review/controlling-nitpickiness | — |
| Graphite | só documentação | https://graphite.com/docs/ai-review-customization | — |
| Sourcery | só documentação | https://docs.sourcery.ai/Code-Review/Overview/ | — |
| Amazon Q | só documentação | https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/code-reviews.html | — |
| Google Gemini Code Assist | só documentação | https://docs.cloud.google.com/gemini/docs/code-review/style-guide | — |
| Windsurf/Devin | só documentação | https://docs.devin.ai/desktop/windsurf-reviews/windsurf-reviews | — |
| Kimi/Moonshot | só documentação | https://www.kimi.com/code/docs/en/kimi-code-cli/reference/slash-commands.html | — |

## Falhas e não encontrados

Nenhuma: os 12 clones e os 4 downloads foram concluídos com sucesso.

## Descartados

Data: 2026-10-02. Arquivos sem relação com revisão de código foram movidos (não apagados) para `_descartados/<repo>/<subpath>/`, preservando o caminho relativo; para reverter, mova de volta para `github-skills/`. `awesome-reviewers/` e os `.source.txt` não foram tocados. Classificação por arquivo (MANTER/DESCARTAR/DÚVIDA, motivo e grupo de duplicata idêntica): `_classificacao_proposta.tsv`.

| Repositório | Movidos para _descartados/ | Restantes em github-skills/ |
|---|---|---|
| agent-reviewer-skills | 10 | 71 |
| agent-skills | 45 | 24 |
| agents | 690 | 57 |
| ai-skills | 224 | 48 |
| brooks-lint | 12 | 24 |
| claude-review-agents | 1 | 4 |
| code-review-agent | 1 | 1 |
| code-review-skill | 1 | 1 |
| skills | 75 | 55 |
| superpowers | 56 | 7 |
| awesome-reviewers | 0 | 5427 |

Total movido: 1115. Restantes fora de awesome-reviewers: 298 (252 MANTER + 46 DÚVIDA). Duplicatas idênticas (hash) estão marcadas na coluna `dup-group` (15 grupos, 30 arquivos); versões quase idênticas de `code-reviewer.md` e `security-auditor.md` não foram agrupadas.
