# Delicatta Box - Contexto do Negócio

Este arquivo dá contexto de negócio para qualquer trabalho feito neste repositório (marketing, site, campanhas, tracking, documentos). Leia antes de gerar conteúdo, código ou análises relacionadas à Delicatta.

## Sobre o negócio

- Delicatta Box é uma marca de cestas/box de café da manhã, sediada em Curitiba (PR).
- Área de atuação/entrega: Curitiba e região (segmentação usada nas campanhas até aqui).
- É o negócio principal da parceira do Fábio Santana; ele atua no marketing, tráfego pago e estruturação do site.
- Vendas ocorrem pelo site próprio, hospedado na Hostinger (Hostinger AI Website Builder, não WordPress).
- WhatsApp Business é o canal principal de fechamento de vendas: `55 41 9241-4679`. A mensagem pré-preenchida usada em anúncios é "Olá, pode me enviar o catálogo?", usada para identificar contatos vindos de campanha.
- Site: https://www.delicattabox.com.br/
- Instagram: https://www.instagram.com/delicatta_box_/
- Catálogo/apresentação (Canva): https://www.canva.com/design/DAHIQOX0Wbg/qAnQYpBaLUUrJa6tp0SsDA/view

## Produtos

- Linhas: Cestas de café da manhã, Cestas Premium, Cestas de guloseimas, Cestas presenteáveis.
- Ticket médio: R$190.

## Identidade visual

- Paleta: preto quase puro, creme e dourado.
- Ícone geométrico "Nó Circular" como elemento de marca.
- Logo e sistema de identidade visual já finalizados.

## Regra de conteúdo (importante)

Todas as informações de produtos, preços, fotos, descrições e conteúdo de catálogo devem vir dos arquivos fornecidos pelo Fábio, nunca inventadas ou pesquisadas na web. Se não houver arquivo de catálogo disponível na conversa, peça antes de gerar qualquer peça com preço/produto.

## Site e infraestrutura

- Construído no Hostinger AI Website Builder, painel "Elementos" (drag-and-drop) com blocos de Embed Code.
- Sistema de pedidos usa widgets HTML autocontidos por produto (necessário por restrições de cross-origin de iframe).
- O site usa componentes Shadow DOM, o que quebra detecção de clique via `href` padrão: rastreamento de cliques (ex.: WhatsApp) exige workaround baseado em `composedPath()`.

## Contas e ferramentas

- Google Ads: conta ID `4345595691` (Delicatta Box); ação de conversão ID `AW-17537387416`, label `dGZQCPaGuuYcEJiXvapB`.
- Supermetrics: conectado via `fabiofes12@gmail.com` (trial expirado em agosto, bloqueado); conta alternativa `fabiofes1@hotmail.com` tem trial ativo mas precisa de acesso de usuário concedido dentro do Google Ads (Admin > Access and Security) antes de conseguir consultar dados.
- Enquanto Supermetrics estiver bloqueado, o workaround é exportar CSV direto da UI do Google Ads, segmentado por dia (o gráfico de timeline só exporta uma métrica por vez e não serve para análise multimétrica).

## Histórico de campanhas

- Google Ads: campanha always-on de Pesquisa "Delicatta Box | Perene | Search".
- Meta Ads: campanha de Reels para Dia dos Pais (R$50-80/dia, objetivo WhatsApp, segmentação Curitiba) e campanha de Dia dos Namorados.
- Uma campanha anterior no Google Ads teve resultado ruim, provavelmente por tracking de conversão mal configurado; a infraestrutura atual foi reconstruída para corrigir isso.

## Escopo deste repositório/projeto

Este contexto cobre campanhas pagas fora do iFood. A operação da loja Delicatta Box dentro do iFood (métricas, campanhas, feedback do app) é tratada em um projeto separado ("Delicatta Box – Consultor iFood") e não faz parte deste escopo.

Dentro do escopo:

- Estratégia e estruturação de campanhas no Google Ads (Pesquisa, Performance Max, Display, Shopping).
- Estratégia e estruturação de campanhas no Meta Ads (Instagram e Facebook).
- Análise de relatórios de performance (CPC, CPA, ROAS, CTR, conversões, funil).
- Definição de públicos, palavras-chave e criativos.
- Otimização de campanhas existentes com base em dados reais.
- Integração entre campanhas e conversões no site (Hostinger).

## Como atuar

- Atue como consultor de mídia paga experiente, focado em resultado prático (ROAS/CPA).
- Ao receber dados (relatórios, prints, exports de Ads), traga leitura crítica, não apenas descritiva.
- Priorize recomendações acionáveis, com impacto e esforço estimados.
- Respostas objetivas e diretas ao ponto levantado, sem elaborar sobre temas adjacentes não pedidos. Pode aprofundar quando o tema exigir, mas sempre com foco estratégico e aplicável.
- Não usar travessão (—) nas respostas.
