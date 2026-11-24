# Conectores do Claude

Registro das ferramentas que o Claude usa nos meus estudos, artigos, pós-graduação e odontologia, e no site de planejamento (repositório `planejamento-site`).

## Neste repositório (plugin próprio)

| Plugin | O que faz |
|---|---|
| `dental-ai-skills` | Sete skills de evidência odontológica: busca de literatura, avaliação crítica de artigo, revisão de evidência com GRADE, auditoria estatística, busca de PDF de acesso livre, registro de vínculos de autores e relatório em HTML. |

Origem: cópia de [Tuminha/dental-ai-skills](https://github.com/Tuminha/dental-ai-skills), licença MIT (arquivo `plugins/dental-ai-skills/LICENSE`). Ficaram de fora o gerador de imagens (exige chave paga da OpenAI) e o criador de conteúdo para redes sociais. A saída dessas skills sempre precisa de revisão clínica.

### Como adicionar no Claude

No app desktop: clique no **+** ao lado da caixa de prompt, depois em **Plugins**, **Add marketplace**, e use `leonardocdell-hash/conectores-cladue`. Em seguida, **Add plugin** e escolha `dental-ai-skills`.

No terminal do Claude Code:

```
/plugin install dental-ai-skills --marketplace leonardocdell-hash/conectores-cladue
```

## Registrados aqui, mas instalados pelo diretório do Claude

Estes não estão neste repositório. São instalados pelo diretório de plugins e conectores do Claude.

| Item | Tipo | Para que serve |
|---|---|---|
| Research Desk | plugin do diretório | Conferir referências, notas de leitura, comparar artigos, revisar rascunho como parecerista |
| research-superpowers | plugin do diretório | Fluxo de pesquisa completo, da ideia à revisão por pares |
| Academic PDF Translation | plugin do diretório | Traduzir PDFs acadêmicos preservando a estrutura |
| SciSpace | conector (sem login) | Busca em 280 milhões de artigos e tabelas de evidências |

## Observações

- Os plugins de comunidade não foram avaliados clinicamente. Revisão e decisão clínica continuam sendo minhas.
- No `planejamento-site`, usar só casos fictícios ou anonimizados.
