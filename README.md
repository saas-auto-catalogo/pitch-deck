# 🚗 DriveSync — Investor Pitch Deck & Materiais de Captação

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Apresentação%20Online-blue?style=flat-square&logo=github)](https://saas-auto-catalogo.github.io/pitch-deck/)
[![Licença](https://img.shields.io/badge/Licença-Proprietária%20%2F%20Confidencial-red?style=flat-square)](./LICENSE)

Repositório oficial de relações com investidores, tese de investimento e materiais de captação da plataforma **DriveSync** (SaaS Auto Catálogo).

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

## 📑 Estrutura do Repositório

```text
├── index.html                     # Apresentação interativa dos 12 slides (Tailwind CSS)
├── slides/
│   └── pitch_deck_drivesync.md    # Roteiro textual completo, notas de oratória e métricas
├── Sincronização DMS e Meta Ads.md # Benchmarks empíricos de CPL, CTR, CPC e conversão
├── Inventário Fantasma em Concessionárias.md # Diagnóstico técnico, latência de fim de semana e evasão orçamentária
├── .github/
│   └── workflows/
│       └── deploy-pages.yml       # Deploy automático no GitHub Pages a cada push na main
├── assets/                        # Diagramas, mockups e logotipos
└── financials/                    # Projeções de ARR, Unit Economics e Cap Table
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
