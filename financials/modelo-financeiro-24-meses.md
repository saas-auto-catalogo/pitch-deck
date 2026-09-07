# 📊 DriveSync — Modelo Financeiro & Projeção 24 Meses (Dataroom Pré-Seed)

> **Documento Oficial de Modelagem Financeira & Due Diligence**  
> **Rodada Pré-Seed:** R$ 1.000.000 (soft cap R$ 600.000) via Mútuo Conversível (LC 182/2021)  
> **Horizonte de Projeção:** 24 Meses (M01 a M24)  
> **Status:** Aprovado para Due Diligence com Investidores

---

## 🎯 1. Resumo Executivo & Indicadores-Chave (SaaS B2B)

A modelagem financeira da **DriveSync** reflete a transição da fase piloto/early-stage para escala comercial acelerada no mercado de concessionárias e revendas de veículos no Brasil (TAM de R$ 106M/ano; 45.000 lojas).

### Principais Marcos Conquistados no Modelo:
| Métrica-Chave | Mês 01 (Partida) | Mês 12 (Meta Intermediária) | Mês 24 (SOM Consolidado) | Benchmark de Mercado |
|---|---|---|---|---|
| **Clientes Pagantes Ativos** | 44 lojas | 469 lojas | **937 lojas** | SOM: 900 lojas |
| **Receita Recorrente Mensal (MRR)** | R$ 8.653,08 | R$ 101.478,80 | **R$ 233.347,30** | Meta M12: R$ 95k+ |
| **Receita Recorrente Anualizada (ARR)** | R$ 103.837,01 | R$ 1.217.745,61 | **R$ 2.800.167,61** | SOM: R$ 2,26M ARR |
| **Ticket Médio Mensal (ARPU)** | R$ 196,66 | R$ 216,37 | **R$ 249,04** | Expansão de planos |
| **Margem Bruta SaaS** | 82,3% | 89,7% | **91,5%** | Benchmark SaaS > 80% |
| **Churn de Logo Mensal** | 2,1% | 2,1% | **2,1%** | Teto projetado < 2,5% |
| **Net Revenue Retention (NRR)** | 106,2% anual | 106,2% anual | **106,2% anual** | Meta > 105% |
| **CAC Médio Ponderado (Blended)** | R$ 417,50 | R$ 417,50 | **R$ 417,50** | Target < R$ 450 |
| **LTV Médio por Cliente** | R$ 4.700,00 | R$ 4.900,00 | **R$ 5.400,00** | LTV/CAC > 10x |
| **Payback do CAC** | 2,2 meses | 2,1 meses | **2,0 meses** | Standard Seed < 12m |
| **Ponto de Equilíbrio (Break-Even EBITDA)** | Mês 11 (Operacional) | Positivo (+R$ 13,5k/mês) | **Lucrativo (+R$ 92,9k/mês)** | Eficiência de capital |
| **Consumo Máximo de Caixa (Valley)** | — | R$ 185.904,40 | R$ 185.904,40 | Aporte de R$ 1M intacto em >81% |

---

## 📦 2. Premissas de Aquisição por Plano e ARPU Dinâmico

O modelo de precificação é baseado em 3 faixas estruturadas de valor, alinhadas à capacidade de estoque e sofisticação da loja:

| Plano | Valor Mensal | Capacidade & Recursos | % Mix Novos Clientes | Impacto no Crescimento |
|---|---|---|---|---|
| **Starter** | **R$ 97,00 / mês** | Até 30 veículos, 1 feed XML Meta Ads, atualização diária | **35%** | Porta de entrada para revendas de bairro e lojistas independentes |
| **Pro (Carro-Chefe)** | **R$ 197,00 / mês** | Até 150 veículos, sincronização a cada 15 min, multi-feed e simulador Meta Ads | **50%** | Concessionárias médias e multimarcas ativas em tráfego pago |
| **Enterprise** | **R$ 397,00 / mês** | Veículos ilimitados, multi-loja/filiais, Google Vehicle Ads, SLA prioritário | **15%** | Redes de concessionárias (ex: CAOA, Saga, Águia Branca) e grandes revendas |

### Dinâmica de Expansão e ARPU:
- **ARPU Inicial de Entrada**: R$ 192,00 (média ponderada pura da entrada).
- **Evolução do ARPU**: Sobe para **R$ 216,37 no M12** e **R$ 249,04 no M24**, impulsionado por:
  1. *Up-sell* natural de revendas Starter que ampliam estoque e migram para Pro;
  2. Adoção do módulo complementar de **Google Vehicle Ads (GVA)** no Mês 7 em diante;
  3. Lojas adicionais de grupos econômicos consolidados no plano Enterprise.

---

## 🔄 3. Retenção de Clientes, Churn (< 2.5%) e Cohorts (NRR > 105%)

