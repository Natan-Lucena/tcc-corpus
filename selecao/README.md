# Seleção das skills

Indicadores extraídos da API do GitHub em 16/11/2026 e aplicados aos critérios de seleção no nível do repositório:

- pelo menos 1.000 estrelas;
- pelo menos 10 contribuidores;
- commit nos 12 meses anteriores à coleta.

Os critérios são eliminatórios e não têm peso. Um repositório só é aprovado se atender aos três.

| Arquivo | Conteúdo |
|---|---|
| `indicadores-repositorios.csv` | Indicadores de cada um dos 16 repositórios do corpus, resultado de cada critério e situação final |
| `skills-candidatas.csv` | Skills de revisão de propósito geral identificadas nos repositórios aprovados, com o tamanho em palavras |

`commit_copiado` é o commit em que os arquivos foram copiados para `github-skills/`. Fica vazio nos repositórios de fornecedores, cujos prompts foram baixados diretamente (ver `INDEX.md`). A seleção no nível da skill ainda está em andamento: 46 arquivos aguardam leitura integral.
