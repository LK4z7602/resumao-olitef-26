# Resumão Olitef 2026 - Nível 2 8º e 9º Anos

---

# MACROTEMA 01 — Educação Financeira Básica

## MT01 — Moeda e Sistema Financeiro Nacional (SFN)

### Evolução da moeda

1. **Escambo** — troca direta de mercadorias. Problema: exigia "dupla coincidência de desejos" (achar alguém que quisesse exatamente o que você tinha).
2. **Moeda-mercadoria** — um bem aceito como meio de troca (ex: **sal** → associado à origem da palavra **salário**).
3. **Moeda metálica** (ouro/prata) → **papel-moeda** → **meios de pagamento eletrônicos** (cartões, Pix).
4. **Pix** — sistema de pagamento **instantâneo**, permite transferências entre contas em segundos, 24h por dia, todos os dias.

### Estrutura do SFN (Sistema Financeiro Nacional) — ESSENCIAL, cai direto na prova

O SFN é dividido em **3 grupos de instituições**:

| Grupo            | Função                                                       | Exemplos                                                                                                                                                                                |
| ---------------- | ------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Normativos**   | **Definem as regras** do sistema                             | Conselho Monetário Nacional (CMN), Conselho Nacional de Seguros Privados (CNSP), Conselho Nacional de Previdência Complementar (CNPC)                                                   |
| **Supervisores** | **Fiscalizam** se as regras normativas estão sendo cumpridas | **Banco Central (BC)**, **Comissão de Valores Mobiliários (CVM)**, **Superintendência de Seguros Privados (Susep)**, **Superintendência Nacional de Previdência Complementar (Previc)** |
| **Operadores**   | **Ofertam** serviços financeiros diretamente à população     | Bancos, **B3**, corretoras de valores, cooperativas de crédito, seguradoras, administradoras de consórcio                                                                               |

> **Pegadinha clássica**: a **B3** atua como **operadora**, não como órgão supervisor. Quem supervisiona o mercado de valores mobiliários é a **CVM**. Não confunda os três grupos.

### Bancos e circulação do dinheiro

* Cada pessoa/empresa/governo pode ter uma conta = "endereço" do dinheiro.
* Quem tem dinheiro sobrando → guarda/investe no banco → pode receber juros.
* Banco capta recursos → empresta para pessoas e empresas → cobra juros. A diferença entre as taxas de captação e de empréstimo é um dos componentes do **spread bancário**.
* Fazem parte do SFN (como operadores): bancos, cooperativas de crédito, financeiras, administradoras de consórcio, seguradoras, corretoras de valores e a B3.

---

## MT02 — Matemática Financeira

### Operações básicas (revisão)

* Adição, subtração, multiplicação, divisão — usadas para somar gastos, calcular troco, ratear contas, etc.

### Comparação de preços — raciocínio cobrado na prova

Quando a prova compara "Loja A" x "Loja B", **calcule o custo total de tudo que a pessoa precisa comprar**, não apenas o preço do item principal.

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
> (O cálculo pode ser feito diretamente: 80 × 1,50 × 0,45 = R$54,00.)

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

* Juros simples (100, 1% a.m., 120 meses): 100 × (1 + 0,01×120) = **R$220,00**
* Juros compostos (mesmos dados): 100 × (1,01)^120 = **R$330,04**
* Quanto maior o prazo, maior tende a ser a diferença entre os dois — efeito "bola de neve".

### Juros embutidos em parcelamento

```
Total de juros = Valor total parcelado − Valor à vista
```

Ex: celular de R$1.000 à vista, ou 10x R$120 (R$1.200 total) → juros pagos = R$200,00.

### Amortização

* Cada parcela de um empréstimo pode ser dividida em **juros** + **amortização** (devolução do principal).
* Ex: empréstimo de R$1.000, pago total R$1.200,00 → R$200 correspondem aos juros e R$1.000 ao principal amortizado.
* Sistemas de amortização podem gerar parcelas iguais, crescentes ou decrescentes.

### Parcelado x à vista — critério de decisão

