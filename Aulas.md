# Diretório de Estudos: Modelagem Matemática

---

## 1. Conjuntos

### Conceitos Básicos e Símbolos
* $\in$ (Pertence) / $\notin$ (Não pertence): Relaciona um **elemento** com um **conjunto**.
* $\subset$ (Está contido) / $\not\subset$ (Não está contido): Relaciona um **conjunto** com outro **conjunto**.
* $n(A)$: Indica o **número de elementos** (cardinalidade) do conjunto $A$.

### Operações entre Conjuntos
* **União ($A \cup B$):** Junta todos os elementos de ambos os conjuntos. Significa "$A$ **ou** $B$".
* **Interseção ($A \cap B$):** Apenas os elementos que eles têm em comum. Significa "$A$ **e** $B$".
* **Diferença ($A - B$):** Elementos que estão em $A$, mas **não** estão em $B$ ("Apenas $A$").
* **Complementar ($A^c$ ou $\overline{A}$):** Tudo o que está no Conjunto Universo ($U$), mas está fora do conjunto $A$.



### Resolução de Problemas (Diagrama de Venn)
Para problemas textuais com contagem de elementos, siga sempre estes três passos:
1. **Comece pelo Centro:** Preencha primeiro a interseção central (quem consome/gosta de todos os produtos ao mesmo tempo).
2. **Subtraia para os Lados:** Ao preencher as partes exclusivas ("Apenas"), subtraia o valor da interseção que você já colocou no centro.
   $$\text{Apenas } A = n(A) - n(A \cap B)$$
3. **Considere o "Fora":** Se houver um grupo que não escolheu nenhuma das opções, ele fica dentro do quadrado do Universo ($U$), mas fora dos círculos.
   $$\text{União Real } n(A \cup B) = \text{Total Geral} - \text{Nenhum}$$

#### Fórmula da União de Dois Conjuntos:
$$n(A \cup B) = n(A) + n(B) - n(A \cap B)$$

---

## 2. Produto Cartesiano e Relações Binárias

### Produto Cartesiano ($A \times B$)
É o conjunto formado por **todos os pares ordenados $(x, y)$ possíveis**, onde $x \in A$ e $y \in B$.
$$A \times B = \{ (x, y) \mid x \in A \text{ e } y \in B \}$$
* **Importante:** A ordem importa! $A \times B \neq B \times A$.
* **Número de Elementos:** $n(A \times B) = n(A) \cdot n(B)$

### Relações Binárias ($R$)
Uma Relação Binária de $A$ em $B$ é qualquer **subconjunto** do Produto Cartesiano $A \times B$.
$$R \subset (A \times B)$$

* **Domínio ($\text{Dom } R$):** Conjunto de todos os primeiros elementos $(x)$ dos pares ordenados que participam da relação ($\text{Dom } R \subset A$).
* **Contradomínio ($C_D$):** O conjunto de chegada inteiro (o próprio conjunto $B$).
* **Imagem ($\text{Im } R$):** Conjunto de todos os segundos elementos $(y)$ que foram gerados pela regra ($\text{Im } R \subset B$).



### Condição para ser Função
Para que uma relação binária de $A$ em $B$ seja considerada uma **função**, ela precisa cumprir duas regras:
1. **Todo** elemento de $A$ deve partir uma seta (não pode sobrar ninguém no domínio).
2. De cada elemento de $A$ deve partir **uma única** seta (um elemento de $x$ não pode se conectar a dois $y$ diferentes).

---

## 3. Aplicações Econômicas (1º e 2º Grau)

### Funções Econômicas Fundamentais
A variável $x$ (ou $q$) representa a **quantidade de unidades** produzidas/vendidas.
* **Função Custo ($C(x)$):** Gasto total. É a soma do custo fixo com o custo variável por unidade.
  $$C(x) = C_f + C_v \cdot x$$
* **Função Receita ($R(x)$):** Todo o dinheiro que entra com as vendas.
  $$R(x) = p \cdot x \quad (\text{onde } p = \text{preço de venda})$$
* **Função Lucro ($L(x)$):** Ganho real da empresa.
  $$L(x) = R(x) - C(x)$$
  > ⚠️ **Atenção:** O sinal de menos inverte os sinais de dentro da função Custo!

### Ponto de Equilíbrio (Break-Even Point)
É o ponto onde a empresa empata: não há lucro nem prejuízo.
$$\text{Condição: } L(x) = 0 \quad \text{ou} \quad R(x) = C(x)$$



### Modelos de 1º Grau (Lineares)
* **Demanda (Procura):** Função decrescente ($a < 0$). Quanto maior o preço, menos as pessoas compram.
* **Oferta:** Função crescente ($a > 0$). Quanto maior o preço, mais os produtores querem vender.
* **Equilíbrio de Mercado:** O preço ideal ocorre quando $\text{Oferta} = \text{Demanda}$.

