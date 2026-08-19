# Boop — Contexto de marca e projeto

Este arquivo reúne tudo que existe hoje sobre a Boop. Coloque na raiz do projeto (Claude Code lê `CLAUDE.md` automaticamente) para qualquer trabalho relacionado à marca — site, copy, identidade visual, materiais comerciais, operação.

## O que é a Boop

- Fundada e tocada por Jabez, em Curitiba.
- Posicionamento **atual (o mais recente e o que vale)**: **consultoria de gestão de marca e crescimento** — não usar a palavra "agência" para descrever a Boop. Isso é um reposicionamento; materiais mais antigos (inclusive a skill de copywriting) ainda descrevem a Boop como "agência de marketing" — trate isso como desatualizado.
- Frentes de trabalho: site, anúncios e conteúdo — mais, num segundo momento, projetos personalizados (ex.: CRM básico de leads com captura via WhatsApp).
- Abordagem: diagnóstico antes de execução. Não é a agência de "cardápio fechado" de serviço genérico.
- Público-alvo: pequenos e médios negócios que já desconfiam de agência — ou levaram um "cano" antes, ou acham que é só relatório bonito sem resultado de verdade.
- Meta de crescimento: operação enxuta (no máximo 4 pessoas), faturamento-alvo de R$100k.
- Domínio: **deumboop.com.br** (registrado no Registro.br, com e-mail configurado). Site hospedado na Vercel (decisão consciente contra hospedagem compartilhada tipo GoDaddy/Hostinger/Locaweb, que não roda Node/Next.js).

## Time

Aparecem como gente de verdade nos posts e materiais, não só como "a marca". Distribuição real de trabalho:

1. **Jabez** — Criação e edição, roteirização, criação do site. É quem toca a parte mais criativa da operação.
2. **Duda** — Produção e Edição
3. **Renatha** — Captação de clientes; também ajuda no operacional.

## Identidade visual

### Logo
- Wordmark **"boop"**, com os dois "o" funcionando como olhos de uma criatura fofa (círculos cheios, esclera branca, pupila escura com brilho, um ciano/azul-médio e outro azul-tinta) + topete/tufo espinhado em preto/azul-tinta entre os olhos.
- Descrição mais recente do estilo: "monstrinho fofo" (olhos grandes redondos, tufos de pelo no topo) — mais macio que a leitura anterior de "olhos de passarinho".
- Assinatura "AGÊNCIA" em caixa alta espaçada aparecia nas versões antigas da logo — **revisar isso**, já que a marca não deve mais se chamar de agência.
- Símbolo isolado = só os dois olhos + topete + chifre. **Não existe** cabeça de pássaro nem queixo/diamante abaixo dos olhos — esse elemento foi removido e não pode aparecer em nenhum código/peça.
- Versões: b/p em azul-tinta para fundos claros; b/p em branco para fundos escuros/azuis.
- **Regra inegociável: a logo NUNCA deve ser redesenhada em código.** Sempre usar os SVGs reais exportados do Figma. Quando o arquivo real não estiver disponível (ex.: PDF institucional), usar só o wordmark tipográfico "boop", sem tentar recriar o ícone dos olhos.

### Cores
Duas paletas coexistem — usar a certa conforme o contexto:

**Site / produto digital**
- `--azul-eletrico`: `#1B3FE0`
- `--ciano-boop`: `#00D4F5`
- `--azul-tinta`: `#0A1740`
- `--off-white`: `#F2EFE9`
- `--preto`: `#08080A`
- A logo em si usa as cores reais do SVG (ciano/azul-teal), não necessariamente o `--azul-eletrico` dos tokens do site.

**Peças de negócio / propostas / institucional**
- Creme `#FFFDF5` (fundo)
- Teal `#26A1C8` (destaque)
- Navy escuro `#0B1B2C` (texto/contraste)
- Indigo `#1B3FE0` (acento secundário)

Paleta "oficial" de marca mencionada de forma mais geral: ciano vibrante, preto e branco.

### Tipografia
- Títulos: **Space Grotesk Bold**
- Corpo: **Inter**

### Proibido visualmente
- Gradiente verde-roxo
- Mascote de yeti
- Ícones de estoque batidos
- Ilustrações clichê de crescimento (setas, foguetes)

### Registros visuais distintos
Existem dois registros visuais diferentes, não misturar:
- **Rede social**: mais expressivo (a "criatura" do logo, tom leve).
- **Boop para negócios** (propostas, PDFs comerciais): sóbrio e editorial.

## Voz de marca