* **Errado**: escolher apenas pela parcela mais barata.
* **Certo**: comparar o **custo total** e, quando disponível, o **Custo Efetivo Total (CET)**.
* Se a pessoa **já tem o dinheiro guardado** para pagar à vista e o valor à vista é menor que o total parcelado, o pagamento à vista tem menor custo nominal. Porém, é preciso considerar o **custo de oportunidade**: o dinheiro poderia estar investido e rendendo.
* Quanto maior o prazo, **geralmente** maior o total de juros, embora isso dependa das condições do parcelamento.

---

## MT03 — Conceitos Básicos de Economia

### Taxa Selic Meta

* Taxa básica de juros da economia brasileira — importante referência para outras taxas de juros.
* **Definida pelo COPOM** (Comitê de Política Monetária, ligado ao Banco Central).
* O COPOM realiza **8 reuniões por ano**, em intervalos definidos no calendário oficial.
* **Sobe**, em geral, quando é necessário combater uma inflação elevada (encarece o crédito e tende a reduzir o consumo).
* **Desce**, em geral, quando há espaço para estimular a atividade econômica.

> Frase-modelo de prova: "A **Taxa Selic** é definida pelo **COPOM**. No geral, ela pode aumentar quando a **inflação** está elevada."

### Inflação

* **Aumento generalizado e persistente do nível de preços** ao longo de um período.
* Inflação alta = seu dinheiro perde poder de compra (compra menos com o mesmo valor).
* **Não confundir inflação com**: extorsão, deflação (queda geral do nível de preços), liquidação ou promoção (esses são fenômenos pontuais, não inflação).
* Índices de preços: **IPCA** (principal índice oficial de inflação, calculado pelo IBGE) e **IGP-M** (calculado pela FGV).

### PIB (Produto Interno Bruto)

* Mede o valor dos **bens e serviços finais produzidos** dentro do país em determinado período.
* O crescimento do PIB pode estar associado ao aumento da produção, da renda e dos investimentos, mas **não garante automaticamente** mais empregos, inovação ou redução da pobreza.
* PIB maior **pode** contribuir para maior arrecadação de impostos, mas isso não significa necessariamente maior investimento público.
* Serve para comparação da atividade econômica ao longo do tempo e entre países.

### Crescimento com responsabilidade

* Crescimento econômico pode ser acompanhado de distribuição de renda, acesso à educação/saúde e proteção ambiental — **crescimento sustentável**.

---

## MT04 — Finanças Pessoais

**Receita (de onde vem o dinheiro):** salário, rendas extras, aposentadoria, auxílios governamentais, pensões, aluguéis recebidos.

**Despesas:** moradia, comida, roupas, lazer etc.

**3 cenários de orçamento:**

| Cenário   | Situação        | Consequência                                                    |
| --------- | --------------- | --------------------------------------------------------------- |
| Empatando | Renda = Despesa | Não sobra dinheiro para imprevistos ou objetivos futuros        |
| Faltando  | Despesa > Renda | Precisa cortar gastos, buscar renda extra ou renegociar dívidas |
| Sobrando  | Renda > Despesa | Permite formar reserva de emergência e investir                 |

**Planejamento de longo prazo:** começar a investir cedo permite que os rendimentos tenham mais tempo para se acumular. Ex. de título voltado a isso: **Tesouro RendA+**.

---

# MACROTEMA 02 — Renda Fixa

## MT01 — Introdução à Renda Fixa

Investir em Renda Fixa = **emprestar dinheiro** para o governo (Tesouro Nacional), bancos, cooperativas ou empresas. A forma de remuneração depende do produto. Tem prazo de vencimento e regras de remuneração **definidas no momento da aplicação**.

### Tipos de remuneração — saiba identificar cada um

| Tipo           | Como identificar                                       | Exemplo                             |
| -------------- | ------------------------------------------------------ | ----------------------------------- |
| **Prefixado**  | Taxa fixa em % ao ano/mês, sem vínculo direto a índice | "paga 12,5% ao ano", "10% ao ano"   |
| **Pós-fixado** | Vinculado a uma taxa/índice que varia                  | "paga 110% do CDI", "100% da Selic" |
| **Híbrido**    | Combina uma parte ligada a um índice com uma taxa fixa | "IPCA + 6% ao ano"                  |