### Premissas de Retenção:
- **Churn Mensal de Logos**: **2,1% ao mês** (equivalente a uma perda média anualizada de ~22%, padrão superior para o segmento B2B automotivo cuja média gira entre 3,0% e 4,5%).
  - *Mitigadores de Churn*: A integração direta ao DMS torna o DriveSync infraestrutura crítica; desligar a ferramenta significa reintroduzir imediatamente o inventário fantasma e elevar o CPL em 47%.
- **Taxa de Expansão Mensal (Expansion MRR)**: **2,6% ao mês** sobre a base ativa existente (adoção de conectores extras, novos pátios e módulos adicionais).
- **Net Revenue Retention (NRR)**:
  $$\text{NRR Mensal} = 1 - 0{,}021 + 0{,}026 = 1{,}005 \implies 100{,}5\% \text{ ao mês}$$
  $$\text{NRR Anualizado} = (1{,}005)^{12} = 106{,}16\% > 105\%$$
  O crescimento da receita dentro da própria base de clientes existentes mais do que compensa o churn de receita (*Net Negative Churn* na ótica de expansão líquida).

---

## 📣 4. Mix de Canais de Aquisição & Modelagem de CAC

O Go-To-Market (GTM) é desenhado em torno de 3 motores complementares para garantir escalabilidade previsível e custo de aquisição controlado:

| Canal de Aquisição | Participação no Mix | CAC Unitário | Taxa Conv. Funil | Ciclo de Venda | Estratégia Operacional |
|---|---|---|---|---|---|
| **1. Inbound IA & SEO Especializado** | **40%** | **R$ 180,00** | 4,2% (Visitante ➔ Pago) | 7 dias | Artigos ultraespecíficos gerados pelo `ai-content-worker` focados em cauda longa ("feed XML Meta Ads concessionária", "sincronizar AutoCerto Meta DAA"), tráfego orgânico e Trial PLG de 14 dias sem cartão. |
| **2. Parcerias com Agências de Tráfego** | **35%** | **R$ 380,00** | 18,5% (Reunião ➔ Ativação) | 14 dias | Programa de Parceiros B2B2B com rev-share de 20%. As agências homologam a DriveSync em suas carteiras para eliminar o retrabalho manual de upload de catálogo. |
| **3. Outbound / Inside Sales SDR** | **25%** | **R$ 850,00** | 8,0% (SQL ➔ Contrato) | 28 dias | Prospecção ativa de redes de concessionárias autorizadas e grandes grupos automotivos via LinkedIn, bases Fenabrave e abordagem consultiva de inventário fantasma. |
| **MÉDIA PONDERADA (BLENDED)** | **100%** | **R$ 417,50** | **8,1%** | **14,7 dias** | **CAC Blended < R$ 450, gerando Payback de ~2,2 meses e LTV/CAC de 11,3x.** |

---

## 💰 5. Alocação do Capital Captado (Use of Proceeds — R$ 1.000.000)

