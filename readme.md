# OLITEF 2026 — Conteúdo Programático Completo (Nível 2, 8º/9º ano)
### Sem enrolação. Só matéria, sigla, fórmula e exemplo resolvido.

---

# MACROTEMA 01 — Educação Financeira Básica

## MT01 — Moeda e Sistema Financeiro Nacional (SFN)

### Evolução da moeda
1. **Escambo** — troca direta de mercadorias. Problema: exigia "dupla coincidência de desejos" (achar alguém que quisesse exatamente o que você tinha).
2. **Moeda-mercadoria** — um bem aceito por todos como meio de troca (ex: **sal** → origem da palavra **salário**).
3. **Moeda metálica** (ouro/prata) → **papel-moeda** → **moeda eletrônica** (cartões, Pix).
4. **Pix** — sistema de pagamento **instantâneo**, transfere dinheiro entre contas em segundos, 24h por dia.

### Estrutura do SFN (Sistema Financeiro Nacional) — ESSENCIAL, cai direto na prova

O SFN é dividido em **3 grupos de instituições**:

| Grupo | Função | Exemplos |
|---|---|---|
| **Normativos** | **Definem as regras** do sistema | Conselho Monetário Nacional (CMN), Conselho Nacional de Seguros Privados (CNSP), Conselho Nacional de Previdência Complementar (CNPC) |
| **Supervisores** | **Fiscalizam** se as regras normativas estão sendo cumpridas | **Banco Central (BC)**, **Comissão de Valores Mobiliários (CVM)**, **Superintendência de Seguros Privados (Susep)**, **Superintendência Nacional de Previdência Complementar (Previc)** |
| **Operadores** | **Ofertam** os serviços financeiros diretamente à população | Bancos, **Bolsa de Valores (B3)**, corretoras de valores, cooperativas de crédito, seguradoras, administradoras de consórcio |

> ⚠️ **Pegadinha clássica**: Bolsa de Valores (B3) é **OPERADORA**, não supervisora. Quem supervisiona o mercado de valores mobiliários é a **CVM**. Não confunda os três grupos.

### Bancos e circulação do dinheiro
- Cada pessoa/empresa/governo tem uma conta = "endereço" do dinheiro.
- Quem tem dinheiro sobrando → guarda/investe no banco → recebe juros.
- Banco pega esse dinheiro → empresta para outra pessoa/empresa/governo → cobra juros (maiores que os pagos ao investidor — a diferença é o lucro do banco, chamado **spread bancário**).
- Fazem parte do SFN (como operadores): bancos, cooperativas de crédito, financeiras, administradoras de consórcio, seguradoras, corretoras de valores, bolsa de valores.

---

## MT02 — Matemática Financeira

### Operações básicas (revisão)
- Adição, subtração, multiplicação, divisão — usadas para somar gastos, calcular troco, ratear contas, etc.

### Comparação de preços — raciocínio cobrado na prova
Quando a prova compara "Loja A" x "Loja B", **calcule sempre o custo total de tudo que a pessoa precisa comprar**, não apenas o preço do item principal.
> Exemplo de raciocínio: se um videogame + 5 jogos custam R$1.200 na loja A, e na loja B o console custa R$880 + 5 jogos de R$63 cada (R$315 total) = R$1.195, a loja B é mais barata (R$1.195 < R$1.200), mesmo o console sozinho sendo mais barato lá.

### Porcentagem

```
% = parte ÷ total
```

**Desconto:**
```
Valor final = Valor original × (1 − taxa de desconto)
```

**Acréscimo:**
```
Valor final = Valor original × (1 + taxa de acréscimo)
```

**Aumentos e descontos sucessivos NÃO se cancelam nem se somam diretamente** — sempre aplique um fator de cada vez, multiplicando em sequência.
> Exemplo: um produto de R$80 sobe 50% (fica R$120,00) e depois tem 55% de desconto **sobre esse novo valor** (R$120): 
> R$120,00 × (1 − 0,55) = R$120,00 × 0,45 = **R$54,00**
> (Repare que NÃO é 80 × 1,50 × 0,45 direto sem calcular o valor intermediário corretamente — sempre resolva passo a passo: primeiro o aumento, depois o desconto sobre o valor já reajustado.)

### Juros Simples