> Se o enunciado disser **"% do CDI"** → é **pós-fixado**.
> Se disser **um número fixo de % ao ano, sem referência a índice** → é **prefixado**.
> Se disser **"IPCA + X%"** → é **híbrido**: o IPCA acompanha a inflação e o "X%" é a taxa real contratada.

**Cuidado com pegadinha:** num título "IPCA + 6% ao ano" com IPCA do período em 5,5%:

* 5,5% = a **inflação do período** (não é taxa Selic nem CDI).
* 6% ao ano = a **taxa real contratada**, parte fixa da remuneração.
* **NÃO** existe informação sobre o CDI nesse título — CDI só aparece se o investimento estiver atrelado a ele.

### CDI (Certificado de Depósito Interbancário)

* Referência ligada às operações de empréstimos entre instituições financeiras.
* **Acompanha de perto a Taxa Selic**, mas não é a mesma coisa.
* A taxa DI é apurada em base diária nos dias úteis e é utilizada como referência para diversos investimentos.
* **CDI NÃO é índice de inflação.** Quem mede inflação são índices como IPCA e IGP-M.
* Um título que rende "150% do CDI" **não necessariamente** vai render mais que o IPCA sempre — depende do patamar de cada taxa no período.
* Rentabilidade pós-fixada expressa como % do CDI: 90%, 100%, 115% do CDI etc.

### Outros indexadores

| Sigla     | O que é                                                               |
| --------- | --------------------------------------------------------------------- |
| **IPCA**  | Índice de preços oficial de inflação, calculado pelo IBGE             |
| **IGP-M** | Índice de preços calculado pela FGV                                   |
| **Selic** | Taxa básica de juros da economia                                      |
| **TR**    | Taxa Referencial, utilizada, entre outros, na remuneração da poupança |

---

## MT02 — Produtos de Renda Fixa

### Rentabilidade x Risco

* Regra geral: quanto **maior o risco de crédito** de quem está pegando o dinheiro emprestado, **maior tende a ser a taxa de juros** exigida pelos investidores (é o "prêmio de risco").
* Ex: **empresas/bancos financeiramente menos estáveis apresentam MAIOR risco de não pagar (calote)** → por isso, em geral, precisam oferecer juros mais altos para atrair investidores.
* **Não existe investimento sem risco.** Riscos diferentes podem resultar em perdas diferentes; maior risco não significa necessariamente perder dinheiro.

### Os 3 tipos de risco

| Risco                 | O que é                                                                     | Como se protege / referência                                                                                                                                                           |
| --------------------- | --------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Risco de crédito**  | Chance de não receber de volta (o "calote")                                 | Tesouro Direto = risco de crédito muito baixo no contexto brasileiro. Alguns produtos bancários/cooperativos são cobertos pelo **FGC** ou **FGCoop**, dentro dos limites estabelecidos |
| **Risco de liquidez** | Dificuldade ou tempo necessário para transformar o investimento em dinheiro | Produtos com liquidez diária permitem resgate conforme as condições previstas; outros possuem prazo/carência                                                                           |
| **Risco de mercado**  | Oscilação do preço/valor do título antes do vencimento                      | Se vender por preço inferior ao de compra, pode haver perda. Se vender por preço superior, pode haver ganho                                                                            |

**Ranking de liquidez (do mais líquido para o menos líquido) — exemplo clássico de prova:**

```
Papel-moeda  >  CDB  >  Obras de arte
```

(dinheiro em espécie é altamente líquido; um CDB pode ter liquidez diária ou prazo/carência; uma obra de arte pode demorar meses/anos para vender).

**FGC/FGCoop:**

* **FGC** (Fundo Garantidor de Créditos) — cobre determinados depósitos e investimentos elegíveis de instituições associadas, até **R$250.000 por CPF/CNPJ por instituição ou conglomerado**, respeitando também o limite global de cobertura aplicável.
* **FGCoop** — sistema de proteção para determinados depósitos e investimentos em **cooperativas de crédito**, conforme suas regras e limites.
* O Tesouro Nacional **não utiliza FGC** — os títulos públicos são obrigações do próprio Tesouro Nacional.
* Título que empresta dinheiro para **banco** (ex: CDB) → pode ser coberto pelo **FGC**, se o produto for elegível.
* Título que empresta dinheiro para **empresa** (ex: debênture) → **NÃO** tem cobertura do FGC.