Os recursos do Mútuo Conversível de R$ 1.000.000 serão alocados estrategicamente ao longo dos primeiros 18 a 24 meses:

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│                   ALOCAÇÃO DA RODADA PRÉ-SEED (R$ 1.000.000)                │
├────────────────────────────────┬──────────────────────────┬─────────────────┤
│ Frente Estratégica             │ % Alocação               │ Montante (R$)   │
├────────────────────────────────┼──────────────────────────┼─────────────────┤
│ 1. GTM & Vendas                │ 45,0%                    │ R$ 450.000,00   │
│ 2. Engenharia & Produto        │ 35,0%                    │ R$ 350.000,00   │
│ 3. Operações & Compliance      │ 10,0%                    │ R$ 100.000,00   │
│ 4. Reserva Estratégica (Caixa) │ 10,0%                    │ R$ 100.000,00   │
└────────────────────────────────┴──────────────────────────┴─────────────────┘
```

### Detalhamento por Frente:
1. **GTM & Vendas (45% — R$ 450.000)**:
   - Contratação de 2 SDRs e 2 AEs/Closers dedicados ao atendimento de agências e grupos de concessionárias;
   - Verba de mídia paga de atração para trials do inbound e presença institucional em eventos setoriais (ex: Congresso Fenabrave).
2. **Engenharia & Produto (35% — R$ 350.000)**:
   - Tech Lead + 2 Desenvolvedores Backend focados na escala do streaming parser SAX de XML de 50MB+;
   - Desenvolvimento dos conectores nativos para **Google Vehicle Ads (GVA)** e **TikTok Automotive Inventory Ads**;
   - Ampliação da biblioteca de conectores DMS (AutoCerto, Sisvag, Altimus, BomControle, Microvix, Linx DMS).
3. **Operações, Suporte & Compliance (10% — R$ 100.000)**:
   - 1 Especialista de Onboarding & Sucesso do Cliente (CS);
   - Adequação contínua LGPD, segurança da informação e auditoria jurídica societária da rodada.
4. **Reserva Estratégica de Caixa (10% — R$ 100.000)**:
   - Buffer de segurança contra oscilações de macroeconomia, assegurando mais de 24 meses de runway total ininterrupto.

---

## 📈 6. Tabela Consolidada Mês a Mês (24 Meses)

Tabela completa detalhando a progressão de base de clientes, receita, custos, despesas operacionais, EBITDA e saldo de caixa:

| Mês | Clientes Início | Novos | Churn | Clientes Fim | MRR Fim (R$) | ARR (R$) | Receita Líq (R$) | COGS (R$) | Margem Bruta (%) | Total OPEX (R$) | EBITDA (R$) | Saldo Caixa (R$) |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **M01** | 30 | 14 | 1 | **43** | R$ 8,446.80 | R$ 101,361.60 | R$ 7,939.99 | R$ 1,494.50 | 81.2% | R$ 31,500.00 | R$ -25,054.51 | **R$ 974,945.49** |
| **M02** | 43 | 18 | 1 | **60** | R$ 12,035.03 | R$ 144,420.41 | R$ 11,312.93 | R$ 1,690.00 | 85.1% | R$ 32,000.00 | R$ -22,377.07 | **R$ 952,568.42** |
| **M03** | 60 | 22 | 1 | **81** | R$ 16,229.21 | R$ 194,750.51 | R$ 15,255.46 | R$ 1,931.50 | 87.3% | R$ 33,000.00 | R$ -19,676.04 | **R$ 932,892.38** |
| **M04** | 81 | 28 | 2 | **107** | R$ 21,626.36 | R$ 259,516.26 | R$ 20,328.77 | R$ 2,230.50 | 89.0% | R$ 44,500.00 | R$ -26,401.73 | **R$ 906,490.65** |
| **M05** | 107 | 32 | 2 | **137** | R$ 27,938.49 | R$ 335,261.84 | R$ 26,262.18 | R$ 2,575.50 | 90.2% | R$ 46,000.00 | R$ -22,313.32 | **R$ 884,177.33** |
| **M06** | 137 | 38 | 3 | **172** | R$ 35,464.18 | R$ 425,570.15 | R$ 33,336.33 | R$ 2,978.00 | 91.1% | R$ 47,000.00 | R$ -16,641.67 | **R$ 867,535.66** |
| **M07** | 172 | 44 | 4 | **212** | R$ 44,209.50 | R$ 530,514.00 | R$ 41,556.93 | R$ 3,438.00 | 91.7% | R$ 61,500.00 | R$ -23,381.07 | **R$ 844,154.59** |
| **M08** | 212 | 49 | 4 | **257** | R$ 53,983.55 | R$ 647,802.57 | R$ 50,744.53 | R$ 3,955.50 | 92.2% | R$ 62,500.00 | R$ -15,710.97 | **R$ 828,443.63** |
| **M09** | 257 | 54 | 5 | **306** | R$ 64,591.47 | R$ 775,097.59 | R$ 60,715.98 | R$ 4,519.00 | 92.6% | R$ 64,000.00 | R$ -7,803.02 | **R$ 820,640.60** |
| **M10** | 306 | 58 | 6 | **358** | R$ 76,140.42 | R$ 913,685.07 | R$ 71,572.00 | R$ 5,117.00 | 92.9% | R$ 73,000.00 | R$ -6,545.00 | **R$ 814,095.60** |
| **M11** | 358 | 62 | 8 | **412** | R$ 88,335.13 | R$ 1,060,021.50 | R$ 83,035.02 | R$ 5,738.00 | 93.1% | R$ 74,500.00 | R$ 2,797.02 | **R$ 816,892.62** |
| **M12** | 412 | 66 | 9 | **469** | R$ 101,478.80 | R$ 1,217,745.61 | R$ 95,390.07 | R$ 6,393.50 | 93.3% | R$ 75,500.00 | R$ 13,496.57 | **R$ 830,389.19** |
| **M13** | 469 | 45 | 10 | **504** | R$ 110,651.19 | R$ 1,327,814.34 | R$ 101,799.10 | R$ 6,796.00 | 93.3% | R$ 92,000.00 | R$ 3,003.10 | **R$ 833,392.29** |
| **M14** | 504 | 46 | 11 | **539** | R$ 120,066.45 | R$ 1,440,797.41 | R$ 110,461.13 | R$ 7,198.50 | 93.5% | R$ 92,500.00 | R$ 10,762.63 | **R$ 844,154.93** |
| **M15** | 539 | 48 | 11 | **576** | R$ 129,822.78 | R$ 1,557,873.39 | R$ 119,436.96 | R$ 7,624.00 | 93.6% | R$ 93,500.00 | R$ 18,312.96 | **R$ 862,467.89** |
| **M16** | 576 | 50 | 12 | **614** | R$ 139,921.90 | R$ 1,679,062.76 | R$ 128,728.15 | R$ 8,061.00 | 93.7% | R$ 94,000.00 | R$ 26,667.15 | **R$ 889,135.03** |
| **M17** | 614 | 52 | 13 | **653** | R$ 150,665.51 | R$ 1,807,986.08 | R$ 138,612.27 | R$ 8,509.50 | 93.9% | R$ 95,000.00 | R$ 35,102.77 | **R$ 924,237.80** |
| **M18** | 653 | 53 | 14 | **692** | R$ 161,559.83 | R$ 1,938,718.01 | R$ 148,635.05 | R$ 8,958.00 | 94.0% | R$ 95,500.00 | R$ 44,177.05 | **R$ 968,414.84** |
| **M19** | 692 | 55 | 15 | **732** | R$ 172,902.63 | R$ 2,074,831.60 | R$ 159,070.42 | R$ 9,418.00 | 94.1% | R$ 106,500.00 | R$ 43,152.42 | **R$ 1,011,567.27** |
| **M20** | 732 | 56 | 15 | **773** | R$ 184,399.15 | R$ 2,212,789.75 | R$ 169,647.21 | R$ 9,889.50 | 94.2% | R$ 107,000.00 | R$ 52,757.71 | **R$ 1,064,324.98** |
| **M21** | 773 | 57 | 16 | **814** | R$ 196,350.14 | R$ 2,356,201.70 | R$ 180,642.13 | R$ 10,361.00 | 94.3% | R$ 108,000.00 | R$ 62,281.13 | **R$ 1,126,606.11** |
| **M22** | 814 | 58 | 17 | **855** | R$ 208,557.89 | R$ 2,502,694.71 | R$ 191,873.26 | R$ 10,832.50 | 94.4% | R$ 108,500.00 | R$ 72,540.76 | **R$ 1,199,146.87** |
| **M23** | 855 | 59 | 18 | **896** | R$ 220,723.68 | R$ 2,648,684.18 | R$ 203,065.79 | R$ 11,304.00 | 94.4% | R$ 109,500.00 | R$ 82,261.79 | **R$ 1,281,408.66** |
| **M24** | 896 | 60 | 19 | **937** | R$ 233,347.30 | R$ 2,800,167.61 | R$ 214,679.52 | R$ 11,775.50 | 94.5% | R$ 110,000.00 | R$ 92,904.02 | **R$ 1,374,312.68** |

---

## 🔬 7. Análise de Sensibilidade & Cenários de Estresse

Para avaliar a resiliência do modelo em cenários adversos, foram simuladas 3 hipóteses:

| Indicador | Cenário Conservador (-25% Tração) | **Cenário Base (Projetado)** | Cenário Otimista (+25% Aceleração) |
|---|---|---|---|
| **Clientes Ativos no M12** | 350 lojas | **469 lojas** | 585 lojas |
| **Clientes Ativos no M24** | 700 lojas | **937 lojas** | 1.170 lojas |
| **MRR no M24** | R$ 174.000,00 | **R$ 233.347,30** | R$ 291.500,00 |
| **ARR no M24** | R$ 2,08M ARR | **R$ 2,80M ARR** | R$ 3,50M ARR |
| **Consumo Máximo de Caixa** | R$ 320.000,00 | **R$ 185.904,40** | R$ 120.000,00 |
| **Mês do Break-Even Operacional** | Mês 15 | **Mês 11** | Mês 09 |
| **Runway Disponível com R$ 1M** | 28 meses | **> 36 meses (Autossustentável)** | **Indefinido (Livre Geração)** |

> 📌 **Conclusão para Investidores**: Mesmo sob o estresse do cenário conservador (-25% de conversão comercial), o aporte de R$ 1.000.000 oferece folga de caixa superior a 28 meses, sem qualquer risco de insolvência antes do atingimento do break-even.

---

## 🔒 8. Governança do Dataroom & Acesso Seguro

- **Repositório Oficial**: [github.com/saas-auto-catalogo/pitch-deck/tree/main/financials](https://github.com/saas-auto-catalogo/pitch-deck/tree/main/financials)
- **Planilha Universal de Dados**: [`drivesync-projecao-financeira-24m.csv`](./drivesync-projecao-financeira-24m.csv) (delimitador `;`, padrão compatível com MS Excel, Apple Numbers e Google Sheets)
- **Matriz de Unit Economics**: [`unit-economics-e-canais.csv`](./unit-economics-e-canais.csv)
- **Plano de Headcount e Alocação**: [`alocacao-capital-headcount.csv`](./alocacao-capital-headcount.csv)
- **Responsável Financeiro**: Relações com Investidores (contato@drivesync.com.br)
