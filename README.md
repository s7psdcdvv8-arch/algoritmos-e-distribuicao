# Algoritmos e distribuição: Instagram Reels e TikTok

**Versão:** 1 · **Criado em:** 01/11/2026 · **Mantido para:** Vilela Imóveis (Zona Leste de São Paulo)

## Objetivo

Acompanhar o que se sabe, hoje, sobre como o Instagram Reels e o TikTok distribuem vídeos, e transformar isso em testes para os vídeos da Vilela Imóveis.

Este repositório **não trata "o algoritmo" como uma fórmula única, fixa ou conhecida.** As duas plataformas usam vários sistemas de recomendação, mudam com frequência e nunca divulgaram pesos exatos. O que existe é: o que elas declaram, o que observadores externos relatam, o que nós supomos e o que nós medimos.

O sucesso que importa para a Vilela é **compradores e oportunidades de venda**, não só visualizações. Distribuição é meio, não fim.

## As 4 classificações (obrigatórias)

Toda afirmação importante leva uma etiqueta, a fonte e as datas.

| Etiqueta | O que significa | Pode orientar decisão? |
|---|---|---|
| **[OFICIAL]** | A própria plataforma declarou (central de ajuda, blog oficial, newsroom, executivo falando em nome dela). | Sim, como ponto de partida. Ainda assim, vale só para o que foi dito, não para o que se deduz. |
| **[EXTERNA]** | Análise de especialista, agência, ferramenta ou criador (Buffer, mLabs etc.). | Como pista. Números de ferramenta são correlação na base de clientes dela, não regra. |
| **[HIPÓTESE]** | Explicação possível, ainda não testada na Vilela. | Só para montar teste. |
| **[EVIDÊNCIA VILELA]** | Resultado medido nos nossos próprios conteúdos. | Sim, dentro do tamanho da amostra. |

Regras de uso:

- **Duas datas por fonte:** data de publicação (ou "sem data") e data em que consultamos.
- **Fonte secundária citando fonte oficial** continua sendo marcada como tal: "[OFICIAL, via TechCrunch]". Quando não conseguimos abrir o original, isso fica escrito.
- **Nada de pesos, porcentagens ou "segredos" que a plataforma não confirmou.** Se uma fonte externa der um número, ele aparece com o nome de quem disse.
- **Divergências ficam registradas**, não escondidas.
- **Recomendação antiga não vira novidade.** Ex.: o texto do TikTok sobre o feed Para Você é de 2020; o do Instagram sobre ranqueamento é de 2023. Continuam válidos como base, mas não são "regra de 2026".
- **Instagram e TikTok são analisados separadamente.** O que vale em um não vale automaticamente no outro.

## Estrutura

```
README.md                                   este arquivo
instagram/fontes-oficiais.md                o que o Instagram/Meta declara
instagram/atualizacoes-e-declaracoes.md     linha do tempo de mudanças (mais recente primeiro)
instagram/hipoteses-a-testar.md             hipóteses para a Vilela no Instagram
tiktok/fontes-oficiais.md                   o que o TikTok declara
tiktok/atualizacoes-e-declaracoes.md        linha do tempo de mudanças
tiktok/hipoteses-a-testar.md                hipóteses para a Vilela no TikTok
estudos-de-caso/analises-externas.md        Buffer, mLabs e outras análises, com o que cada uma sustenta
testes-vilela/resultados-e-aprendizados.md  testes da Vilela: plano, resultado, aprendizado
```

## Como usar

1. **Antes de planejar uma semana de vídeos:** leia `*/hipoteses-a-testar.md` e a seção "Testes prioritários" em `testes-vilela/resultados-e-aprendizados.md`.
2. **Quando aparecer uma "novidade do algoritmo":** procure a fonte primária. Registre em `atualizacoes-e-declaracoes.md` com as duas datas e a etiqueta. Se só existir fonte secundária, marque [EXTERNA].
3. **Depois de publicar um vídeo de teste:** registre o resultado em `testes-vilela/resultados-e-aprendizados.md`, comparando com a **mediana e o histórico da própria conta**, nunca com uma conta grande.
4. **Revisão mensal:** reabrir as fontes oficiais, conferir se mudaram, atualizar a data de consulta.

## Como avaliar um resultado da Vilela

- **Régua da conta (Instagram, ago–out/2026):** mediana de 1.278 visualizações por conteúdo único; por 1.000 views: 0,89 seguidor, 4,95 compartilhamentos, 2,08 comentários, 1,60 salvamento. Fonte: `marketing-and-growth/diagnosticos/2026-10-31-reels-ago-out.md` e `planejamento/plano-de-acao-4000-seguidores.md`.
- **Excluir impulsionados das conclusões orgânicas.** Os Reels #08, #54 e #68 foram impulsionados (no #08, 89% das views vieram de anúncio). A exportação do Meta mistura pago e orgânico.
- **Considerar ao mesmo tempo:** formato, tema, gancho, duração, narrativa e métricas disponíveis. Um vídeo muda várias coisas de uma vez; por isso **não atribuímos causa a um único fator** sem teste que isole a variável.
- **Um viral não é regra; um fracasso não condena um formato.** As regras de repetir, declarar vencedor e abandonar estão no plano de ação (seção 8) e valem aqui.
- **Retenção e taxa de pulo só existem no app** (Insights do Reel). Sem esses números, conclusões sobre "tempo de exibição" ficam como hipótese.

## Relação com os outros repositórios

- `marketing-and-growth`: contexto da empresa, diagnóstico, plano de ação e experimentos X1–X7. Os testes daqui **reaproveitam** X1–X7 em vez de criar uma lista paralela.
- `roteiro-e-storytelling` e `v-deo-e-edi-o`: execução (roteiro e edição).

## Pendências gerais

- A Vilela tem conta ativa no TikTok? Com quantos seguidores e vídeos? Sem isso, a parte de TikTok é só pesquisa.
- Exportar retenção, taxa de pulo e % de não seguidores dos Reels recentes (só pelo app).
- Ler diretamente as páginas oficiais que bloquearam leitura automática (ver cada `fontes-oficiais.md`).