### Caderneta de Poupança

* Criada em 1861, durante o Segundo Reinado. Não paga Imposto de Renda para pessoa física sobre seus rendimentos.
* Regra de rendimento:

  * Selic Meta **> 8,5% a.a.** → poupança rende **0,5% ao mês + TR**
  * Selic Meta **≤ 8,5% a.a.** → poupança rende **70% da Selic Meta + TR**
* O rendimento é creditado conforme a **data de aniversário do depósito**, e não diariamente como ocorre na divulgação das taxas de alguns investimentos pós-fixados.

### Títulos Públicos (Tesouro Direto)

* Empresta dinheiro ao **Tesouro Nacional**. Possui risco de crédito muito baixo no contexto brasileiro e liquidez oferecida pelo programa, conforme suas regras.
* O valor mínimo depende do título; **não generalize R$1,00 para todos os títulos**.

| Título                | Característica                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Tesouro Selic**     | Pós-fixado, acompanha a Selic. Possui baixa sensibilidade às oscilações de mercado em comparação com outros títulos |
| **Tesouro Reserva**   | Rende 100% da Selic, possui liquidez imediata conforme as condições do produto e é voltado à reserva de emergência  |
| **Tesouro Prefixado** | Taxa fixa conhecida na compra, mas com risco de mercado se vender antes do vencimento                               |
| **Tesouro IPCA+**     | Híbrido (IPCA + taxa fixa), geralmente usado para objetivos de longo prazo                                          |
| **Tesouro Educa+**    | Híbrido, proporciona renda mensal por 5 anos a partir da data escolhida — voltado ao planejamento de estudos        |
| **Tesouro RendA+**    | Híbrido, proporciona renda mensal por 20 anos — voltado ao planejamento de aposentadoria                            |

### CDB (Certificado de Depósito Bancário)

* Empresta dinheiro para o **banco**, que devolve com juros.
* Pode ser coberto pelo FGC até os limites aplicáveis, se for um produto elegível.
* Se um banco A (menor risco) paga 10% ao ano, um banco B com **mais risco** pode precisar oferecer uma taxa **maior que 10%** para atrair investidores, como compensação pelo risco extra.
* Similares: **LCI** (Letra de Crédito Imobiliário), **LCA** (Letra de Crédito do Agronegócio), **RDB** (Recibo de Depósito Bancário).

### Debêntures

* Título emitido por **empresas**.
* Rentabilidade geralmente maior, MAS:

  * risco de crédito maior;
  * **NÃO tem cobertura do FGC**;
  * liquidez geralmente baixa.
* **Empresas financeiramente menos estáveis** (maior chance de não pagar) → podem precisar oferecer taxas mais altas para atrair investidores, compensando o risco extra de crédito.
* Algumas debêntures podem possuir **garantias específicas**, conforme as condições da emissão.

---

# MACROTEMA 03 — Renda Variável

## MT01 — Investindo em empresas

* Renda Variável = **investir em ativos cujo valor ou rendimento pode variar**.
* Comprar **ações** (participações em empresas negociadas na bolsa) → pode receber parte dos lucros por meio de **dividendos**, quando houver distribuição.
* Resultado **imprevisível** (depende do desempenho da empresa e do mercado).
* Ações geralmente são **sem prazo de vencimento** — preço e possíveis rendimentos variam ao longo do tempo.

---

## MT02 — Histórico do Mercado Financeiro

* **Bolsa de valores**: ambiente (hoje predominantemente eletrônico) que permite a negociação organizada de ativos.
* No Brasil: a **Bolsa de Valores do Rio de Janeiro (BVRJ)** foi uma das primeiras bolsas brasileiras, com origem em 1820; a bolsa do Rio teve grande importância histórica.
* **B3** (bolsa do Brasil, sede em São Paulo) — resultado de fusões:

  * **Bovespa** (bolsa de ações) + **BM&F** (Bolsa de Mercadorias & Futuros — negociava contratos de commodities, juros, câmbio etc.) → uniram-se em **2008**, formando a **BM&FBOVESPA**.
  * Fusão com a **CETIP** em **2017** → nasce a **B3**.

