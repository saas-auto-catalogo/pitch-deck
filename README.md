# 🚗 DriveSync — Investor Pitch Deck & Materiais de Captação

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Apresentação%20Online-blue?style=flat-square&logo=github)](https://saas-auto-catalogo.github.io/pitch-deck/)
[![PDF Pitch Deck (16:9)](https://img.shields.io/badge/PDF-Pitch%20Deck%2016%3A9-emerald?style=flat-square)](./exports/DriveSync-Pitch-Deck-2026.pdf)
[![PDF One-Pager (A4)](https://img.shields.io/badge/PDF-One--Pager%20Executivo-emerald?style=flat-square)](./exports/DriveSync-One-Pager.pdf)
[![Licença](https://img.shields.io/badge/Licença-Proprietária%20%2F%20Confidencial-red?style=flat-square)](./LICENSE)

Repositório oficial de relações com investidores, tese de investimento e materiais de captação da plataforma **DriveSync** (SaaS Auto Catálogo).

**Rodada Pré-Seed em andamento:** R$ 1M (soft cap R$ 600k) via **Mútuo Conversível** (LC 182/2021) — pipeline consolidado em [`fundraising/`](./fundraising/).

---

## 📥 Materiais para Envio Rápido (WhatsApp / E-mail)

**Formatos estáticos prontos para envio direto a investidores e parceiros**, gerados em alta qualidade a partir dos templates de impressão da pasta [`/exports`](./exports).

| Documento | Formato | Conteúdo |
|---|---|---|
| [**Pitch Deck Completo**](./exports/DriveSync-Pitch-Deck-2026.pdf) | PDF Widescreen 16:9 (12 páginas) | Todos os 12 slides em paisagem, com mockups HD e dados consolidados — ideal para telas e apresentações offline |
| [**One-Pager Executivo**](./exports/DriveSync-One-Pager.pdf) | PDF A4 (1 página) | Síntese da tese: problema, solução, métricas & ROI, TAM/SAM/SOM, planos e contato |
| [Fonte do Pitch Deck (HTML)](./exports/print-deck.html) | HTML `@page` 16in × 9in | Template de impressão dos 12 slides — gere/atualize o PDF em qualquer navegador (Ctrl+P) |
| [Fonte do One-Pager (HTML)](./exports/one-pager.html) | HTML Tailwind CSS A4 | Template do one-pager otimizado para impressão |

> ⚠️ **Confidencial**: os PDFs são exclusivos para uso interno e envio a investidores e parceiros autorizados, conforme a licença do repositório.

---

## 🧭 Resumo Executivo
> **"Para concessionárias e revendas de seminovos que perdem milhares de reais em anúncios manuais e carros já vendidos, o DriveSync é a plataforma SaaS que conecta automaticamente os DMSs de pátio ao Meta Automotive Inventory Ads (DAA) em 3 minutos, reduzindo o Custo por Lead em 29% a 47% (média de -47%), reduzindo o custo por carro vendido em 44,8% e eliminando 100% do inventário fantasma."**

---

## 🖥️ Apresentação Interativa (Slides)
A apresentação visual interativa dos 12 slides foi desenvolvida com Tailwind CSS e navegação via teclado:
- **Apresentação Online**: [saas-auto-catalogo.github.io/pitch-deck](https://saas-auto-catalogo.github.io/pitch-deck/)
- **Arquivo Local / GitHub**: [`index.html`](./index.html)
- **Roteiro & Notas de Oratória**: [`slides/pitch_deck_drivesync.md`](./slides/pitch_deck_drivesync.md)
- **Navegação**: Use as setas do teclado (`←`, `→`, `Espaço`), `F` para tela cheia, atalhos numéricos via URL (`#slide-N`) ou deslize com o dedo (*swipe touch*) em dispositivos móveis.

---

## 💼 Captação de Investimento & Fundraising

Processo de captação da rodada Pré-Seed da DriveSync, com base de inteligência de mercado e instrumento jurídico já estruturados:

| Arquivo | Conteúdo |
|---|---|
| [**Pipeline de Investidores (CSV)**](./fundraising/pipeline-investidores.csv) | CRM com **52 registros**: 36 anjos setoriais (ex-Webmotors, ex-99, ex-iCarros, ex-OLX, Fenabrave, CAOA), 11 fundos Seed/Pré-Seed SaaS B2B (Canary, Maya, DOMO.VC, Bossa, SaaSholic, Astella, ONEVC, etc.) e 5 redes/veículos (BR Angels, GVAngels, FJ Labs) |
| [**CRM & Governança do Funil**](./fundraising/investors-crm.md) | Estágios Lead ➔ Term Sheet, métricas semanais, matriz de priorização, FAQ de argumentos e ritmo de abordagem |
| [**Teasers de Abordagem**](./fundraising/teasers-outreach.md) | 4 templates de 2 parágrafos (LinkedIn InMail, WhatsApp, E-mail Executivo, Redes de Anjos) com dados da tese |
| [**Instrumento de Investimento**](./fundraising/instrumento-investimento-safe-mutuo.md) | Especificação do **Mútuo Conversível** (LC 182/2021): R$ 1M (soft cap R$ 600k), cap R$ 10M pós-money, desconto 20%, vencimento 24 meses, MFN |
| [**Inteligência de Anjos Automotivos**](./fundraising/Investidores%20Anjo%20do%20Mercado%20Automotivo.md) | Relatório analítico: 36 investidores-anjo com histórico no setor e teses de investimento |
| [**Inteligência de Fundos SaaS B2B**](./fundraising/Mapeamento%20Fundos%20SaaS%20B2B.md) | Relatório analítico: fundos Seed/Pré-Seed LATAM, faixas de cheque, critérios de subscrição e métricas por estágio |

---

## 📈 Dataroom Financeiro & Projeções (24 Meses)

Projeções detalhadas mês a mês, dinâmica de unit economics, cohorts e uso de recursos da rodada Pré-Seed, consolidados na pasta [`financials/`](./financials/):

| Documento | Formato | Conteúdo |
|---|---|---|
| [**Relatório do Modelo Financeiro**](./financials/modelo-financeiro-24-meses.md) | Relatório Executivo Markdown | Análise exaustiva dos 24 meses: DRE projetada, fluxo de caixa, cohorts de churn (<2,5%) e NRR (>105%), mix de canais e análise de sensibilidade |
| [**Projeção Mensal M01-M24 (Planilha)**](./financials/drivesync-projecao-financeira-24m.csv) | CSV Universal (UTF-8 / `;`) | Planilha tabular completa mês a mês com clientes, MRR por plano, ARR, impostos, COGS, OPEX, EBITDA e fluxo de caixa acumulado |
| [**Unit Economics & Mix de Canais**](./financials/unit-economics-e-canais.csv) | CSV Paramétrico (UTF-8 / `;`) | CAC, LTV, Payback, ciclo de vendas e taxas de conversão por canal (Inbound IA, Agências B2B2B e Outbound) |
| [**Alocação de Capital & Headcount**](./financials/alocacao-capital-headcount.csv) | CSV Orçamentário (UTF-8 / `;`) | Use of proceeds de R$ 1.000.000 (GTM 45%, P&D 35%, Operações 10%, Reserva 10%) e evolução de quadro de colaboradores |
| [**Guia do Dataroom (README)**](./financials/README.md) | Guia de Navegação | Instruções de importação em Excel e Google Sheets e síntese dos indicadores-chave |

---

## 📑 Estrutura do Repositório

```text
├── index.html                     # Apresentação interativa dos 12 slides (Tailwind CSS)
├── slides/
│   └── pitch_deck_drivesync.md    # Roteiro textual completo, notas de oratória e métricas
├── exports/                       # Formatos estáticos prontos para envio (PDF 16:9 + One-Pager)
│   ├── DriveSync-Pitch-Deck-2026.pdf  # PDF widescreen 16:9 com os 12 slides (alta resolução)
│   ├── DriveSync-One-Pager.pdf        # One-pager executivo em A4 (1 página)
│   ├── print-deck.html                # Template de impressão do deck (16in × 9in)
│   └── one-pager.html                 # Template de impressão do one-pager (Tailwind, A4)
├── financials/                    # Projeções financeiras de 24 meses e Dataroom Pré-Seed
│   ├── README.md                      # Guia executivo e sumário de métricas do Dataroom
│   ├── modelo-financeiro-24-meses.md  # Relatório analítico completo (DRE, Fluxo de Caixa, NRR)
│   ├── drivesync-projecao-financeira-24m.csv # Planilha tabular detalhada mês a mês (M01-M24)
│   ├── unit-economics-e-canais.csv    # CAC, LTV, Payback e canais (Inbound, Agências, Outbound)
│   └── alocacao-capital-headcount.csv # Use of proceeds de R$ 1M e headcount roadmap
├── Sincronização DMS e Meta Ads.md # Benchmarks empíricos de CPL, CTR, CPC e conversão
├── Inventário Fantasma em Concessionárias.md # Diagnóstico técnico, latência de fim de semana e evasão orçamentária
├── .github/
│   └── workflows/
│       └── deploy-pages.yml       # Deploy automático no GitHub Pages a cada push na main
├── assets/                        # Assets visuais de alta definição (HD) e multimídia
│   ├── mockup-instagram-bmw-320i.png    # Mockup do simulador de anúncio Instagram (BMW 320i)
│   ├── mockup-instagram-porsche-macan.png # Mockup do simulador Meta Advantage+ (Porsche Macan)
│   ├── tabela-pendencias-estoque.png     # Captura da Tabela de Pendências de Estoque do frontend-app
│   ├── mapeador-de-para.png             # Captura do Estúdio Mapeador De/Para Interativo
│   ├── demo-sync-feed.mp4               # Vídeo curto (10s) da demonstração de sincronização ponta-a-ponta
│   ├── demo-sync-feed.gif               # Versão em GIF animado para fallback e compartilhamento
│   ├── car-bmw-320i.jpg                 # Fotografia de alta resolução do veículo BMW 320i M Sport
│   └── car-porsche-macan.jpg            # Fotografia de alta resolução do veículo Porsche Macan GTS
├── fundraising/                   # Processo de captação da rodada Pré-Seed
│   ├── pipeline-investidores.csv          # CRM do funil: 36 anjos + 11 fundos + 5 redes/veículos
│   ├── investors-crm.md                   # Governança do funil (Lead ➔ Term Sheet) e métricas
│   ├── teasers-outreach.md                # 4 templates de abordagem (LinkedIn, WhatsApp, E-mail, Redes)
│   ├── instrumento-investimento-safe-mutuo.md # Mútuo Conversível (LC 182/2021) — termos da rodada
│   ├── Investidores Anjo do Mercado Automotivo.md # Inteligência de anjos do setor automotivo
│   └── Mapeamento Fundos SaaS B2B.md      # Inteligência de fundos Seed/Pré-Seed LATAM
```

---

## 📊 Principais Indicadores & Benchmarks Empíricos do Negócio

| Métrica | Valor / Benchmark | Impacto Operacional / Fonte |
|---|---|---|
| **Redução de CPL Médio** | **-29% a -47% (média -47%)** | De $42,50 para $22,58 com AIA sincronizado ao DMS (Meta Benchmarks) |
| **Custo por Carro Vendido** | **-44,8% ($259 vs $469)** | Redução direta de R$ 1.050+ no custo de aquisição por veículo comercializado |
| **Eliminação de Inventário Fantasma**| **100% Supressão (&lt; 15 min)** | Estanca perda de **R$ 1.800 a R$ 5.760/mês** (até **28,8% do orçamento de mídia**) |
| **Latência de Fim de Semana** | **&lt; 15 min (vs 48h–72h manual)** | Elimina o gargalo crítico entre faturamento na sexta e consumo mobile no sábado/domingo |
| **Aumento no Volume de Leads** | **3,4x (+240%)** | De 1,0x para 3,4x mais conversões com o mesmo investimento em mídia |
| **Taxa de Conversão (CVR)** | **7,80% (vs 2,30%)** | VDP canônica e dados exatos de preço, km e fotos eliminam atrito e suspeita de *bait-and-switch* |
| **Taxa de Cliques (CTR)** | **1,80% a 4,50% (vs 0,90%)** | Relevância contextual no leilão (+100% a +400% de CTR no link) |
| **Economia Operacional** | **~40h / mês por loja** | Fim do upload e cadastro manual repetitivo de fotos e preços |
| **TAM (Brasil)** | **R$ 106M / ano** | +45.000 revendas e concessionárias ativas (Fenauto / Fenabrave) |
| **SAM** | **R$ 52M / ano** | ~22.000 revendas que já investem em mídia paga digital |
| **SOM (24 meses)** | **R$ 2,26M ARR** | 900 concessionárias ativas capturadas com ticket médio de R$ 210/mês |
| **Margem Bruta SaaS** | **> 88%** | Modelo SaaS B2B puro com infraestrutura em Node/Postgres/Redis |
| **LTV / CAC** | **10,4x** | LTV R$ 4.700 vs CAC R$ 450 (Inbound IA + Parcerias de Agências) |

---

## 🗺️ Mapa de Repositórios da Organização

| Repositório | Escopo | Stack Principal |
|---|---|---|
| [**backend-api**](https://github.com/saas-auto-catalogo/backend-api) | API multi-tenant, streaming parser SAX, motor de diffs e feed Meta DAA | Node.js, Fastify, Prisma, Redis, BullMQ |
| [**frontend-app**](https://github.com/saas-auto-catalogo/frontend-app) | Painel do lojista, simulador de anúncios e tabela de pendências | React 18, Vite, Tailwind CSS |
| [**backoffice-app**](https://github.com/saas-auto-catalogo/backoffice-app) | Painel Super Admin, telemetria global e auditoria | React 18, Vite, Tailwind CSS |
| [**marketing-site-blog**](https://github.com/saas-auto-catalogo/marketing-site-blog) | Site institucional comercial, planos e blog de autoridade | React 18, Vite, Tailwind CSS |
| [**ai-content-worker**](https://github.com/saas-auto-catalogo/ai-content-worker) | Agente IA autônomo de SEO e pesquisa de mercado | LangGraph, Gemini, Deep Research |
| [**legal-docs**](https://github.com/saas-auto-catalogo/legal-docs) | Termos de uso, privacidade e contratos em Akoma Ntoso | Akoma Ntoso, XML |
| [**.github**](https://github.com/saas-auto-catalogo/.github) | Governança, SDLC, especificações técnicas e wiki | GitHub Actions, Specs |
| [**pitch-deck**](https://github.com/saas-auto-catalogo/pitch-deck) | Pitch deck executivo, apresentação interativa e relações com investidores | HTML, Markdown, GitHub Pages |
