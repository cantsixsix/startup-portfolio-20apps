# 💡 Ideia: Startup Portfolio

> Este repositório é uma **ideia em validação**. Mapa completo de todas as ideias: [IDEIAS.md no repo `dev`](https://github.com/cantsixsix/dev/blob/claude/serene-bardeen-1tjfw2/IDEIAS.md).
>
> Estágios: 💡 ideia · 🧪 protótipo · 🚀 no ar · ✅ validada · 🗄️ arquivada.
> Regra: antes de escrever mais código, rodar o **teste** de uma variação. Sem reação em 2 semanas → 🗄️.

## X2 · Startup Portfolio — vitrine — `startup-portfolio-20apps` 🧪

- **X2.a Vitrine das ideias** — `public/` com todas as ferramentas do grupo A e V.
- **X2.b Banco de ideias** — `20-startup-ideas.jsx` (custo, MRR, concorrentes, lacuna) pode virar conteúdo/newsletter "1 ideia de micro-SaaS por semana".

## F3 · GreenPulse — ESG para PMEs — portfolio `esg` 🧪

Estimativa: $10-30k MRR · lacuna: só existe opção enterprise.
- **F3.a Calculadora ESG grátis** — gera lead. **F3.b Relatório pronto pago** — para fornecedor de empresa grande que exige ESG.

## V4 · PriceRadar — portfolio `price-monitor` 🧪

$10-30k MRR · lacuna: ninguém atende lojas pequenas.
- **V4.a Monitor para lojas Shopify.** **V4.b Monitor para vendedores do ML** (junta com V1). **V4.c Alerta de queda de preço para consumidor** (alimenta V2).

## V5 · BoxCrate — portfolio `sub-box` 🧪

$5-20k MRR · lacuna: Cratejoy fechou.
- **V5.a Gestão de clube de assinatura para creators.**

## V6 · ProofPulse — portfolio `social-proof` 🧪

$5-15k MRR.
- **V6.a Popup de prova social** — *teste:* instalar no PromoTech e medir conversão.
- **V6.b Copy do popup feita por IA.**

## V7 · LoveWall — portfolio `testimonials` 🧪

$10-25k MRR · lacuna: vídeo-first.
- **V7.a Mural de depoimentos em texto.** **V7.b Coleta de depoimento em vídeo.** **V7.c IA corta os melhores trechos.**

## V8 · LaunchPad — portfolio `waitlist` 🧪

$5-15k MRR.
- **V8.a Waitlist com indicação** — **usar como ferramenta de validação de todas as outras ideias.**
- **V8.b Página de lançamento + A/B test.**

## Ferramentas de IA para negócios (`public/apps/`)

| # | Ideia | Variações (nichos) | MRR estimado |
|---|---|---|---|
| A1 | **CodeSnap** · `screenshot-to-code` | a) print → landing page · b) print → componente React · c) clonar landing de concorrente | $10-30k |
| A2 | **ColdReach** · `cold-email` | a) gerador de e-mail · b) checador de entregabilidade grátis (`dnsChecks.js` já existe) · c) sequência de follow-up | $15-50k |
| A3 | **ProposalCraft** · `proposals` | a) proposta para freelancer · b) orçamento → fatura · c) proposta para agência | $10-30k |
| A4 | **HireWave** · `job-board` | a) job board white-label · b) board de nicho (ex.: vagas de dev BR) | $5-25k |
| A5 | **ShipLog** · `changelog` | a) changelog a partir de texto · b) changelog direto do GitHub · c) widget "novidades" no site | $5-15k |
| A6 | **PulseMetrics** · `analytics` | a) analytics sem cookie · b) insights automáticos por IA · c) alertas de queda de tráfego | $10-40k |
| A7 | **MeetingPad** · `meeting-notes` | a) vendas · b) clínicas/dentistas · c) advogados · d) imobiliárias | $15-50k |
| A8 | **BrandForge** · `brand-kit` | a) paleta + fontes · b) guia de marca completo · c) templates de post | $10-30k |
| A9 | **ClientHub** · `client-portal` | a) status de projeto · b) entrega de arquivos · c) aprovação de layout | $10-25k |
| A10 | **ResumeAI** · `resume` | a) currículo por vaga · b) otimização ATS avulsa ($4,99) · c) carta de apresentação | $10-30k |
| A11 | **PodWave** · `podcast` | a) show notes · b) newsletter do episódio · c) cortes/clips | $10-30k |
| A12 | **BlogForge** · `notion-blog` | a) Notion → blog · b) Notion → site · c) SEO automático | $5-20k |
| A13 | **UptimeGuard** · `uptime` | a) monitor + status page · b) IA explica por que caiu | $5-20k |
| A14 | **DeckBuilder** · `pitch-deck` | a) pitch deck · b) one-pager para investidor | $10-30k |

