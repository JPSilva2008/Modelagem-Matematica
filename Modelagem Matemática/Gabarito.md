# Gabarito Oficial: Modelagem Matemática

---

### Questão 1: Teoria dos Conjuntos (Diagrama de Venn)

**Resolução Passo a Passo:**
1. **União de três conjuntos pela fórmula da inclusão-exclusão:**
   $$n(A \cup B \cup C) = n(A) + n(B) + n(C) - n(A \cap B) - n(A \cap C) - n(B \cap C) + n(A \cap B \cap C)$$

2. **Substituindo os valores fornecidos:**
   $$n(A \cup B \cup C) = 160 + 140 + 120 - 60 - 50 - 40 + 20$$
   $$n(A \cup B \cup C) = 420 - 150 + 20 = 290$$

3. **Cálculo dos alunos que não utilizam nenhuma plataforma:**
   $$\text{Nenhum} = \text{Total} - n(A \cup B \cup C)$$
   $$\text{Nenhum} = 300 - 290 = 10 \text{ alunos}$$

---

### Questão 2: Relações Binárias e Condição de Função

**Resolução Passo a Passo:**

* **a) Produto Cartesiano $X \times Y$:**
  $$X \times Y = \{ (1, 5), (1, 10), (1, 15), (1, 20), (2, 5), (2, 10), (2, 15), (2, 20), (3, 5), (3, 10), (3, 15), (3, 20) \}$$

* **b) Domínio, Contradomínio e Imagem de $R = \{(1, 5), (2, 10), (3, 15)\}$:**
  * **Domínio $\text{Dom}(R)$:** $\{1, 2, 3\}$
  * **Contradomínio $C_D$:** $\{5, 10, 15, 20\}$
  * **Imagem $\text{Im}(R)$:** $\{5, 10, 15\}$

* **c) Análise se é Função:**
  **Sim, é uma função.** Todos os elementos do conjunto de partida $X$ possuem exatamente uma única correspondência no conjunto de chegada $Y$.

---

### Questão 3: Função Afim (Custo e Ponto de Equilíbrio)

**Resolução Passo a Passo:**

* **a) Equações de Custo Total e Receita:**
  * Custo Total: $C(x) = 12000 + 40x$
  * Receita Total: $R(x) = 100x$

* **b) Ponto de Equilíbrio ($R(x) = C(x)$):**
  $$100x = 12000 + 40x$$
  $$100x - 40x = 12000$$
  $$60x = 12000$$
  $$x = \frac{12000}{60} = 200 \text{ licenças}$$

---

### Questão 4: Função Quadrática (Otimização de Lucro)

Dada $L(x) = -5x^2 + 600x - 10000$, onde $a = -5$, $b = 600$, $c = -10000$:

**Resolução Passo a Passo:**

* **a) Quantidade para Lucro Máximo ($X_v$):**
  $$X_v = \frac{-b}{2a} = \frac{-600}{2(-5)} = \frac{-600}{-10} = 60 \text{ unidades}$$

* **b) Valor do Lucro Máximo ($Y_v$):**
  $$Y_v = L(60) = -5(60)^2 + 600(60) - 10000$$
  $$Y_v = -5(3600) + 36000 - 10000$$
  $$Y_v = -18000 + 36000 - 10000 = \text{R\$ } 8.000,00$$

---

### Questão 5: Função Quadrática (Zero da Função)

Para $L(x) = -2x^2 + 160x - 1800 = 0$:

**Resolução Passo a Passo:**
1. **Simplificando a equação dividindo tudo por $-2$:**
   $$x^2 - 80x + 900 = 0$$

2. **Aplicando a Fórmula de Bhaskara:**
   $$\Delta = (-80)^2 - 4(1)(900) = 6400 - 3600 = 2800$$
   $$\sqrt{2800} = \sqrt{400 \cdot 7} = 20\sqrt{7} \approx 52{,}915$$