### Redes sociais (posts, legendas, carrosséis)
- **Leve e descontraída — NÃO irreverente/debochada, NÃO provocativa/opinião forte.** Este é o ponto mais fácil de errar.
- Frases curtas, ritmo de conversa, não de press release.
- Pode ter leveza ou uma virada inesperada de frase, mas nunca à custa da clareza do resultado.
- Zero jargão corporativo vazio ("soluções inovadoras", "somos apaixonados por marketing") e zero superlativo genérico ("o melhor", "revolucionário").
- Fala **com** a pessoa, não **para o mercado**.
- Teste rápido: se o post pudesse ter sido escrito por qualquer agência genérica trocando só o nome, reescreve. Se a piada precisa de explicação, corta.
- "Boop" é gancho de linguagem (cutucar, empurrar, ativar) — ex. headline oficial **"Dê um boop na sua empresa"**. Usar com moderação, é tempero, não a piada de todo post.

### Peças de negócio (propostas, PDFs, contratos)
- Frases curtas e declarativas, com contraste e ritmo.
- Sem conectivos tipo "a empresa que X e faz Y para Z".
- Sem lista genérica de serviços.
- Autoridade vem da clareza do pensamento e do posicionamento — nunca de prova social fabricada.

### Regra de ouro dos números (vale nos dois registros)
- Prefira número absoluto a porcentagem ("de 3 para 11 vendas por semana", não "+266%").
- Toda porcentagem precisa vir com legenda de prazo e base de comparação.
- Frase-símbolo da marca: **"a gente conta olho no olho"** — sem gráfico inflado, sem métrica que não paga conta.
- Título usado numa seção de resultados: "A gente conta olho no olho" (com "olho no olho" em serif itálica) + apoio "Sem gráfico inflado. Sem métrica que não paga conta."

### Estrutura de case (post ou peça)
1. Quem é o cliente (nome, função, negócio, cidade — com foto da pessoa em duotone, quando visual)
2. Onde a pessoa estava antes (frase concreta, sem drama)
3. O número (de preferência absoluto)
4. O que a Boop fez (uma frase, sem se gabar)
5. Uma linha na voz da própria pessoa (depoimento curto)

### O que evitar sempre
- Clichê de agência ("resultados que impressionam", "somos apaixonados", "growth hacking")
- Emoji em excesso ou fora de tom
- Porcentagem sem contexto
- Humor ácido/debochado ou opinião polêmica forçada
- Textão em redes sociais — legendas curtas, com respiro visual (parágrafos de 1-2 linhas)

### CTA
Existe **um único CTA** em toda a operação de conteúdo: agendar diagnóstico gratuito de 30 min via WhatsApp. Não inventar outros CTAs (e-book, seguir a página etc.) a menos que peçam explicitamente.

## Site (deumboop.com.br)

- Formato: one-page longa com âncoras, texto em pt-BR.
- CTA único: agendar diagnóstico gratuito de 30 min via WhatsApp.
- Estilo desejado: bem interativo, com animações, scroll horizontal/lateral, linha de azul, nada genérico.
- Referências visuais citadas: Forge Motorsports (azul chapado + tipografia gigante), Crunchy sound studio (gradiente azul blur), Forma Studio (azul + tipografia oversized), 21st.dev (dark azul), Normal is Boring (tipografia editorial + scroll lateral).

**Stack**
- Next.js (App Router) + TypeScript + Tailwind
- Framer Motion + GSAP/ScrollTrigger + Lenis (scroll suave)

**Elementos visuais**
- Fundo animado: componente React de grid animado + ruído sobre azul escuro ("noise-dark-blue-gradient-with-squares").
- Elemento-assinatura: os dois "o" do logo como olhos com pupilas de ciano que seguem o cursor.
- No H1 do hero, a palavra "boop" deve ser o SVG real do wordmark embutido na frase (não texto serif itálico). Esse SVG específico ("boop-wordmark") é exclusivo para a palavra dentro da frase do hero — não é a logo principal do header/footer nem o símbolo isolado.
- O símbolo (olhos + topete) fica centralizado à direita do hero, alinhado ao título — nunca empurrado para o rodapé da seção.
- Headline do hero em tamanho grande (clamp ~40px/8.5vw/138px, 4 linhas, entrelinha .84) — "grande, mas coerente"; se precisar reduzir, quebrar em mais linhas curtas em vez de diminuir a fonte.

**Copy do hero**
- Headline: **"Dê um boop na sua empresa"**
- Subheadline: Boop cuida do site, dos anúncios e do conteúdo; relatório todo mês com quanto entrou (sem mencionar "três pessoas" no texto).

**Estrutura de conteúdo**
- Serviços: site, anúncios, conteúdo (título do serviço de anúncios ainda em aberto — "Anúncio que se paga" foi descartado, precisa de copy melhor).
- Seção de resultados: título "A gente conta olho no olho" + cards de case na estrutura acima.
- Seção de time: Jabez, Duda, Renatha, nessa ordem.

## Operação interna