```
Juros = Capital × taxa × tempo
Montante = Capital × (1 + taxa × tempo)
```

### Juros Compostos — o mais cobrado da prova

```
Montante = Capital × (1 + taxa)^tempo
```

**Cálculo direto (dado capital, ache o montante):**
Capital R$100, taxa 1% a.m., 6 meses:
Montante = 100 × (1,01)^6 = **R$106,15**

**Cálculo inverso (dado o montante, ache o capital) — MUITO cobrado:**
Se uma pessoa pagou **R$242,00** após **2 meses** com juros compostos de **10% ao mês**, qual foi o capital emprestado?

```
Montante = Capital × (1 + taxa)^tempo
242 = Capital × (1,10)^2
242 = Capital × 1,21
Capital = 242 ÷ 1,21 = R$200,00
```

> Sempre que a prova der o valor final e pedir o valor inicial (ou vice-versa), monte a equação `Montante = Capital × (1+i)^n` e isole o que falta.

**Comparação simples x composto no longo prazo:**
- Juros simples (100, 1% a.m., 120 meses): 100 × (1 + 0,01×120) = **R$220,00**
- Juros compostos (mesmos dados): 100 × (1,01)^120 = **R$330,04**
- Quanto maior o prazo, maior a vantagem (ou o perigo) dos juros compostos — efeito "bola de neve".

### Juros embutidos em parcelamento
```
Total de juros = Valor total parcelado − Valor à vista
```
Ex: celular de R$1.000 à vista, ou 10x R$120 (R$1.200 total) → juros pagos = R$200,00.

### Amortização
- Cada parcela de um empréstimo = **juros** + **amortização** (devolução do valor principal).
- Ex: empréstimo de R$1.000, pago total R$1.200,00 → R$200 são juros, R$1.000 é amortização.
- Sistema de Amortização pode gerar parcelas iguais, crescentes ou decrescentes — mas os juros sempre estão embutidos.

### Parcelado x à vista — critério de decisão
- **Errado**: escolher pela parcela mais barata.
- **Certo**: escolher pela **menor taxa de juros total**.
- Se a pessoa **já tem o dinheiro guardado** para pagar à vista e o valor à vista é menor que o total parcelado, **pagar à vista é sempre a opção mais barata** (a menos que o dinheiro parado renda mais investido do que os juros cobrados no parcelamento — mas isso é exceção rara e precisa ser calculado, não assumido).
- Quanto maior o prazo do parcelamento, maior o total de juros pagos, mesmo que a parcela pareça "caber melhor no bolso".

---

## MT03 — Conceitos Básicos de Economia

### Taxa Selic Meta
- Taxa básica de juros da economia brasileira — referência para todos os outros juros do país.
- **Definida pelo COPOM** (Comitê de Política Monetária, ligado ao Banco Central).
- Reunião a cada 45 dias (8x/ano).
- **Sobe** quando a inflação está **alta** (esfria o consumo, encarece crédito).
- **Desce** quando a inflação está controlada (estimula a economia).

> Frase-modelo de prova: "A **Taxa Selic** é definida pelo **COPOM**. No geral, ela aumenta quando a **inflação** está alta."

### Inflação
- **Aumento geral do nível de preços** em um período (geralmente 1 ano).
- Inflação alta = seu dinheiro perde poder de compra (compra menos com o mesmo valor).
- **Não confundir inflação com**: extorsão, deflação (queda geral de preços — o oposto), liquidação, promoção (esses são pontuais, não gerais).
- Indexadores de inflação: **IPCA** (índice oficial, calculado pelo IBGE) e **IGP-M** (calculado pela FGV).

### PIB (Produto Interno Bruto)
- Mede o valor total de tudo que é produzido (bens e serviços) dentro do país em 1 ano.
- **Positivamente correlacionado com o PIB** (sobem junto com ele): aumento da produção nacional, mais investimentos na economia, criação de empregos, geração de renda, inovação.
- **Negativamente correlacionado**: pobreza (tende a cair quando o PIB sobe).
- PIB em alta → mais arrecadação de impostos → mais investimento público.
- Serve para comparação ao longo do tempo e entre países.

### Crescimento com responsabilidade
- Crescimento econômico deve vir acompanhado de distribuição de renda, acesso à educação/saúde, e proteção ambiental — crescimento sustentável.

---

## MT04 — Finanças Pessoais