**Teste do grupo A:** colocar todas no ar com o LaunchPad (V8) na frente e ver quais 2–3 recebem inscrições. Só essas ganham repo próprio.

Números de MRR vêm de `20-startup-ideas.jsx` — estimativas, não dados verificados.

A plataforma que roda essas ferramentas (AI gateway + app hub) é a ideia **X1**, no repo `mega-repo`.

<!-- validacao:inicio -->

## 🧪 Como validar

Teste de 7 dias. Resultados vão na [Bancada de Ideias](https://claude.ai/artifact/Y4H9MCxyvwwLDmhL812znj).

### F3 · GreenPulse — ESG para PMEs

**Em uma frase:** Gera o relatório ESG (ambiental, social e governança) que empresas grandes começam a exigir dos fornecedores pequenos.

- **Problema:** PMEs que vendem para grandes empresas recebem questionário ESG e não sabem responder; consultoria é cara.
- **Para quem:** Fornecedores PME de indústrias e varejo grande.
- **Como funciona:** Você responde perguntas simples sobre a empresa e a IA monta um relatório ESG com pontuação.
- **Como ganha dinheiro:** Calculadora grátis; relatório completo por R$ 297.

| Teste | |
|---|---|
| Tipo | Conversar com 3–5 clientes |
| Página | https://validar-ideias.netlify.app/f3/ |
| Onde divulgar | LinkedIn: donos e gerentes de PMEs fornecedoras |
| Preço testado | R$ 297 por relatório |
| Meta em 7 dias | **3 empresas dispostas a pagar** |

### V4 · PriceRadar

**Em uma frase:** Avisa quando o concorrente muda o preço e sugere o seu.

- **Problema:** Lojista pequeno perde venda porque não percebe que o concorrente baixou o preço.
- **Para quem:** Lojas Shopify/Nuvemshop pequenas e vendedores de marketplace.
- **Como funciona:** Você cadastra os produtos dos concorrentes; ele checa os preços todo dia e manda alerta.
- **Como ganha dinheiro:** R$ 79/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/v4/ |
| Onde divulgar | Grupos de lojistas Shopify/Nuvemshop e vendedores ML |
| Preço testado | R$ 79/mês |
| Meta em 7 dias | **15 inscrições e 3 cliques no preço em 7 dias** |

### V5 · BoxCrate

**Em uma frase:** Gerencia assinantes de clube de assinatura (caixinha mensal) num lugar só.

- **Problema:** Quem tem clube de assinatura pequeno controla assinante em planilha e erra envio.
- **Para quem:** Creators e pequenas marcas com clube de assinatura (café, livros, cosméticos).
- **Como funciona:** Cadastro de planos, assinantes, cobranças e lista de envio do mês.
- **Como ganha dinheiro:** R$ 59/mês.

| Teste | |
|---|---|
| Tipo | Conversar com 3–5 clientes |
| Página | https://validar-ideias.netlify.app/v5/ |
| Onde divulgar | Instagram: buscar clubes de assinatura pequenos e mandar DM |
| Preço testado | R$ 59/mês |
| Meta em 7 dias | **3 donos de clube aceitam uma conversa** |

### V6 · ProofPulse

**Em uma frase:** Popups de 'Fulano acabou de comprar' que aumentam a confiança no site.

- **Problema:** Visitante de loja pequena desconfia e vai embora sem comprar.
- **Para quem:** Lojas online e infoprodutores.
- **Como funciona:** Um código que você cola no site; ele mostra notificações reais de compras/cadastros.
- **Como ganha dinheiro:** R$ 29/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/v6/ |
| Onde divulgar | Grupos de e-commerce e infoprodutores |
| Preço testado | R$ 29/mês |
| Meta em 7 dias | **20 inscrições em 7 dias** |

### V7 · LoveWall

**Em uma frase:** Coleta depoimentos de clientes (inclusive em vídeo) e mostra num mural no site.

- **Problema:** Depoimentos ficam perdidos em prints de WhatsApp e nunca chegam no site.
- **Para quem:** Prestadores de serviço, cursos online, agências.
- **Como funciona:** Você manda um link ao cliente, ele grava/escreve o depoimento, e o mural aparece no seu site.
- **Como ganha dinheiro:** R$ 39/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/v7/ |
| Onde divulgar | Grupos de prestadores de serviço e infoprodutores |
| Preço testado | R$ 39/mês |
| Meta em 7 dias | **20 inscrições em 7 dias** |

### V8 · LaunchPad

**Em uma frase:** Lista de espera que cresce sozinha: quem indica amigos sobe na fila.

- **Problema:** Lançar produto sem público; lista de espera comum não se espalha.
- **Para quem:** Quem vai lançar app, curso ou produto.
- **Como funciona:** Página de lista de espera com link de indicação e ranking.
- **Como ganha dinheiro:** R$ 29/mês ou R$ 99 por lançamento. O plano é usá-la também para validar as outras ideias deste mapa (hoje a validação usa um formulário da Netlify).

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/v8/ |
| Onde divulgar | Indie Hackers BR, grupos de makers |
| Preço testado | R$ 99 por lançamento |
| Meta em 7 dias | **20 inscrições em 7 dias** |

### A1 · CodeSnap

**Em uma frase:** Manda um print de site e recebe o código da landing page pronto.

- **Problema:** Criar landing page do zero demora; contratar dev é caro.
- **Para quem:** Fundadores, makers e freelancers sem tempo de codar layout.
- **Como funciona:** Upload do print ou descrição; a IA gera HTML/CSS/React funcional.
- **Como ganha dinheiro:** R$ 49/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a1/ |
| Onde divulgar | Twitter/X de makers, r/brdev |
| Preço testado | R$ 49/mês |
| Meta em 7 dias | **30 inscrições em 7 dias** |

### A2 · ColdReach

**Em uma frase:** Escreve e-mail de prospecção personalizado e checa se ele vai cair no spam.

- **Problema:** E-mail frio genérico é ignorado ou vai para o spam.
- **Para quem:** Vendedores B2B, agências e freelancers que prospectam.
- **Como funciona:** Você informa o cliente-alvo; a IA escreve o e-mail e aponta palavras que acionam spam.
- **Como ganha dinheiro:** R$ 59/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a2/ |
| Onde divulgar | LinkedIn de vendas B2B |
| Preço testado | R$ 59/mês |
| Meta em 7 dias | **25 inscrições em 7 dias** |

### A3 · ProposalCraft

**Em uma frase:** Transforma um briefing curto em proposta comercial profissional em 5 minutos.

- **Problema:** Freelancer perde horas montando proposta e às vezes perde o cliente pela demora.
- **Para quem:** Freelancers e pequenas agências.
- **Como funciona:** Cola o que o cliente pediu; a IA monta escopo, prazo e preço num documento bonito.
- **Como ganha dinheiro:** R$ 29/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a3/ |
| Onde divulgar | Grupos de freelancers (Workana, 99Freelas) |
| Preço testado | R$ 29/mês |
| Meta em 7 dias | **30 inscrições em 7 dias** |

### A4 · HireWave

**Em uma frase:** Crie um site de vagas de nicho com a sua marca em minutos.

- **Problema:** Comunidades de nicho postam vagas soltas no grupo e elas se perdem.
- **Para quem:** Donos de comunidades, newsletters e grupos de nicho.
- **Como funciona:** Site de vagas pronto com a sua marca; empresas pagam para anunciar.
- **Como ganha dinheiro:** R$ 99/mês para o dono do site de vagas.

| Teste | |
|---|---|
| Tipo | Conversar com 3–5 clientes |
| Página | https://validar-ideias.netlify.app/a4/ |
| Onde divulgar | DM para donos de comunidades de nicho |
| Preço testado | R$ 99/mês |
| Meta em 7 dias | **3 donos de comunidade interessados** |

### A5 · ShipLog

**Em uma frase:** Gera as notas de 'o que há de novo' a partir dos commits do GitHub.

- **Problema:** Ninguém gosta de escrever changelog, então os usuários nunca sabem das novidades.
- **Para quem:** Times pequenos de software e devs indie.
- **Como funciona:** Conecta no GitHub; a IA agrupa as mudanças em Novo / Melhorado / Corrigido.
- **Como ganha dinheiro:** R$ 39/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a5/ |
| Onde divulgar | Twitter/X de devs indie, Product Hunt |
| Preço testado | R$ 39/mês |
| Meta em 7 dias | **25 inscrições em 7 dias** |

### A6 · PulseMetrics

**Em uma frase:** Estatísticas do seu site sem cookies e com explicação em português do que mudou.

- **Problema:** Google Analytics é complicado e exige banner de cookies (LGPD).
- **Para quem:** Donos de sites pequenos, blogs e SaaS.
- **Como funciona:** Um script leve no site; painel simples e um resumo semanal escrito por IA.
- **Como ganha dinheiro:** R$ 29/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a6/ |
| Onde divulgar | Grupos de WordPress, blogueiros e makers |
| Preço testado | R$ 29/mês |
| Meta em 7 dias | **25 inscrições em 7 dias** |

### A7 · MeetingPad

**Em uma frase:** Transforma a gravação de reunião em resumo, decisões e tarefas — feito para um nicho específico.

- **Problema:** Ferramentas de ata são genéricas; dentista, advogado ou corretor precisa de formato próprio.
- **Para quem:** Começar por um nicho: corretores de imóveis, clínicas ou advogados.
- **Como funciona:** Cola a transcrição; a IA gera a ata no modelo do nicho.
- **Como ganha dinheiro:** R$ 79/mês.

| Teste | |
|---|---|
| Tipo | Conversar com 3–5 clientes |
| Página | https://validar-ideias.netlify.app/a7/ |
| Onde divulgar | Escolher 1 nicho e falar com 5 profissionais dele |
| Preço testado | R$ 79/mês |
| Meta em 7 dias | **2 de 5 profissionais querem pagar** |

### A8 · BrandForge

**Em uma frase:** Descreva seu negócio e receba cores, fontes e guia de marca completo.

- **Problema:** Pequeno negócio começa sem identidade visual e designer é caro.
- **Para quem:** MEIs e pequenos negócios abrindo agora.
- **Como funciona:** Você descreve o negócio; a IA gera paleta, tipografia, tom de voz e modelos de post.
- **Como ganha dinheiro:** R$ 97 por kit de marca.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a8/ |
| Onde divulgar | Grupos de MEI e empreendedorismo |
| Preço testado | R$ 97 por kit |
| Meta em 7 dias | **30 inscrições e 3 cliques no preço em 7 dias** |

### A9 · ClientHub

**Em uma frase:** Portal simples onde o cliente do freelancer vê status, arquivos e aprova entregas.

- **Problema:** Freelancer responde 'e aí, como está?' o dia todo no WhatsApp.
- **Para quem:** Freelancers de design, dev e marketing; pequenas agências.
- **Como funciona:** Um link por cliente com etapas do projeto, arquivos e botão de aprovação.
- **Como ganha dinheiro:** R$ 39/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a9/ |
| Onde divulgar | Grupos de freelancers de design/dev |
| Preço testado | R$ 39/mês |
| Meta em 7 dias | **25 inscrições em 7 dias** |

### A10 · ResumeAI

**Em uma frase:** Ajusta seu currículo para cada vaga, passando nos filtros automáticos (ATS).

- **Problema:** Currículo genérico é cortado pelo robô de RH antes de alguém ler.
- **Para quem:** Quem está procurando emprego, principalmente em tecnologia e administração.
- **Como funciona:** Cola a vaga e o seu currículo; a IA reescreve destacando o que a vaga pede.
- **Como ganha dinheiro:** R$ 9,90 por currículo otimizado.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a10/ |
| Onde divulgar | LinkedIn, grupos de vagas no Telegram |
| Preço testado | R$ 9,90 por currículo |
| Meta em 7 dias | **50 inscrições e 5 cliques no preço em 7 dias** |

### A11 · PodWave

**Em uma frase:** Transforma o episódio de podcast em resumo, tópicos com minutagem e newsletter.

- **Problema:** Podcaster gasta horas escrevendo descrição e divulgação de cada episódio.
- **Para quem:** Podcasters independentes.
- **Como funciona:** Envia a transcrição; recebe resumo, minutagem dos tópicos e texto de newsletter.
- **Como ganha dinheiro:** R$ 39/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a11/ |
| Onde divulgar | Grupos de podcasters BR |
| Preço testado | R$ 39/mês |
| Meta em 7 dias | **20 inscrições em 7 dias** |

### A12 · BlogForge

**Em uma frase:** Escreve no Notion e publica como blog rápido e bem posicionado no Google.

- **Problema:** Manter blog em WordPress dá trabalho; quem já escreve no Notion quer só publicar.
- **Para quem:** Criadores e pequenas empresas que usam Notion.
- **Como funciona:** Conecta uma página do Notion; vira um blog com domínio próprio e SEO automático.
- **Como ganha dinheiro:** R$ 35/mês por site.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a12/ |
| Onde divulgar | Comunidades de Notion BR |
| Preço testado | R$ 35/mês |
| Meta em 7 dias | **25 inscrições em 7 dias** |

### A13 · UptimeGuard

**Em uma frase:** Avisa quando seu site cai e explica em português o provável motivo.

- **Problema:** Site cai de madrugada e o dono só descobre quando o cliente reclama.
- **Para quem:** Donos de lojas online, SaaS pequenos e agências.
- **Como funciona:** Checa o site a cada minuto; se cair, manda alerta no WhatsApp com diagnóstico.
- **Como ganha dinheiro:** R$ 19/mês.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a13/ |
| Onde divulgar | Grupos de agências e e-commerce |
| Preço testado | R$ 19/mês |
| Meta em 7 dias | **25 inscrições em 7 dias** |

### A14 · DeckBuilder

**Em uma frase:** Monta o pitch deck da sua startup em 5 minutos.

- **Problema:** Fundador de primeira viagem não sabe estruturar apresentação para investidor.
- **Para quem:** Fundadores em estágio inicial, alunos de aceleradora.
- **Como funciona:** Responde perguntas sobre o negócio; a IA gera os slides de problema, solução, mercado e pedido de investimento.
- **Como ganha dinheiro:** R$ 97 por deck.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/a14/ |
| Onde divulgar | Grupos de startups e aceleradoras |
| Preço testado | R$ 97 por deck |
| Meta em 7 dias | **20 inscrições em 7 dias** |

### X2 · Startup Portfolio — vitrine

**Em uma frase:** Vitrine com os 20 apps do portfólio e um banco de ideias de micro-SaaS (pequenos softwares vendidos por assinatura).

- **Problema:** Quem quer empreender não sabe que ideia de micro-SaaS escolher.
- **Para quem:** Aspirantes a empreendedor digital.
- **Como funciona:** Página com as ferramentas + newsletter semanal com 1 ideia analisada (custo, concorrentes, lacuna).
- **Como ganha dinheiro:** Newsletter grátis; banco completo de ideias por R$ 49.

| Teste | |
|---|---|
| Tipo | Post de conteúdo com link |
| Página | https://validar-ideias.netlify.app/x2/ |
| Onde divulgar | Twitter/X e LinkedIn com 1 ideia por post |
| Preço testado | R$ 49 (banco completo) |
| Meta em 7 dias | **100 inscrições em 14 dias** |

<!-- validacao:fim -->