---

## MT03 — Ações e outros investimentos de Renda Variável

### Ibovespa B3

* Índice que mede o desempenho de uma **carteira teórica de ativos selecionados segundo critérios definidos pela B3**, principalmente ações e units.
* Calculado desde **1968**.
* **Principal índice/termômetro do mercado acionário brasileiro**.
* **Não confundir com**: IFIX B3 (índice de fundos imobiliários), índices de BDRs, índices de ETFs e IPCA (que mede inflação, não ações).

### Outros produtos de Renda Variável

| Produto                                     | O que é                                                                                                                                                   |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **FII (Fundo de Investimento Imobiliário)** | Fundo que investe em imóveis ou ativos ligados ao mercado imobiliário. Cotas podem ser negociadas na B3                                                   |
| **Fiagro**                                  | Fundo voltado a investimentos relacionados ao agronegócio                                                                                                 |
| **ETF (Fundo de Índice)**                   | Fundo cujas cotas são negociadas em bolsa e que busca acompanhar determinado índice ou estratégia. Pode proporcionar diversificação numa única operação   |
| **BDR (Brazilian Depositary Receipt)**      | Certificados negociados no Brasil que representam valores mobiliários emitidos ou lastreados em ativos de outros mercados, como ações e ETFs estrangeiros |

**Regras gerais de Renda Variável:**

* Maior potencial de retorno = **geralmente maior risco**.
* **Diversificação** pode reduzir o risco específico da carteira (conjunto de investimentos).
* É mais adequada para dinheiro que **não será necessário no curto prazo**, especialmente quando há possibilidade de oscilações de preço.

---

# RESUMO DE FÓRMULAS — cola final

```
Porcentagem:            % = parte ÷ total
Desconto:               Valor final = Valor original × (1 − taxa%)
Acréscimo:              Valor final = Valor original × (1 + taxa%)
Juros Simples:          Juros = Capital × taxa × tempo
Montante (simples):     Montante = Capital × (1 + taxa × tempo)
Montante (composto):    Montante = Capital × (1 + taxa)^tempo
Capital (composto):     Capital = Montante ÷ (1 + taxa)^tempo
Juros de parcelamento:  Juros = Valor total parcelado − Valor à vista
```

---

# TABELA-RESUMO: quem empresta pra quem, e qual garantia

| Investimento                                             | Emprestando para                  | Garantia                                                    | Risco de crédito                    |
| -------------------------------------------------------- | --------------------------------- | ----------------------------------------------------------- | ----------------------------------- |
| Tesouro Direto (Selic, Prefixado, IPCA+, Educa+, RendA+) | Governo (Tesouro Nacional)        | Obrigação do próprio Tesouro Nacional (não utiliza FGC)     | Muito baixo no contexto brasileiro  |
| Poupança, CDB, RDB, LCI, LCA                             | Bancos/cooperativas               | FGC/FGCoop, quando elegíveis, dentro dos limites aplicáveis | Depende da instituição e do produto |
| Debênture                                                | Empresas                          | **Sem FGC; pode possuir garantias específicas**             | Maior e varia conforme a empresa    |
| Ações, FII, Fiagro, ETF, BDR                             | Empresas/mercado (Renda Variável) | Não possuem FGC; preço pode flutuar                         | Variável, podendo ser alto          |

---

# ESTRUTURA DO SFN — quadro-resumo final

```
NORMATIVOS   → definem as regras     → CMN, CNSP, CNPC
SUPERVISORES → fiscalizam as regras  → Banco Central (BC), CVM, Susep, Previc
OPERADORES   → ofertam os serviços   → Bancos, B3, corretoras,
                                         cooperativas de crédito, seguradoras
```

### Conteúdo gerado e revisado por inteligência artificial - considere pesquisar temas importantes