**Receita (de onde vem o dinheiro):** salário, rendas extras, aposentadoria, auxílios governamentais, pensões, aluguéis recebidos.

**Despesas:** moradia, comida, roupas, lazer etc.

**3 cenários de orçamento:**
| Cenário | Situação | Consequência |
|---|---|---|
| Empatando | Renda = Despesa | Problema futuro: preços sobem, dinheiro vai faltar |
| Faltando | Despesa > Renda | Precisa cortar gastos, buscar renda extra, renegociar dívidas |
| Sobrando | Renda > Despesa | Ideal: permite reserva de emergência, investimento, juros compostos a favor |

**Planejamento de longo prazo:** começar a investir cedo = juros compostos trabalhando mais tempo a seu favor. Ex de título voltado a isso: **Tesouro RendA+**.

---

# MACROTEMA 02 — Renda Fixa

## MT01 — Introdução à Renda Fixa

Investir em Renda Fixa = **emprestar dinheiro** para o governo (Tesouro Nacional), bancos, cooperativas ou empresas. Usa **juros compostos**. Tem prazo de vencimento e regra de remuneração **definida no momento da aplicação**.

### Tipos de remuneração — saiba identificar cada um

| Tipo | Como identificar | Exemplo |
|---|---|---|
| **Prefixado** | Taxa fixa em % ao ano/mês, sem vínculo a índice | "paga 12,5% ao ano", "10% ao ano" |
| **Pós-fixado** | Vinculado a um índice/taxa que muda (CDI, Selic) | "paga 110% do CDI", "100% da Selic" |
| **Híbrido** | Uma parte por índice de inflação + uma parte fixa (taxa real) | "IPCA + 6% ao ano" |

> Se o enunciado disser **"% do CDI"** → é **pós-fixado**.
> Se disser **um número fixo de % ao ano, sem referência a índice** → é **prefixado**.
> Se disser **"IPCA + X%"** → é **híbrido**: o IPCA é a parte pós-fixada (acompanha a inflação), e o "X%" é a **taxa real prefixada**.

**Cuidado com pegadinha:** num título "IPCA + 6% ao ano" com IPCA do período em 5,5%:
- 5,5% = a **inflação do período** (não é taxa Selic nem CDI).
- 6% ao ano = a **taxa prefixada** (taxa real, parte fixa do título).
- **NÃO** existe informação sobre o CDI nesse título — CDI só aparece em título pós-fixado atrelado a CDI.

### CDI (Certificado de Depósito Interbancário)
- Taxa de **empréstimo entre bancos** (bancos emprestam dinheiro entre si).
- **Acompanha de perto a Taxa Selic Meta** (não é a mesma coisa, mas segue "coladinho").
- Calculado **diariamente** (dias úteis) — títulos atrelados a ele rendem todo dia útil.
- ⚠️ **CDI NÃO é métrica de inflação.** Quem mede inflação é IPCA/IGP-M. Não confunda os dois.
- ⚠️ Um título que rende "150% do CDI" **não necessariamente** vai render mais que o IPCA sempre — depende do patamar de cada taxa no período. Não existe garantia automática de que um pós-fixado no CDI supere um índice de inflação.
- Rentabilidade pós-fixada expressa como % do CDI: 90%, 100%, 115% do CDI etc.

### Outros indexadores
| Sigla | O que é |
|---|---|
| **IPCA** | Índice de inflação oficial do Brasil (calculado pelo IBGE) |
| **IGP-M** | Índice de inflação calculado pela FGV |
| **Selic** | Taxa básica de juros da economia |
| **TR** | Taxa Referencial (usada na poupança) |

---

## MT02 — Produtos de Renda Fixa

### Rentabilidade x Risco
- Regra geral: quanto **maior o risco de crédito** de quem está pegando o dinheiro emprestado, **maior a taxa de juros** que precisa oferecer para atrair investidores (é o "prêmio de risco").
- Ex: **empresas/bancos financeiramente menos estáveis têm MAIOR risco de não pagar (calote)** → por isso **precisam pagar juros mais altos** para compensar esse risco e atrair quem for investir.
- Não existe ganho sem risco. Risco final = sempre "perder dinheiro".

### Os 3 tipos de risco

