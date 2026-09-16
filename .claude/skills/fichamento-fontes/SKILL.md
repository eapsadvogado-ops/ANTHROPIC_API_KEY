---
name: fichamento-fontes
description: Use para produzir fichamentos (resenhas de leitura estruturadas) de livros, artigos e capítulos acadêmicos usados como fonte de pesquisa de doutorado. Acione quando o usuário pedir para fichar, resumir criticamente, ou extrair estrutura analítica de um texto acadêmico para uso posterior em revisão bibliográfica ou capítulo teórico.
---

# Fichamento de Fontes Acadêmicas

## Propósito

Produzir fichamentos analíticos (não meros resumos) que permitam reutilização eficiente do material em revisão bibliográfica, capítulos teóricos e argumentação da tese, preservando rastreabilidade de páginas para citação direta.

## Modelo de ficha

1. **Referência completa** (padrão ABNT — ver skill `citacoes-abnt`).
2. **Tipo de fonte**: livro, capítulo, artigo, tese, documento institucional.
3. **Problema/questão que o texto se propõe a responder** (uma frase).
4. **Tese central do autor** (uma ou duas frases, na própria formulação analítica, não cópia literal).
5. **Estrutura argumentativa**: como o autor constrói a demonstração (passos lógicos, capítulos, seções) — útil para replicar ou contrastar estrutura na própria tese.
6. **Conceitos-chave operacionalizados**, com página de definição/primeira ocorrência relevante.
7. **Citações literais de interesse**, com página exata, marcadas para uso potencial como citação direta.
8. **Relação com o projeto de pesquisa do usuário**: em que ponto o texto serve de (a) fundamento teórico, (b) contraponto crítico, (c) fonte de dado empírico, ou (d) referência metodológica.
9. **Limites e críticas ao argumento do autor** (identificadas pelo pesquisador ou por outros autores na literatura).
10. **Palavras-chave de indexação pessoal** (para permitir busca posterior no acervo de fichas).

## Diretrizes de qualidade

- Nunca copie trechos extensos sem marcação clara de citação literal — todo texto fichado que não seja citação direta deve estar em paráfrase autoral, para evitar plágio acidental posteriormente na tese.
- Registre o número de página de toda ideia relevante, mesmo em paráfrase — a ABNT recomenda página também para citação indireta de ideias centrais.
- Ao fichar textos que usam terminologia sensível (raça, racismo, classe), preserve a terminologia exata do autor, sem substituir por sinônimos aparentes que alterem o sentido técnico (ver skill `teoria-racial-critica`).
- Para textos que fazem parte de correntes teóricas concorrentes, registre explicitamente com quais outros autores fichados o texto dialoga, concorda ou diverge — isso alimenta diretamente a etapa de síntese crítica da revisão bibliográfica.

## Formato de saída sugerido

```
FICHA Nº [X]
Referência: [ABNT completo]
Tipo: [livro/artigo/capítulo/tese/documento]

Problema: [...]
Tese central: [...]

Estrutura argumentativa:
[...]

Conceitos-chave:
- [conceito 1] (p. XX): [definição sintética]
- [conceito 2] (p. XX): [definição sintética]

Citações de interesse:
- "[citação literal]" (p. XX)

Relação com o projeto: [fundamento teórico / contraponto / dado empírico / referência metodológica]
Diálogo com outros autores fichados: [...]
Limites/críticas: [...]
Palavras-chave: [...]
```

## Checklist

- [ ] Toda ideia relevante tem página de referência registrada.
- [ ] Citações literais estão claramente distinguidas de paráfrase.
- [ ] A ficha indica explicitamente a função da fonte no projeto de pesquisa.
- [ ] Terminologia técnica do autor foi preservada sem substituição imprecisa.
- [ ] A ficha está pronta para ser diretamente incorporada à revisão bibliográfica (ver skill `revisao-bibliografica-juridica`).
