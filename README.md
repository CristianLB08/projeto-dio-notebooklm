# projeto-dio-notebooklm
Neste projeto prático, você vai aliar pensamento crítico, curadoria de fontes e organização do conhecimento para criar um Caderno Temático no NotebookLM.

Perfeito — você já fez a parte mais difícil (coletar fontes e usar o NotebookLM). Agora o que falta é **transformar isso em um projeto bem estruturado no GitHub** que impressione quem avaliar 👇

Vou te guiar como se fosse um checklist prático.

---

# 📌 1. Contexto e Objetivos

Aqui você explica:

👉 O que são Ondas de Elliott
👉 Por que escolheu esse tema
👉 O que quer aprender

### Exemplo (pode adaptar):

* Entender como funcionam as Ondas de Elliott no mercado financeiro
* Identificar padrões de impulsão e correção
* Aplicar o conceito em análise técnica
* Usar IA para organizar e aprofundar o conhecimento

---

# 📚 2. Curadoria de Fontes

## 🎥 Vídeos

* [https://www.youtube.com/watch?v=niyhE28JZJA](https://www.youtube.com/watch?v=niyhE28JZJA)
* [https://www.youtube.com/watch?v=4oVYF60GcOo](https://www.youtube.com/watch?v=4oVYF60GcOo)
* [https://www.youtube.com/watch?v=ceQzPskjbKg](https://www.youtube.com/watch?v=ceQzPskjbKg)
* [https://www.youtube.com/watch?v=G2Ba-Xr70TI](https://www.youtube.com/watch?v=G2Ba-Xr70TI)
* [https://www.youtube.com/watch?v=2gVJOmu-6tQ](https://www.youtube.com/watch?v=2gVJOmu-6tQ)

## 📖 Artigos

* [https://cmcapital.com.br/blog/ondas-de-elliott/](https://cmcapital.com.br/blog/ondas-de-elliott/)
* [https://www.investopedia.com/terms/e/elliottwavetheory.asp](https://www.investopedia.com/terms/e/elliottwavetheory.asp)
* [https://blog.nelogica.com.br/ondas-de-elliott-de-forma-facil-e-pratica/](https://blog.nelogica.com.br/ondas-de-elliott-de-forma-facil-e-pratica/)
* [https://coinext.com.br/blog/ondas-de-elliot](https://coinext.com.br/blog/ondas-de-elliot)
* [https://blog.toroinvestimentos.com.br/trading/ondas-de-elliott/](https://blog.toroinvestimentos.com.br/trading/ondas-de-elliott/)

---

# 🤖 3. Engenharia de Prompts + "Cicatrizes"

## Exemplo de estrutura:

### 🔹 Prompt 1 (simples)

> "Explique ondas de Elliott"
> "A Teoria das Ondas de Elliott é uma metodologia de análise técnica desenvolvida por **Ralph Nelson Elliott** na década de 1930, que interpreta os movimentos dos preços nos mercados financeiros como padrões repetitivos chamados "ondas". Esta teoria baseia-se na premissa de que os mercados não se movem de forma aleatória, mas seguem ciclos impulsionados pela **psicologia das massas**, oscilando entre o otimismo (euforia) e o pessimismo (pânico).

Abaixo estão os conceitos fundamentais para entender as ondas de Elliott:

### 1. A Estrutura Básica (Ciclo 5-3)
Um ciclo completo de mercado, segundo Elliott, consiste em **oito ondas** divididas em duas fases principais:
*   **Fase de Impulso (Motriz):** Composta por **cinco ondas** (numeradas de 1 a 5) que se movem na direção da tendência principal. As ondas 1, 3 e 5 são de avanço, enquanto as ondas 2 e 4 são pequenas correções internas.
*   **Fase Corretiva:** Composta por **três ondas** (letras A, B e C) que se movem contra a tendência anterior, corrigindo o movimento das cinco ondas iniciais.

### 2. As Três Regras Inegociáveis
Para que uma contagem de ondas de impulso seja considerada válida, ela deve respeitar rigorosamente três regras:
1.  **Regra da Onda 2:** A onda 2 nunca pode retrair mais de 100% da onda 1 (ou seja, não pode ultrapassar o início da onda 1).
2.  **Regra da Onda 3:** Entre as ondas de impulso (1, 3 e 5), a **onda 3 nunca pode ser a menor** delas. Frequentemente, ela é a mais longa e poderosa.
3.  **Regra da Onda 4:** A onda 4 não pode entrar no território de preço da onda 1 (exceto em formações raras chamadas triângulos diagonais).

### 3. Natureza Fractal e Graus de Onda
A teoria é **fractal**, o que significa que os padrões se repetem em todas as escalas de tempo. Uma única onda de um gráfico diário pode ser decomposta em cinco ondas menores em um gráfico de 1 hora. Elliott identificou nove graus de ondas, desde o "Grand Supercycle" (que dura séculos) até o "Subminuette" (que dura minutos).

### 4. Relação com Fibonacci
As ondas de Elliott estão profundamente ligadas à **sequência de Fibonacci** para prever alvos de preço e níveis de correção. 
*   **Retrações:** A onda 2 costuma corrigir entre **50% e 61,8%** da onda 1. A onda 4 geralmente corrige cerca de **38,2%** da onda 3.
*   **Extensões:** A onda 3 frequentemente atinge **161,8%** (a Razão Áurea) ou mais do comprimento da onda 1.

### 5. Personalidade das Ondas
Cada onda reflete um estado emocional do mercado:
*   **Onda 1:** Frequentemente difícil de identificar, pois surge após uma tendência de baixa, cercada de ceticismo.
*   **Onda 3:** É a **onda do dinheiro**. É o movimento mais forte, com alto volume e participação clara dos investidores.
*   **Onda 5:** O empurrão final. É marcada por otimismo extremo, mas muitas vezes apresenta **divergências** em indicadores como o RSI ou MACD, sinalizando que a tendência está perdendo força.
*   **Ondas Corretivas (ABC):** Podem assumir formas variadas, como **Ziguezagues** (fortes correções), **Flats** (movimentos laterais) ou **Triângulos** (consolidação antes de um novo impulso)."

📉 Problema:
Resposta muito genérica.

---

### 🔹 Prompt 2 (melhorado)

> "Explique as Ondas de Elliott com exemplos práticos e linguagem simples"
> "A Teoria das Ondas de Elliott é um modelo de análise técnica que interpreta os movimentos do mercado como padrões repetitivos baseados na **psicologia das massas**, oscilando entre o otimismo e o pessimismo. Ralph Nelson Elliott descobriu que os preços não se movem de forma aleatória, mas seguem um ritmo natural de **cinco ondas a favor da tendência** e **três ondas contra ela**.

### 1. A Estrutura Básica (Ciclo 5-3)
O ciclo completo de mercado é composto por oito ondas principais:
*   **Fase de Impulso (1, 2, 3, 4, 5):** São as ondas que "empurram" o mercado na direção principal. As ondas 1, 3 e 5 são de avanço, enquanto a 2 e a 4 são pequenas pausas.
*   **Fase Corretiva (A, B, C):** Ocorre após o impulso, funcionando como um "respiro" do mercado antes de retomar a tendência.

### 2. As Três Regras Inegociáveis
Para que uma contagem de ondas de impulso seja válida, ela deve respeitar rigorosamente estas regras:
1.  **Regra da Onda 2:** A onda 2 nunca pode cair abaixo do ponto onde a onda 1 começou.
2.  **Regra da Onda 3:** Entre as ondas de impulso (1, 3 e 5), a **onda 3 nunca pode ser a menor** de todas; ela é geralmente a mais longa e poderosa.
3.  **Regra da Onda 4:** A onda 4 não pode entrar no território de preço ocupado pela onda 1 (exceto em formações raras chamadas triângulos diagonais).

### 3. Exemplos Práticos e Personalidade das Ondas
Cada fase reflete uma emoção humana diferente:
*   **Onda 1 (Início):** É difícil de identificar porque surge no meio de notícias ruins, quando poucos acreditam na reversão.
*   **Onda 3 (A "Onda do Dinheiro"):** É o movimento mais forte e fácil de reconhecer. **Exemplo prático:** No gráfico do **Bitcoin**, o rompimento de um topo anterior após uma queda prolongada costuma marcar o início de uma Onda 3 poderosa, onde o volume financeiro explode e as instituições entram comprando pesado.
*   **Onda 5 (Euforia final):** O preço sobe com otimismo extremo, mas com menos força que a onda 3.
*   **Onda C (O Desespero):** É a fase final da correção, onde o medo toma conta e o preço cai de forma devastadora.

### 4. A Natureza Fractal (O Brócolis do Mercado)
As ondas de Elliott são **fractais**, o que significa que o padrão se repete em qualquer escala de tempo. Uma comparação simples é com um **brócolis**: se você destacar um pequeno pedaço dele, ele terá o mesmo formato da cabeça de brócolis inteira. Da mesma forma, uma onda "mestra" de um gráfico diário é composta por várias ondas menores de 5 e 15 minutos que seguem o mesmo desenho.

### 5. Como usar com Fibonacci
Traders usam a ferramenta de Fibonacci para prever até onde o preço pode ir:
*   **Entrada:** A **Onda 2** costuma recuar entre **50% e 61,8%** do tamanho da Onda 1, oferecendo uma ótima oportunidade de compra para surfar a Onda 3.
*   **Alvo:** A **Onda 3** frequentemente atinge **161,8%** (a Razão Áurea) do comprimento da Onda 1."

✅ Resultado:
Mais didático, porém ficou mais superficial.

---

### 🔹 Prompt 3 (refinado)

> "Explique detalhadamente as 5 ondas de impulso e 3 de correção, com exemplos aplicados ao mercado financeiro"
> "A Teoria das Ondas de Elliott propõe que o mercado financeiro se move em ciclos repetitivos de **oito ondas**, compostos por uma **fase motriz de cinco ondas** que seguem a tendência principal e uma **fase corretiva de três ondas** que se movem contra ela. Esses padrões são fractais, o que significa que cada onda pode ser subdividida em ondas menores que seguem a mesma estrutura.

### As 5 Ondas de Impulso (Fase Motriz)
As ondas de impulso (numeradas de 1 a 5) são responsáveis pelo progresso direcional do mercado. Elas devem seguir três regras básicas e inegociáveis para serem consideradas válidas: a **Onda 2** nunca pode retrair mais de 100% da Onda 1; a **Onda 3** nunca pode ser a menor das ondas impulsivas (1, 3 e 5); e a **Onda 4** não pode entrar no território de preço da Onda 1 (exceto em formações raras chamadas diagonais).

*   **Onda 1 (Início):** É frequentemente difícil de identificar no começo, pois surge após uma tendência de baixa e as notícias fundamentais ainda costumam ser negativas. Ela representa o primeiro movimento de acumulação por investidores institucionais.
*   **Onda 2 (Retração):** Corrige a Onda 1 através de uma venda por investidores céticos que acreditam que a tendência anterior voltará. Ela costuma retrair entre **50% e 61,8%** da Onda 1, mas nunca deve ultrapassar o seu início.
*   **Onda 3 (A "Onda do Dinheiro"):** É geralmente a mais forte, longa e dinâmica de todo o ciclo. Neste ponto, a confiança retorna, o volume aumenta e a maioria dos investidores reconhece a nova tendência, resultando em rompimentos de topos e gaps de alta.
*   **Onda 4 (Consolidação):** É uma fase de realização de lucros e movimento lateral, frequentemente frustrante pela falta de progresso. Pela **regra da alternância**, se a Onda 2 foi rápida e profunda, a Onda 4 tende a ser lateral, complexa e rasa, raramente corrigindo mais de 38,2% da Onda 3.
*   **Onda 5 (Euforia Final):** Representa o último empurrão na direção da tendência. Embora os preços atinjam novos máximos, o volume e o ímpeto costumam ser menores do que na Onda 3, resultando em **divergências** em indicadores como o RSI.

### As 3 Ondas de Correção (Fase Corretiva)
As correções são rotuladas pelas letras **A, B e C** e servem para neutralizar os excessos da fase de impulso. Elas são mais variadas e complexas do que as ondas motrizes.

*   **Onda A:** É o primeiro sinal de fraqueza da tendência, mas muitos investidores a confundem com um simples recuo antes de novas altas. Ela pode ter uma estrutura de 5 sub-ondas (em um **Ziguezague**) ou 3 sub-ondas (em um **Flat**).
*   **Onda B (Armadilha de Touros):** É um rali enganoso que dá a falsa esperança de que a tendência original foi retomada. Ela apresenta volume baixo e geralmente não supera o topo da Onda 5 (exceto em flats expandidos).
*   **Onda C (Capitulação):** É a fase final da correção, onde as ilusões de alta desaparecem e o medo domina o mercado. A Onda C é quase sempre um movimento impulsivo de 5 ondas e costuma ser devastadora em sua queda.

### Exemplos Aplicados ao Mercado Financeiro
1.  **Bitcoin (BTC):** No gráfico diário, o rompimento de um topo válido após uma queda prolongada pode marcar o início de uma Onda 3 poderosa, como ocorreu quando o preço superou consolidações históricas com explosão de volume.
2.  **Ações da Reliance Industries:** O ativo demonstrou um padrão clássico de 5 ondas de impulso em gráficos mensais, onde a Onda 3 foi claramente a mais longa e evidente, permitindo que traders antecipassem a reversão na Onda 4.
3.  **Café (Commodities):** A explosão de preços do café entre 1975 e 1977 seguiu um padrão Elliott inconfundível, onde a Onda 3 atingiu alvos precisos de Fibonacci de 1,618 em relação à Onda 1 antes de uma correção severa.
4.  **Índice Bovespa (IBOV):** Em movimentos de alta prolongada, o índice costuma formar Ondas 4 laterais que duram meses, alternando com Ondas 2 que foram rápidas correções em formato de "V", respeitando o princípio da alternância.
5.  **Ouro:** Durante crises de confiança no dólar, o ouro formou impulsos de 5 ondas com a **Onda 5 estendida**, refletindo a psicologia do pânico e da busca por proteção (fear extension), comum em commodities."

🔥 Resultado:
Resposta completa e útil.

---

### 💡 Dificuldades encontradas

* IA respondia de forma superficial
* Falta de exemplos reais
* Necessidade de refinar prompts

---

# 📘 4. Miniguia de Estudo (ENTREGA FINAL)

---

## 🧠 4.1 Resumo Estruturado

### 📊 O que são Ondas de Elliott?

As **Ondas de Elliott** são uma metodologia de análise técnica desenvolvida por Ralph Nelson Elliott na década de 1930, que sugere que os mercados financeiros se movem em padrões repetitivos chamados "ondas". Essa teoria baseia-se na premissa de que os preços não flutuam de forma aleatória, mas refletem a **psicologia das massas**, oscilando entre ciclos naturais de otimismo e pessimismo dos investidores.

---

### 📈 Estrutura das Ondas

A estrutura fundamental da Teoria das Ondas de Elliott é baseada em um ciclo completo de **oito ondas**, conhecido como o **padrão 5-3**. Este ciclo é composto por duas fases distintas:

*   **Fase Motriz (Impulso):** Consiste em **cinco ondas** (numeradas de 1 a 5) que se movem na direção da tendência principal. Dentro desta fase, as ondas 1, 3 e 5 são os motores do movimento, enquanto as ondas 2 e 4 atuam como pausas ou interrupções de contratendência.
*   **Fase Corretiva:** Segue-se ao impulso e é composta por **três ondas** (letras A, B e C) que se movem contra a tendência de grau maior para ajustar os excessos anteriores.

### Regras Inegociáveis das Ondas de Impulso
Para que uma contagem de ondas seja considerada válida, ela deve respeitar rigorosamente três regras:
1.  **Regra da Onda 2:** A onda 2 nunca pode retrair mais de 100% da onda 1 (não ultrapassa o início da onda 1).
2.  **Regra da Onda 3:** Entre as ondas de impulso (1, 3 e 5), a **onda 3 nunca pode ser a menor**; ela é frequentemente a mais longa e poderosa.
3.  **Regra da Onda 4:** A onda 4 não pode entrar no território de preço da onda 1 (não há sobreposição), exceto em formações raras chamadas triângulos diagonais.

### Natureza Fractal e Graus de Onda
A teoria postula que o mercado é **fractal**, o que significa que os padrões se repetem em todas as escalas de tempo. Uma onda de um ciclo maior é composta por ondas menores de um grau inferior que seguem a mesma estrutura de 5 e 3 ondas. Elliott identificou **nove graus de ondas**, desde o "Grand Supercycle" (que dura séculos) até o "Subminuette" (que dura minutos).

### Psicologia e Personalidade das Ondas
A estrutura das ondas é a manifestação física da **psicologia das massas**.
*   **Onda 1:** Difícil de identificar no início, surgindo em meio a notícias negativas.
*   **Onda 3:** É o movimento mais forte e dinâmico, onde a maioria dos investidores reconhece a nova tendência; geralmente apresenta o **maior volume**.
*   **Onda 5:** O empurrão final, marcado por otimismo extremo, mas com momentum perdendo força.
*   **Ondas A-B-C:** A onda B é frequentemente uma "armadilha para touros" (bull trap), enquanto a onda C é uma queda devastadora e persistente que confirma a correção.

---

### 🔺 Ondas de Impulso (1–5)

As **Ondas de Impulso** (também chamadas de ondas motrizes) formam a estrutura que impulsiona o mercado na direção da tendência principal. Esse padrão é composto por **cinco ondas**, numeradas de 1 a 5, onde as ondas 1, 3 e 5 são as que avançam no sentido da tendência, enquanto as ondas 2 e 4 servem como interrupções ou correções internas.

### **Onda 1: O Início e Acúmulo**
*   **Características:** É o início de um novo movimento e costuma ser a onda mais **difícil de identificar** em tempo real. Geralmente surge após um período de baixa, quando as notícias fundamentais ainda são negativas e a maioria dos investidores continua pessimista.
*   **Psicologia:** Representa um leve aumento na confiança de um pequeno grupo de investidores que acredita na reversão da tendência.
*   **Estrutura Interna:** Como é uma onda motriz, ela se subdivide internamente em cinco ondas menores de um grau inferior.

### **Onda 2: A Retração e o Ceticismo**
*   **Características:** Funciona como uma resposta corretiva à primeira onda. Ela tende a ser **profunda**, muitas vezes devolvendo grande parte dos lucros obtidos na onda 1.
*   **Fibonacci:** Frequentemente retrai entre **50% e 61,8%** (e às vezes até 78,6%) da onda 1.
*   **Psicologia:** O volume costuma ser menor que na onda 1, indicando falta de convicção na venda, embora o público em geral ainda esteja convencido de que a tendência antiga voltará.

### **Onda 3: O Poder e a "Onda do Dinheiro"**
*   **Características:** Geralmente é a onda **mais forte, longa e dinâmica** do ciclo. É nesta fase que o mercado reconhece a nova tendência e a maioria dos investidores decide entrar.
*   **Fibonacci:** É comum que a onda 3 atinja uma extensão de **1,618 vezes** (razão áurea) ou mais em relação ao comprimento da onda 1.
*   **Volume:** É acompanhada por alto volume, rompimento de topos anteriores e lacunas (gaps) de aceleração. **Regra inegociável:** ela nunca pode ser a menor das três ondas de impulso (1, 3 e 5).

### **Onda 4: A Consolidação e a Frustração**
*   **Características:** É uma fase de realização de lucros e pausa após a força da onda 3. Costuma ser um movimento **lateral, complexo e demorado**.
*   **Regra da Alternância:** Se a onda 2 foi uma correção aguda e profunda, a onda 4 tende a ser lateral e rasa.
*   **Fibonacci:** Geralmente retrai entre **23,6% e 38,2%** da onda 3. **Regra inegociável:** em impulsos comuns, a onda 4 não pode entrar no território de preço da onda 1.

### **Onda 5: O Empurrão Final e a Euforia**
*   **Características:** Representa a perna final da tendência dominante. Embora atinja novos preços máximos, ela geralmente apresenta **menos força e volume** do que a onda 3.
*   **Divergências:** É comum observar divergências em indicadores de momentum (como RSI ou MACD), onde o preço sobe, mas o indicador não acompanha, sinalizando exaustão.
*   **Psicologia:** É o momento em que o otimismo é extremo e o investidor médio finalmente decide comprar, muitas vezes pouco antes da reversão para a fase corretiva maior.

---

### **As Três Regras de Ferro do Impulso**
Para que uma contagem de ondas de impulso seja válida, ela deve obrigatoriamente respeitar estas três regras:
1.  **A Onda 2 nunca pode retrair mais de 100% da Onda 1** (não pode ultrapassar o início da onda 1).
2.  **A Onda 3 nunca pode ser a menor** entre as ondas de impulso (1, 3 e 5).
3.  **A Onda 4 nunca pode entrar no território de preço da Onda 1** (não pode haver sobreposição, exceto em raras formações diagonais).

---

### 🔻 Ondas Corretivas (A–B–C)

As **Ondas Corretivas (A–B–C)** ocorrem após a conclusão de um ciclo de impulso de cinco ondas. Elas têm como objetivo **corrigir ou retratar** parte do movimento anterior, movendo-se contra a tendência de grau maior. Diferente das ondas de impulso, as correções são geralmente mais variadas, complexas e difíceis de identificar em tempo real.

### **Onda A: O Início do Recuo**
*   **Função:** É o primeiro movimento de contra-tendência, sinalizando que a tendência principal perdeu força.
*   **Psicologia:** Frequentemente é confundida com um simples recuo temporário ou realização de lucro dentro de um mercado que o público ainda acredita ser de alta. 
*   **Estrutura Interna:** É considerada uma **onda híbrida**. Pode se subdividir em **5 sub-ondas** (em um padrão de Ziguezague) ou em **3 sub-ondas** (em padrões Planos/Flats ou Triângulos).
*   **Características:** Geralmente apresenta um aumento de volume e volatilidade em relação ao final da onda 5 anterior.

### **Onda B: A Armadilha (Bull/Bear Trap)**
*   **Função:** Representa um rali de curta duração na direção da tendência original, funcionando como um "respiro" da correção.
*   **Psicologia:** É descrita como uma **onda "falsa" ou enganosa**. Ela atrai investidores que acreditam que a tendência principal foi retomada, criando o que analistas chamam de **"bull trap" (armadilha para touros)**.
*   **Estrutura Interna:** Por definição, a onda B é **sempre corretiva** e se subdivide em 3 ondas.
*   **Características:** Apresenta **baixo volume** e falta de força técnica, raramente superando o topo da onda 5 anterior (exceto em formações de "flats expandidos").

### **Onda C: A Confirmação e Capitulação**
*   **Função:** É a fase final da correção, que confirma a reversão temporária e limpa os excessos de otimismo.
*   **Psicologia:** Marcada pelo sentimento de **medo e desespero**. É o momento em que as ilusões criadas nas ondas A e B desaparecem e o mercado entra em pânico.
*   **Estrutura Interna:** Na grande maioria das vezes, a onda C é uma **onda de impulso de 5 ondas**, o que a torna forte e persistente.
*   **Características:** Costuma ser tão devastadora quanto uma onda 3 de impulso, apresentando ampla participação e queda (ou alta, em mercados de baixa) agressiva nos preços.

---

### **Principais Padrões de Estrutura ABC**
1.  **Ziguezague (5-3-5):** Uma correção **aguda e rápida** onde a onda A tem 5 ondas, a B tem 3 e a C tem 5.
2.  **Plano ou Flat (3-3-5):** Uma correção **lateral e rasa**, indicando que a tendência principal é muito forte e o mercado apenas consolidou antes de continuar.
3.  **Triângulo (3-3-3-3-3):** Um movimento lateral de afunilamento que reflete um equilíbrio entre compradores e vendedores, geralmente ocorrendo antes do último empurrão da tendência (onda 4 ou onda B).

---

## 📖 4.2 Glossário

*   **Teoria das Ondas de Elliott:** Método de análise técnica que interpreta os ciclos de mercado através de **padrões repetitivos (ondas) baseados na psicologia de massa**.
*   **Ondas Motrizes (ou de Impulso):** Estruturas de **cinco ondas (1-2-3-4-5)** que impulsionam o preço na direção da tendência principal.
*   **Ondas Corretivas:** Estruturas de **três ondas (A-B-C)** que realizam pausas ou recuos contra a tendência dominante.
*   **Fractal:** Propriedade geométrica onde **os padrões se repetem em qualquer escala**, permitindo que ondas menores componham ondas maiores identicamente.
*   **Grau da Onda:** Classificação da **escala temporal e tamanho** de um ciclo, variando desde o *Grand Supercycle* (séculos) até a *Subminuette* (minutos).
*   **Regra da Onda 2:** A onda 2 **nunca pode retrair mais de 100% da onda 1**, ou seja, não ultrapassa o seu ponto inicial.
*   **Regra da Onda 3:** Em um impulso, a onda 3 **nunca pode ser a mais curta** entre as ondas de ação (1, 3 e 5).
*   **Regra da Onda 4:** A onda 4 **não pode entrar no território de preço da onda 1**, exceto em padrões de diagonais.
*   **Zigzag:** Correção **aguda e rápida** com estrutura interna **5-3-5**.
*   **Flat (Plana):** Correção **lateral** com estrutura interna **3-3-5**, onde a onda B termina perto do início da onda A.
*   **Triângulo:** Padrão lateral rotulado como **A-B-C-D-E** com estrutura **3-3-3-3-3**, refletindo equilíbrio entre compradores e vendedores.
*   **Diagonal (Leading/Ending):** Padrão motriz em **formato de cunha** onde as ondas 1 e 4 frequentemente se sobrepõem.
*   **Alternância (Diretriz):** Tendência de o mercado **variar o estilo das correções**; se a onda 2 for aguda, a onda 4 será provavelmente lateral.
*   **Fibonacci:** Sequência matemática usada para definir **alvos de expansão (ex: 161,8%) e níveis de retração (ex: 61,8%)** das ondas.
*   **Truncagem (ou Falha):** Ocorre quando a **onda 5 termina sem superar o topo** alcançado pela onda 3.
*   **Extensão:** Um impulso alongado com **subdivisões exageradas**, sendo a onda 3 a que mais comumente se estende.
*   **Ondas Híbridas:** Termo usado para as **ondas A e C**, que podem se comportar como impulsos ou correções dependendo do padrão.
*   **Topo/Fundo Ortodoxo:** O ponto onde uma onda **termina tecnicamente**, que pode diferir do preço máximo ou mínimo real atingido.
*   **EWO (Elliott Wave Oscillator):** Indicador (média de 5 períodos menos a de 35) usado para **identificar o pico de momentum da onda 3** e divergências na onda 5.

---

## 🤖 4.3 Prompts Reutilizáveis

* "Explique a teoria das Ondas de Elliott de forma didática, como para um iniciante, incluindo exemplos simples e analogias que facilitem a compreensão dos padrões de mercado."
* "Descreva detalhadamente a estrutura das Ondas de Elliott, explicando as 5 ondas de impulso e as 3 ondas corretivas, incluindo as regras que validam cada uma delas e exemplos práticos no contexto do mercado financeiro."
* "Forneça exemplos práticos de aplicação das Ondas de Elliott em gráficos de ativos financeiros, explicando como identificar cada onda e interpretar possíveis movimentos futuros do mercado."
* "Explique passo a passo como identificar ondas de impulso e ondas corretivas em um gráfico, destacando critérios técnicos, sinais visuais e erros comuns cometidos por iniciantes."

---

# 🧩 5. Conclusão

Neste projeto, aprofundei meu entendimento sobre a teoria das Ondas de Elliott, compreendendo com mais clareza a estrutura das ondas, suas regras fundamentais e as diferentes variações que podem ocorrer no mercado. Esse processo foi essencial para desenvolver uma visão mais analítica sobre movimentos de preço e comportamento do mercado financeiro.

O uso do NotebookLM foi um grande diferencial durante o estudo, pois permitiu acelerar significativamente a aprendizagem. A ferramenta não apenas organizou e sintetizou as informações das fontes selecionadas, como também expandiu o conteúdo com sugestões adicionais, trazendo mais de 20 novas referências complementares. Isso contribuiu para tornar o estudo mais completo, menos superficial e com maior profundidade conceitual.

Além disso, a experiência com engenharia de prompts evidenciou a importância de saber interagir com a IA de forma estratégica, refinando perguntas para obter respostas mais relevantes e detalhadas.

Como próximo passo, pretendo continuar utilizando o NotebookLM para aprofundar meus estudos em conceitos mais avançados de análise de mercado, como o Smart Money Concept (SMC), ampliando ainda mais minha base de conhecimento e capacidade analítica.


