# Instagram: hipóteses a testar na Vilela

Cada hipótese parte de uma fonte (oficial ou externa) e de um dado da Vilela quando existe. **Nenhuma está comprovada.** Status possíveis: `aberta`, `em teste`, `apoiada`, `não apoiada`, `inconclusiva`.

Régua de comparação: mediana e taxas da própria conta (ver README). Reels impulsionados (#08, #54, #68) ficam fora.

Ligação com o plano: os experimentos X1–X7 estão em `marketing-and-growth/planejamento/plano-de-acao-4000-seguidores.md` (seção 8). Quando uma hipótese daqui já é testada por um X, o teste é o mesmo; aqui só acrescentamos o que a pesquisa de distribuição muda (métrica, controle ou leitura).

---

## H-IG-01 · O que falta para a Vilela é alcance de não seguidores, não engajamento de seguidores

- **Base:** [OFICIAL] nos Reels, "a maior parte do que você vê é de contas que você não segue" (IG-OF-01). [EVIDÊNCIA VILELA] nos Reels recentes, 50% a 70% das views vieram de quem já segue (leitura do Insights em 31/10/2026, no navegador do Bruno). [EVIDÊNCIA VILELA] 0,89 seguidor por 1.000 views (ago–out/2026).
- **Hipótese:** a conta está sendo distribuída principalmente para a base atual, e o crescimento depende de aumentar a fatia de não seguidores.
- **O que não sabemos:** a % de não seguidores dos Reels mais antigos; se ela é baixa por causa do conteúdo, do tamanho da conta ou de outra coisa.
- **Como medir:** % de visualizações de não seguidores por Reel (Insights do app). Registrar em toda linha de teste.
- **Status:** aberta. É a métrica central dos testes prioritários.

## H-IG-02 · Os 3 primeiros segundos estão custando distribuição

- **Base:** [OFICIAL] tempo de exibição é um dos três sinais principais (IG-OF-02); o Instagram passou a mostrar taxa de pulo e retenção (IG-OF-05). [EXTERNA] mLabs cita o cartão de sistema da Meta: "assistir menos de 3 segundos" seria previsão negativa (não confirmado por nós).
- **Hipótese:** ganchos que mostram logo o imóvel com informação concreta (tipo, bairro, preço) têm taxa de pulo menor que ganchos genéricos.
- **[EVIDÊNCIA VILELA] disponível:** nenhuma. Não temos taxa de pulo nem retenção de nenhum Reel.
- **Como testar:** é o X2 (cotidiano × preço) com duas métricas a mais: taxa de pulo e % de retenção no segundo 3 e no meio do vídeo.
- **Status:** aberta → entra no Teste 1.

## H-IG-03 · Conteúdo que dá vontade de enviar para alguém traz não seguidores

- **Base:** [OFICIAL] envios pesam um pouco mais para quem não segue (IG-OF-02); compartilhar é a primeira previsão listada em 2023 (IG-OF-01). [EVIDÊNCIA VILELA] 4,95 compartilhamentos por 1.000 views na média; o apto da Vila Ema (#52) teve 35 compartilhamentos.
- **Hipótese:** temas que a pessoa manda para outra ("olha esse pra gente", "manda pro seu pai que quer sair do aluguel") geram mais envios por alcance e, por consequência, mais alcance de não seguidores.
- **Cuidado:** [EXTERNA] a mLabs alerta que CTA do tipo "compartilha com um amigo" pode ser tratado como isca de engajamento. Testar o **tema** que dá vontade de enviar, não pedir o envio.
- **Como medir:** envios por 1.000 alcance (o Insights separa "compartilhamentos"; confirmar se inclui DM) e % de não seguidores.
- **Status:** aberta → entra no Teste 2.

## H-IG-04 · Publicar o mesmo vídeo duas vezes desperdiça a segunda publicação (e talvez prejudique a primeira)

- **Base:** [OFICIAL] Reels "já publicados no Instagram" ficam menos visíveis (IG-OF-01, 2023). [EVIDÊNCIA VILELA] em 31 dos 32 pares de cópias, uma publicação teve distribuição normal e a outra ficou perto de zero.
- **O que dá para dizer:** o dado da Vilela é **compatível** com a regra oficial. Não prova a causa, e o motivo de cada duplicação continua pendente (não presumir).
- **Decisão já tomada:** o plano de ação define que cada vídeo é publicado uma vez. Nada a testar; só manter.
- **Status:** apoiada pela fonte oficial; regra operacional em vigor.

## H-IG-05 · Tour mais longo (até 3 min) com preço na abertura pode reter melhor que tour curto para quem procura imóvel

- **Base:** [OFICIAL] Reels de até 3 min são elegíveis para não seguidores (IG-OF-03). [EXTERNA, observação nossa de referência] a conta @victorvesete (Zona Leste, 39,2 mil seguidores, mediana ~15,6 mil views) usa tours de 2 a 3,5 min com preço logo no começo (ficha em `marketing-and-growth/pesquisa/fichas/conta-victorvesete.md`).
- **Hipótese:** para quem está procurando imóvel, um tour completo com preço no início segura mais tempo total de exibição e gera mais contato, mesmo com retenção percentual menor.
- **Cuidado:** a conta de referência é maior, tem outro histórico e posta ~1 por dia; o resultado dela não se transfere automaticamente. E duração muda junto com narrativa e ritmo.
- **Como testar:** Teste 3.
- **Status:** aberta.

## H-IG-06 · Reels de teste podem servir para testar formatos novos sem gastar a base

- **Base:** [OFICIAL] Reels de teste vão primeiro a não seguidores, com métricas em ~24 h (IG-OF-04).
- **Hipótese:** usar Reels de teste para os formatos novos do X5 dá uma leitura mais limpa de "funciona com quem não conhece a Vilela" e evita que um formato fraco ocupe espaço no perfil.
- **Limite:** o Reel de teste não mede o efeito em seguidores (curtidas pesam mais ali); seguidores ganhos podem ser menores porque o vídeo não aparece no perfil.
- **Status:** aberta → entra no Teste 2.

## H-IG-07 · Texto na tela e legenda com bairro e tipo de imóvel ajudam a encontrar o público certo

- **Base:** [EXTERNA] Buffer recomenda palavras-chave na legenda e no perfil para busca e tema. [OFICIAL] o Instagram usa "informações do Reel" para recomendar (IG-OF-01), sem detalhar se lê texto na tela. Mosseri diz que hashtags não ajudam alcance ([EXTERNA], via Buffer/mLabs).
- **[EVIDÊNCIA VILELA]:** no diagnóstico, ganchos de bairro tiveram desempenho fraco. Isso é sobre o **gancho**, não sobre a palavra-chave na legenda.
- **Hipótese:** colocar "casa à venda em Vila Prudente" (tipo + bairro) na legenda ajuda a busca e a recomendação para quem procura imóvel na região, sem precisar abrir o vídeo pelo bairro.
- **Como medir:** difícil isolar. O Insights mostra origem das views (Reels, Explorar, perfil, busca?) — confirmar se a origem "busca" aparece no app. Registrar como observação, não como teste principal.
- **Status:** aberta, prioridade baixa.

## H-IG-08 · Mostrar a pessoa real (Bruno, corretor) no vídeo protege contra a queda de conteúdo genérico/IA

- **Base:** [OFICIAL, via Engadget] Mosseri prevê feeds cheios de conteúdo sintético e valoriza o que é "real" (IG-OF-07). Não há declaração de que o ranqueamento favoreça isso.
- **Hipótese:** vídeos com o corretor em cena, sem acabamento excessivo, mantêm retenção melhor que vídeos só de imagens ou com IA.
- **Cuidado:** o Bruno tem liberdade criativa para usar IA e atores; isto não é regra contra IA. É uma hipótese a observar no X5.
- **Status:** aberta, observar.