| Risco | O que é | Como se protege / referência |
|---|---|---|
| **Risco de crédito** | Chance de não receber de volta (o "calote") | Tesouro Direto = menor risco de crédito do Brasil. Bancos/cooperativas: cobertos pelo **FGC** (bancos) ou **FGCOOP** (cooperativas) até **R$250.000,00 por CPF** |
| **Risco de liquidez** | Tempo que demora pra resgatar o dinheiro | Liquidez diária = resgata quando quiser. Outros só em data específica |
| **Risco de mercado** | Oscilação do preço do título antes do vencimento | Se vender mais barato do que comprou, perde dinheiro. Visível em gráficos de rentabilidade |

**Ranking de liquidez (do mais líquido para o menos líquido) — exemplo clássico de prova:**
```
Papel-moeda  >  CDB  >  Obras de arte
```
(dinheiro em espécie é o mais líquido possível; um CDB tem prazo/carência; uma obra de arte pode demorar meses/anos para vender).

**FGC/FGCOOP:**
- **FGC** (Fundo Garantidor de Crédito) — cobre depósitos e investimentos em **bancos** até **R$250.000,00 por CPF**, em caso de calote/quebra da instituição.
- **FGCOOP** — mesma função, mas para **cooperativas de crédito**.
- O Tesouro Nacional **não precisa** de FGC — é garantido diretamente pelo governo (menor risco de crédito do país).
- Título que empresta dinheiro para **banco** (ex: CDB) → coberto pelo **FGC** até R$250.000,00.
- Título que empresta dinheiro para **empresa** (ex: debênture) → **NÃO** tem cobertura de FGC.

### Caderneta de Poupança
- Criada em 1861 (Dom Pedro II). Não paga Imposto de Renda sobre os juros.
- Regra de rendimento:
  - Selic Meta **> 8,5% a.a.** → poupança rende **0,5% ao mês + TR**
  - Selic Meta **≤ 8,5% a.a.** → poupança rende **70% da Selic Meta + TR**
- Rende a cada 30 dias (não diariamente, diferente dos pós-fixados atuais).

### Títulos Públicos (Tesouro Direto)
- Empresta dinheiro para o Tesouro Nacional. Menor risco de crédito do país, alta liquidez, mínimo de **R$1,00**.

| Título | Característica |
|---|---|
| **Tesouro Selic** | Pós-fixado, rende conforme a Selic diariamente. Risco de mercado muito baixo. |
| **Tesouro Reserva** | Rende 100% da Selic, resgate 24h/7 dias, ideal para reserva de emergência |
| **Tesouro Prefixado** | Taxa fixa conhecida na compra, ideal para médio prazo, mas com risco de mercado se vender antes |
| **Tesouro IPCA+** | Híbrido (IPCA + taxa fixa), ideal para longo prazo |
| **Tesouro Educa+** | Híbrido, renda mensal por 5 anos a partir de data escolhida — para custear estudos |
| **Tesouro RendA+** | Híbrido, renda mensal por 20 anos — para aposentadoria |

### CDB (Certificado de Depósito Bancário)
- Empresta dinheiro para o **banco**, que devolve com juros.
- Coberto pelo FGC até R$250.000,00.
- Se um banco A (menor risco) paga 10% ao ano, um banco B com **mais risco** precisa oferecer uma taxa **maior que 10%** para conseguir atrair investidores (compensação pelo risco extra).
- Similares: **LCI** (Letra de Crédito Imobiliário), **LCA** (Letra de Crédito do Agronegócio), **RDB** (Recibo de Depósito Bancário).

### Debêntures
- Título emitido por **empresas** (não bancos, não governo).
- Rentabilidade geralmente maior, MAS:
  - risco de crédito maior;
  - **NÃO tem cobertura do FGC**;
  - liquidez geralmente baixa.
- **Empresas financeiramente menos estáveis** (maior chance de não pagar) → **precisam oferecer taxas mais altas** para atrair investidores, compensando o risco extra de crédito.

---

# MACROTEMA 03 — Renda Variável

## MT01 — Investindo em empresas

- Renda Variável = **virar sócio de empresas**.
- Comprar **ações** (pedaços de empresas negociados na bolsa) → recebe parte do lucro via **dividendos**.
- Resultado **imprevisível** (depende do desempenho da empresa).
- Geralmente **sem prazo de vencimento** — preço e renda variam o tempo todo.

