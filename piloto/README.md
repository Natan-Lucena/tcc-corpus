# Piloto do rastreamento das instruções

O piloto aplicou a regra de enquadramento à skill `code-review-and-quality`, do repositório addyosmani/agent-skills (commit 9d0c60d406). O arquivo analisado está em `github-skills/agent-skills/skills/code-review-and-quality/SKILL.md`.

`matriz-code-review-and-quality.tsv` traz uma linha para cada enquadramento, com estas colunas:

- `linhas`: as linhas do SKILL.md;
- `trecho`: o texto da instrução;
- `tipo`:
  - `defeito`: categoria de defeito;
  - `pratica`: prática de comentário;
  - `incidental`: menção não enquadrada;
  - `sem_respaldo`: instrução sem correspondência na literatura reunida;
- `classe`, `categoria_ou_pratica` e `aspecto`.

Uma instrução que trata de dois aspectos aparece em duas linhas com o mesmo `id`.

## Resultado

| Conjunto | Presentes | Total | % |
|---|---|---|---|
| Defeitos funcionais | 5 | 7 | 71,4 |
| Defeitos de evolutibilidade | 2 | 3 | 66,7 |
| Categorias complementares | 3 | 3 | 100,0 |
| **Cobertura de defeitos** | **10** | **13** | **76,9** |
| **Práticas de comentário** | **6** | **10** | **60,0** |

- **Categorias ausentes:** recurso, interface e representação visual. A formatação aparece apenas como exemplo do rótulo *Nit*, e por isso é tratada como menção incidental.
- **Práticas ausentes:**
  - P2, explicar o motivo;
  - P4, evitar perguntas e elogios;
  - P6, citar a boa prática;
  - P9, restringir-se à alteração.

As categorias de defeito e as práticas de comentário seguem o Capítulo de Resultados Preliminares do TCC. O piloto será refeito com as categorias conferidas nos textos originais.