### Modelos de 2º Grau (Quadráticos)
Ocorre quando o preço ($p$) varia conforme a quantidade demandada ($p = -ax + b$), tornando a Receita quadrática: $R(x) = -ax^2 + bx$.

#### Otimização com o Vértice da Parábola ($\cap$)
* **Quantidade Ótima ($X_v$):** Quantidade necessária para atingir o topo (Lucro ou Receita máxima).
  $$X_v = \frac{-b}{2a}$$
* **Valor Máximo ($Y_v$):** O teto financeiro do Lucro Máximo ou da Receita Máxima.
  $$Y_v = \frac{-\Delta}{4a} \quad \text{onde } \Delta = b^2 - 4ac$$

#### Pegadinha do Break-Even Quadrático
Se ao igualar $R(x) = C(x)$ você encontrar duas raízes positivas ($x_1$ e $x_2$):
* **Menor raiz ($x_1$):** É o verdadeiro Ponto de Equilíbrio (quando a empresa começa a dar lucro).
* **Maior raiz ($x_2$):** É o ponto de saturação (onde os custos voltam a engolir a receita).

---

## 4. Função Exponencial

### Estrutura Padrão
$$f(x) = a \cdot b^x \quad \text{com } a > 0, b > 0 \text{ e } b \neq 1$$
* Se $b > 1$: Função **Crescente** (Ex: juros compostos, crescimento populacional).
* Se $0 < b < 1$: Função **Decrescente** (Ex: depreciação de ativos, desvalorização).

### Domínio e Imagem
* **Matemático Puro:** $\text{Dom} = \mathbb{R}$ e $\text{Im} = \mathbb{R}_+^*$ ($y > 0$, o gráfico nunca toca o zero).
* **Econômico (Restringido):** Como o tempo/quantidade $x \ge 0$, o gráfico começa no valor inicial $a$.
  * Se crescente: $\text{Im} = [a, +\infty[$
  * Se decrescente: $\text{Im} = ]0, a]$

---

## 5. Função Logarítmica

### Estrutura Padrão
$$f(x) = \log_b(x) \quad \text{com } b > 0 \text{ e } b \neq 1$$
Modela fenômenos de crescimento lento com saturação (Ex: impacto de campanhas publicitárias ao longo do tempo).

### Restrições Críticas (Condição de Existência)
* O que está dentro do logaritmo (logaritmando) **obrigatoriamente deve ser maior que zero**.
* A base $b$ deve ser maior que zero e diferente de 1.



### Truque para Montar a Tabela de Gráficos
Para calcular sem números quebrados, escolha valores de $x$ que façam o conteúdo do parênteses se transformar em **potências da base** do logaritmo ($1, b, b^2, b^3...$).

Se a base for 3 na função $f(x) = 2 \cdot \log_3(-x + 1)$:
* Faça $-x + 1 = 1 \implies x = 0 \implies 2 \cdot \log_3(1) = 2 \cdot 0 = 0 \rightarrow (0,0)$
* Faça $-x + 1 = 3 \implies x = -2 \implies 2 \cdot \log_3(3) = 2 \cdot 1 = 2 \rightarrow (-2,2)$
* Faça $-x + 1 = 9 \implies x = -8 \implies 2 \cdot \log_3(9) = 2 \cdot 2 = 4 \rightarrow (-8,4)$

#### Sintaxe do GeoGebra:
Para bases diferentes de 10 ou $e$, digite: `log(base, argumento)` $\rightarrow$ Ex: `log(3, -x + 1)`.

---

## 6. Função Trigonométrica (Seno e Cosseno)

### O Modelo Geral Sazonal
Modela fenômenos cíclicos (sazonalidade de vendas, ondas de estoque).
$$f(x) = A + B \cdot \sin(C \cdot x)$$
* **$A$ (Linha Média / Eixo Central):** O ponto de equilíbrio vertical da onda.
* **$B$ (Amplitude):** O quanto a onda oscila para cima e para baixo a partir da linha média.
* **$C$ (Frequência):** Altera o período (comprimento) da onda.



### Cálculo da Imagem
A imagem da função oscila perfeitamente entre o ponto mais baixo e o ponto mais alto:
$$\text{Im} = [A - B, A + B]$$

---

## 7. Função Composta

### Conceito
É a aplicação de uma função dentro da outra. Representada por $f(g(x))$ ou $(f \circ g)(x)$.

### Como Resolver
Substitua a expressão da função interna ($g(x)$) em **cada** lugar onde aparece a variável $x$ na função externa ($f(x)$).

* **Exemplo:** Se $f(x) = x^2 + 2$ e $g(x) = 3x - 1$:
  $$f(g(x)) = (3x - 1)^2 + 2$$
  $$f(g(x)) = (9x^2 - 6x + 1) + 2 \implies 9x^2 - 6x + 3$$