---

## MT02 — Histórico do Mercado Financeiro

- **Bolsa de valores**: ambiente (hoje eletrônico) que reúne pessoas para comprar/vender ações de forma organizada.
- No Brasil: primeira bolsa foi a **BVRJ** (Bolsa de Valores do Rio de Janeiro, 1851), destaque até os anos 1980.
- **B3** (bolsa do Brasil, sede em São Paulo) — resultado de fusões:
  - **Bovespa** (bolsa de ações) + **BM&F** (Bolsa de Mercadorias e Futuros — negociava contratos de commodities, juros, dólar) → uniram-se em **2008**, formando a **BM&FBOVESPA**.
  - Fusão com a **CETIP** (maior mercado de balcão organizado de Renda Fixa) em **2017** → nasce a **B3, a bolsa do Brasil**.

---

## MT03 — Ações e outros investimentos de Renda Variável

### Ibovespa B3
- Índice/média que mede o desempenho das ações das **maiores empresas** negociadas na B3.
- Calculado desde **1968**.
- **Principal índice/termômetro do mercado de ações brasileiro** — se as maiores empresas sobem, o Ibovespa fecha em alta.
- **Não confundir com**: IFIX B3 (índice de fundos imobiliários), índice de BDRs, índice de ETFs, IPCA (que é inflação, não ações).

### Outros produtos de Renda Variável

| Produto | O que é |
|---|---|
| **FII (Fundo de Investimento Imobiliário)** | Investe em imóveis (fundo de tijolo) ou títulos ligados a imóveis (fundo de papel). Cotas negociadas na B3. |
| **Fiagro** | Parecido com FII, mas voltado ao agronegócio. |
| **ETF (Fundo de Índice)** | Cotas negociadas na bolsa, replicam um índice (ex: Ibovespa). Compra uma "cesta" diversificada numa única operação. |
| **BDR (Brazilian Depositary Receipts)** | Recibos negociados na B3 que representam ações/ETFs/títulos de empresas **estrangeiras** (principalmente EUA). Permite investir fora do Brasil sem sair da B3. |

**Regras gerais de Renda Variável:**
- Maior potencial de retorno = maior risco.
- **Diversificação** reduz o risco da carteira (conjunto de investimentos).
- Indicado para dinheiro que **não** será usado no curto prazo.

---

# RESUMO DE FÓRMULAS — cola final

```
Porcentagem:            % = parte ÷ total
Desconto:                Valor final = Valor original × (1 − taxa%)
Acréscimo:               Valor final = Valor original × (1 + taxa%)
Juros Simples (total):   Juros = Capital × taxa × tempo
Montante (simples):      Montante = Capital × (1 + taxa × tempo)
Montante (composto):     Montante = Capital × (1 + taxa)^tempo
Capital (composto, inverso):  Capital = Montante ÷ (1 + taxa)^tempo
Juros de parcelamento:   Juros = Valor total parcelado − Valor à vista
```

---

# TABELA-RESUMO: quem empresta pra quem, e qual garantia

| Investimento | Emprestando para | Garantia | Risco de crédito |
|---|---|---|---|
| Tesouro Direto (Selic, Prefixado, IPCA+, Educa+, RendA+) | Governo (Tesouro Nacional) | Garantido pelo próprio Tesouro Nacional (não precisa de FGC) | Menor do país |
| Poupança, CDB, RDB, LCI, LCA | Bancos/cooperativas | FGC (bancos) / FGCOOP (cooperativas) até R$250.000/CPF | Baixo, mas depende do banco |
| Debênture | Empresas | **Nenhuma** (sem FGC) | Maior (varia por empresa) |
| Ações, FII, Fiagro, ETF, BDR | Empresas/mercado (Renda Variável) | Nenhuma — preço flutua | Alto, imprevisível |

---

# ESTRUTURA DO SFN — quadro-resumo final

```
NORMATIVOS   → definem as regras     → CMN, CNSP, CNPC
SUPERVISORES → fiscalizam as regras  → Banco Central (BC), CVM, Susep, Previc
OPERADORES   → ofertam os serviços   → Bancos, B3 (Bolsa de Valores), corretoras,
                                        cooperativas de crédito, seguradoras
```

### Conteúdo gerado e revisado por inteligência artificial - considere pesquisar temas importantes