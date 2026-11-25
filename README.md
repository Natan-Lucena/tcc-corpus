# tcc-corpus

Corpus de prompts, skills e critérios de *code review* assistido por LLM, coletado em 2026-10-02 como material de pesquisa do TCC (UFC Quixadá) que acompanha o projeto **Bella Reviewer**.

## Estrutura

| Caminho | Conteúdo |
|---|---|
| `INDEX.md` | Índice da coleta: fontes, URLs, commits, contagens e log de descartes |
| `_classificacao_proposta.tsv` | Classificação proposta por arquivo (KEEP / DISCARD / UNSURE) |
| `github-skills/<repo>/` | Arquivos copiados sem alteração de 12 repositórios públicos do GitHub; procedência em `.source.txt` |
| `fornecedores/` | Prompts públicos de fornecedores (Anthropic, OpenAI Codex, Qodo PR-Agent); procedência em `*.source.txt` |
| `_descartados/` | Arquivos julgados fora do escopo de code review, movidos (não apagados) para manter a rastreabilidade |
| `selecao/` | Indicadores de seleção dos repositórios (coletados em 2026-11-16), aplicação dos critérios e skills candidatas |
| `piloto/` | Matriz de enquadramento do piloto (skill `code-review-and-quality`): cada instrução ligada à categoria de defeito ou prática de comentário |

## Procedência e licenças

Todo o conteúdo de `github-skills/`, `fornecedores/` e `_descartados/` pertence aos respectivos autores e foi copiado sem alteração, apenas para fins acadêmicos de análise. A URL de origem e o commit de cada fonte estão em `INDEX.md` e nos arquivos `.source.txt`. Consulte o repositório original de cada fonte para os termos de licença aplicáveis.

Alguns arquivos contêm exemplos de chaves e cabeçalhos de chave privada (por exemplo, a chave de exemplo oficial `...EXAMPLE` da AWS). São ilustrações presentes nos textos originais, não credenciais reais.