- Toda a operação da Boop roda dentro da **Ummense**: fluxos = processos, cards = projetos/leads, tarefas dentro dos cards, painel para tarefas/eventos diários. Objetivo: não depender de planilha.
- Fase 2 planejada: um fluxo por cliente dentro da Ummense, com privacidade definida, para o cliente acompanhar o próprio projeto (planejamento de posts, etapas).
- Existe (ou existiu) um fluxo dedicado à gestão de posts da Boop dentro da Ummense (etapas de produção, cards por post, tarefas, painel de rotina).
- Documentação em estruturação: diagnóstico, proposta, contrato, e endomarketing da Boop.
- Possível produto adicional (fase futura): CRM básico de leads para clientes, com captura automática via integração de WhatsApp, no mesmo portal onde o cliente acompanha interações, anúncios e conteúdo.
- Explorou automação de WhatsApp via feature Coexistence da Meta + Supabase Edge Functions como possível oferta de serviço.

## Estratégia de conteúdo

- Fase atual: ainda validando os primeiros cases — o objetivo do conteúdo agora é construir audiência/confiança, não vender agressivamente.
- Foco inicial (fase de lançamento): exclusivamente conteúdo para redes sociais e site — sem anúncios pagos por enquanto.
- Linha editorial — pilares, alternados ao longo da semana/mês (nunca dois posts do mesmo pilar seguidos sem pedido explícito):
  1. Cases/resultado de cliente
  2. Bastidores da agência/consultoria (processo real, não "dia perfeito")
  3. Conteúdo educativo (erro comum ou verdade incômoda do marketing para pequeno negócio, explicada simples)
  4. Opinião leve do time (algo que incomoda no mercado, dito com leveza — nunca debochado)
- Método editorial próprio: **ATA** — Atração → Técnico → Autoridade — com biblioteca de formatos, análise manual de Reels de referência e ciclos semanais de teste com métricas.
- Cadência-meta: 3 reels + 3 carrosséis por semana, de forma constante.
- Primeiro reels já lançado.
- Frentes de estudo para elevar qualidade de conteúdo: colorimetria, edição de vídeo, criação de carrossel, estratégia.
- Existe uma skill separada no Claude Code chamada **`boop-copywriting`** para redigir posts seguindo essa linha editorial — mas atualiza a Boop como "consultoria", não "agência", ao usá-la (a skill ainda está desatualizada nesse ponto).

## Materiais institucionais

**PDF comercial (~10 páginas)**, para prospecção via WhatsApp. Regra explícita: nada de cases, clientes, resultados, métricas ou depoimentos inventados — autoridade vem da clareza do pensamento e do posicionamento, deixando espaço para o próprio destinatário virar o primeiro case. Estrutura:
1. Capa
2. O que é a Boop
3. Posicionamento (não é consultoria/agência tradicional de cardápio fechado)
4. Frentes de trabalho (conteúdo / digital / projetos personalizados)
5. Como podemos ajudar (identificação por problema)
6. Como trabalhamos (método em 4 etapas: entender → pensar → criar → colocar no mundo)
7. O que pode sair de uma Boop (catálogo de possibilidades, não cases)
8. Por que Boop (diferenciais)
9. Vamos conversar (CTA comercial)
10. Contato

**Vídeo de lançamento/inauguração**: roteiro dividido entre falas de Jabez e Renatha, cenas dinâmicas, trilha sonora boa, edição simples, estilo de copywriting pessoal/magnético (referência de tom citada: conteúdo "magnético" no estilo de Julia Becks). Não pode soar como "mais uma agência genérica que nasce igual às outras" — tom único, pessoal, "nosso".

## Negócios em andamento

- **Velmont Marcas e Patentes** (Curitiba, marcas e patentes) — em negociação como primeira cliente da Boop, via permuta.
  - Sócias: Danielle Cubas de Azevedo e Lisandra Ferreira dos Santos.
  - Proposta: Boop entrega site institucional + arquitetura editorial + primeiro ciclo de aplicação em 30 dias.
  - Em troca: pesquisa de anterioridade, registro da marca "boop" no INPI, alinhamento de contratos/titularidade.
  - Deck da proposta já gerado em .pptx, para servir de base a um deck refinado no Figma.

## Regras não-negociáveis (resumo rápido)

- Nunca chamar a Boop de "agência" — é consultoria de gestão de marca e crescimento.
- Nunca redesenhar a logo em código — só usar os SVGs reais exportados do Figma.
- Nunca inventar case, cliente, resultado, métrica ou depoimento.
- Nunca usar porcentagem sem prazo e base de comparação; preferir número absoluto.
- Nunca usar humor ácido/debochado ou opinião provocativa — a voz é leve, não engraçadinha.
- Nunca usar clichê de agência, superlativo genérico ou jargão corporativo vazio.
- Um único CTA em conteúdo: diagnóstico gratuito de 30 min via WhatsApp.
