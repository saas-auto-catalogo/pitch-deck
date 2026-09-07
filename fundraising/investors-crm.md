# 📊 CRM de Investidores — Pipeline de Captação DriveSync

Painel de governança do processo de captação. A fonte da verdade é o **[`pipeline-investidores.csv`](./pipeline-investidores.csv)** (52 registros: 36 anjos setoriais + 11 fundos + 5 redes/veículos); o presente documento define o **funil, as métricas e o ritmo de operação**.

## 1. Funil de captação (estágios)

| Estágio | Critério de entrada (Definition of Ready) | Próxima ação padrão | Meta de SLA |
|---|---|---|---|
| **Lead** | Nome identificado com tese de fit em potencial, sem validação setorial | Classificar perfil/tese e enriquecer contato | 48h |
| **Mapeado** | Inteligência preenchida no CSV: histórico, tese, ticket, canal (qualificado) | Disparar onda de abordagem (cadência de 3 toques) | 7 dias |
| **Abordagem Iniciada** | 1º toque enviado (InMail/WhatsApp/E-mail) e registrado | Cumprir cadência D+5 e D+12; registrar resposta | 15 dias |
| **Reunião de Pitch** | Investidor confirmou call (15–30 min) | Enviar deck + one-pager; preparar datas; registrar na agenda | 48h antes da call |
| **Due Diligence** | Investidor demonstrou interesse formal (reunião + pedido de matérias) | Montar data room (cap table, uso de recursos, contratos, LGPD) | 10 dias úteis |
| **Term Sheet / Alocação** | Term sheet (Mútuo Conversível) aprovado | Assinatura do instrumento e desembolso; atualizar cap table | 15 dias úteis |

> Regra de pipeline: **um estágio por registro** no CSV (coluna "Estágio no Funil"). Mover para trás no funil é permitido e deve ser anotado na coluna "Próxima Ação".

## 2. Métricas de acompanhamento (semanas Wk1 → Wk12)

| Métrica | Definição | Meta da rodada |
|---|---|---|
| **Contatos qualificados** | Registros "Mapeado" com canal preenchido | 40+ |
| **Fila de abordagem** | "Abordagem Iniciada" com 1º toque feito | 10/semana |
| **Taxa de resposta** | Respostas / toques enviados | ≥ 25% |
| **Reuniões de pitch** | Calls realizadas | ≥ 3/semana |
| **Conversão pitch → DD** | DD iniciada / calls | ≥ 30% |
| **Compromissos (commitments)** | Term sheets assinados | ≥ 10 (R$ 60k+ médio) |
| **Capital commitado / meta** | Valor total dos term sheets | R$ 600k (soft cap) → R$ 1M (target) |

**Dashboard sugerido (Wk1):** planilha derivada do CSV + coluna "Último Contato" e "Próximo Toque" (datas), filtrada por estágio.

## 3. Ritmo operacional

- **Segunda-feira:** revisão semanal do funil (mover estágios, limpar leads); definição da fila de 10 abordagens da semana.
- **Terça a quinta:** disparo dos toques (InMail/WhatsApp pela manhã, E-mail executivo à tarde); follow-ups D+5 e D+12.
- **Sexta-feira:** registro de métricas WkX, atualização do CSV e do dashboard; preparar agenda da semana seguinte.
- **Cadência:** no máximo **3 toques por investidor** sem resposta; depois disso, "Mapeado" com anotação de reativação (novo milestone de tração = novo gatilho).

## 4. Matriz de priorização (fit × ticket)

| Quadrante | Investidores | Estratégia |
|---|---|---|
| **Alta prioridade** (fit setorial alto + ticket ≥ R$ 200k) | Feldman, Caporal, Veras, Rocha, Assumpção, CAOA, Águia Branca, fundos Canary/Maya/DOMOVC | Toques personalizados Template 3 + warm intro; reuniões de pitch na 2ª quinzena |
| **Prioridade média** (fit médio ou ticket < R$ 200k) | Grande parte dos anjos setoriais; Bossa, Latitud, redes de anjos | Template 1/2 e 4; agendar ritos coletivos das redes |
| **Relacionamento de longo prazo** (checagem periódica) | Fusões/Fellows de anúncios, consultores, Instituto | Paive-se a reengajamento em marcos semestrais (Série A) |

## 5. Dados e privacidade

- **LGPD:** adotar base legal de execução de contrato/captação para tratamento de contatos; registrar consentimento no CSV e nunca compartilhar a base externamente.
- **Hygiene do CSV:** colunas obrigatórias sempre preenchidas (Nome, Perfil, Tese de Fit, Canal, Estágio, Próxima Ação); registrar datas de toque e resultados na narrativa da coluna "Próxima Ação".
- **Versão:** o CSV é o fonte única; o GitHub Pages não deve expor dados de contato pessoais sem consentimento — manter os arquivos deste diretório **fora do deploy público** ou sanitizados (ver `.github/workflows/deploy-pages.yml`).

## 6. Status atual da base (baseline Wk0)

- **Total:** 52 registros (36 anjos, 11 fundos, 4 redes + 1 veículo global FJ Labs).
- **Estágio dominante:** Mapeado (inteligência pronta para a 1ª onda de abordagem).
- **Exceção:** Sylvio de Barros registrado como legado histórico (Lead, "não abordar").
- **Próximo marco:** fila de 10 abordagens (Template 1/2) com anjos setoriais de baixo custo de acesso (ex-Webmotors/iCarros/99) na semana Wk1.

## 7. FAQ de respostas a investidores (piggy bank de argumentos)

| Pergunta típica | Resposta-âncora |
|---|---|
| Qual a barreira técnica vs. concorrentes? | Parser SAX multi-tenant + motor de diffs em tempo real sobre DMS legados (Neovibe, etc.); setup plug & play de 3 min sem substituir o DMS |
| Por que o lojista precisa disso? | Latência manual de 48h–72h queima até 28,8% do orçamento de mídia com inventário fantasma; prova: benchmarks de CPL/carro vendido |
| Como vocês defendem o negócio? | Integrações proprietárias de dados, embedded finance futuro (crédito/consórcio via leads), capilaridade de rede de concessionárias e rede de anjos setoriais como canal |
| O que os DMS legados impedem? | API restrita — nosso diferencial é o middleware de mapeamento e diffs; ver [`../Inventário Fantasma em Concessionárias.md`](../Inventário%20Fantasma%20em%20Concessionárias.md) |
| Vontade de co-investir com fundo? | rodada estruturada para permear anjos (R$ 25k cheque mínimo) e abrir espaço para fundo líder em Série A |

## 8. Integrações com este repositório

- [`pipeline-investidores.csv`](./pipeline-investidores.csv) — base do funil.
- [`teasers-outreach.md`](./teasers-outreach.md) — templates de abordagem (cadência de 3 toques).
- [`instrumento-investimento-safe-mutuo.md`](./instrumento-investimento-safe-mutuo.md) — termos da rodada (Mútuo Conversível, R$ 1M target).
- [`Investidores Anjo do Mercado Automotivo.md`](./Investidores%20Anjo%20do%20Mercado%20Automotivo.md) · [`Mapeamento Fundos SaaS B2B.md`](./Mapeamento%20Fundos%20SaaS%20B2B.md) — inteligência de mercado fonte.
- [`../exports/DriveSync-One-Pager.pdf`](../exports/DriveSync-One-Pager.pdf) · [`../exports/DriveSync-Pitch-Deck-2026.pdf`](../exports/DriveSync-Pitch-Deck-2026.pdf) — materiais de envio.