3. **Calculando as raízes $x_1$ e $x_2$:**
   $$x = \frac{80 \pm 20\sqrt{7}}{2} = 40 \pm 10\sqrt{7}$$
   * $x_1 = 40 - 10\sqrt{7} \approx 13{,}54 \text{ unidades}$
   * $x_2 = 40 + 10\sqrt{7} \approx 66{,}46 \text{ unidades}$

---

### Questão 6: Função Exponencial (Depreciação de Ativos)

Dada $V(t) = 15000 \cdot (0{,}8)^t$:

**Resolução Passo a Passo:**

* **a) Valor Inicial ($t = 0$):**
  $$V(0) = 15000 \cdot (0{,}8)^0 = 15000 \cdot 1 = \text{R\$ } 15.000,00$$

* **b) Valor após 3 anos ($t = 3$):**
  $$V(3) = 15000 \cdot (0{,}8)^3$$
  $$V(3) = 15000 \cdot 0{,}512 = \text{R\$ } 7.680,00$$

---

### Questão 7: Função Logarítmica (Engajamento de Usuários)

Dada $N(t) = 200 + 100 \cdot \log_3(t + 2)$:

**Resolução Passo a Passo:**
1. **Substituindo $t = 25$:**
   $$N(25) = 200 + 100 \cdot \log_3(25 + 2)$$
   $$N(25) = 200 + 100 \cdot \log_3(27)$$

2. **Resolvendo o logaritmo ($\log_3 27 = 3$, pois $3^3 = 27$):**
   $$N(25) = 200 + 100(3)$$
   $$N(25) = 200 + 300 = 500 \text{ acessos diários}$$

---

### Questão 8: Função Trigonométrica (Análise de Sazonalidade)

Dada $S(t) = 400 + 200 \cdot \cos\left(\frac{\pi \cdot t}{6}\right)$:

**Resolução Passo a Passo:**

* **a) Vendas Máximas e Mínimas:**
  Como a função cosseno varia no intervalo $[-1, 1]$:
  * **Vendas Máximas:** $S_{\text{máx}} = 400 + 200(1) = 600 \text{ aparelhos}$
  * **Vendas Mínimas:** $S_{\text{mín}} = 400 + 200(-1) = 200 \text{ aparelhos}$

* **b) Amplitude e Valor Médio:**
  * **Amplitude:** $200 \text{ aparelhos}$ (coeficiente multiplicador do cosseno)
  * **Valor Médio:** $400 \text{ aparelhos}$ (termo constante da função)

---

### Questão 9: Função Composta

Dadas $f(x) = -3x^2 + 150x - 500$ e $g(x) = 0{,}9x - 100$:

**Resolução Passo a Passo:**

* **a) Expressão de $(g \circ f)(x)$:**
  $$(g \circ f)(x) = g(f(x)) = 0{,}9(-3x^2 + 150x - 500) - 100$$
  $$(g \circ f)(x) = -2{,}7x^2 + 135x - 450 - 100$$
  $$(g \circ f)(x) = -2{,}7x^2 + 135x - 550$$

* **b) Valor Numérico para $x = 10$:**
  $$f(10) = -3(10)^2 + 150(10) - 500 = -300 + 1500 - 500 = 700$$
  $$g(700) = 0{,}9(700) - 100 = 630 - 100 = 530$$
  *(Ou aplicando na composta: $-2{,}7(100) + 135(10) - 550 = -270 + 1350 - 550 = 530$)*

---

### Questão 10: Domínio de Funções

**Resolução Passo a Passo:**

* **a) $f(x) = \frac{2x + 5}{x - 8}$:**
  O denominador não pode ser nulo:
  $$x - 8 \neq 0 \implies x \neq 8$$
  $$\text{Dom}(f) = \mathbb{R} \setminus \{8\}$$

* **b) $g(x) = \sqrt{3x - 15}$:**
  O radicando de uma raiz de índice par deve ser maior ou igual a zero:
  $$3x - 15 \geq 0 \implies 3x \geq 15 \implies x \geq 5$$
  $$\text{Dom}(g) = \{x \in \mathbb{R} \mid x \geq 5\} \text{ ou } [5, +\infty)$$