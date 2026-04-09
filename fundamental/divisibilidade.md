# Divisão Exata

Considerando um exempo de da seguinte operação $10 / 2 = 5$, é possível concluir a seguinte observação:

> Se o resultado da divisão de 10 por 2 é igual a 5, então o resultado da divisão de 10 por 5 é igual a 2. Além disso, isso equivale a dizer que 2 vezes 5 é igual a 10.

Essa conclusão vale para quaisquer números naturais não nulos. Na verdade, também se aplica a números negativos ou não inteiros, desde que sejam diferentes de zero.

> Se $n = a \times b$, onde $a$ e $b$ são naturais não nulos,  
> então podemos dividir $n$ objetos em $b$ grupos de $a$ elementos  
> e também em $a$ grupos de $b$ elementos ($n \div a = b$).  
> Assim, $n$ dividido por $a$ é igual a $b$ e  
> $n$ dividido por $b$ é igual a $a$ ($n \div b = a$).

Vejamos outra propriedade importante da divisão, que nos ajudará bastante a fazer contas:

> Imagine que você dividiu um certo número  
> de objetos em grupos de mesmo tamanho. Se  
> você multiplicar o total de objetos por um  
> número $k$ e continuar dividindo pela mesma  
> quantidade de grupos, então a quantidade de  
> objetos em cada grupo também será multiplicada por $k$.

Já sabemos que 15 (objetos) dividido(s) em 3 (grupos) resulta em 5 (objetos por grupo). Se começarmos com
um total 2 vezes maior, ou seja, 30 objetos, e continuarmos
dividindo-os em 3 grupos, obteremos 10 objetos em cada grupo:

$15 ÷ 3 = 5 ⇒ (2 × 15) ÷ 3 = 2 × 5 ⇒ 30 ÷ 3 = 10$.

## Por que a regra citada acima não se aplica a zero ou a números decimais?

1. O problema da divisão por zero

A regra diz que se _n = a × b_, então _n ÷ a = b_. Se permitirmos que o zero entre na jogada, a lógica quebra:

### A indeterminação

Digamos que _n = 0_. Podemos dizer que _0 = 5 × 0_. Pela regra, _0 ÷ 0_ deveria ser _5_. Mas também poderíamos dizer que _0 = 10 × 0_, o que significaria que _0 ÷ 0 = 10_. Como um resultado não pode ser dois valores diferentes ao mesmo tempo, a divisão por zero é considerada indeterminada ou impossível.

### Impossibilidade física

Tente dividir 10 objetos em 0 grupos. Não importa o que você faça, os objetos continuam lá; você não consegue executar a ação de distribuir em "lugar nenhum".

1. A natureza dos "objetos" e "grupos"

A definição é baseada em uma visão discreta da matemática (contagem de itens físicos):

- **Grupos Inteiros:** Na definição de "dividir _n_ objetos em _b_ grupos de _a_ elementos", tanto _a_ quanto _b_ precisam ser números inteiros para que a analogia faça sentido físico.

O que acontece com decimais? Se _n = 5_, e tentarmos usar _a = 2,5_ e _b = 2_, a frase "dividir 5 objetos em 2 grupos de 2,5 elementos" já não descreve uma contagem natural de objetos físicos (você teria que partir um objeto ao meio). Por isso, essa interpretação específica de "formar grupos" é restrita aos naturais.

1. Elemento Neutro e a Identidade

Se incluirmos o zero, perdemos a capacidade de "voltar" ao número original.

Na multiplicação:

$a × b = n$

Para que a divisão funcione como operação inversa, precisamos que:

$n ÷ b = a$

Se _b = 0_, a equação _a × 0 = 0_ é verdadeira para qualquer valor de _a_. Se você sabe apenas que o resultado (_n_) é 0, você nunca conseguirá descobrir qual era o valor original de _a_. O zero "apaga" a informação original.

### Resumo Visual da Relação

A regra é perfeitamente estável nos números naturais porque eles lidam com quantidades contáveis e divisões exatas. No momento em que o zero ou frações entram, passamos da aritmética de grupos para a álgebra abstrata ou cálculo, onde as regras de "formar grupinhos" precisam ser adaptadas.

# Divisão com resto

Para ser considerado “resto” da divisão, a sobra precisa ser tão pequena que não seja mais possível dividi-la pela quantidade de pessoas ou grupos. Em outras palavras, o resto deve ser sempre um número estritamente menor do que o divisor. Além disso, vale a seguinte relação fundamental:

**dividendo** = **divisor** × **quociente** + **resto**

Chamando o dividendo de _n_, o divisor de _d_, o quociente de _q_ e o resto de _r_, temos, de forma simplificada:

$n = d × q + r$

Com essa notação, podemos reescrever a segunda propriedade da seção anterior da seguinte maneira:

> Numa divisão exata, se multiplicarmos o dividendo por um número natural _k_,
> o quociente da divisão também será multiplicado por _k_.

De fato, estamos no caso em que _r = 0_, e vale que:

$n ÷ d = q
 ⇒ n = d × q
 ⇒ k × n = d × (k × q)
 ⇒ (k × n) ÷ d = k × q$

Algo parecido continua valendo quando há sobras: se multiplicarmos o dividendo por _k_, tanto o quociente como a sobra serão multiplicados por _k_, pois

$n = d × q + r
 ⇒ k × n = d × (k × q) + k × r$

**Mas tome muito cuidado**: é possível que a nova sobra, o valor _k × r_, seja maior que o divisor _d_ e, assim, possa ser repartida entre os _d_ grupos. Dessa forma, _k × r_ é uma sobra, mas pode não ser o resto da divisão de _k × n_ por _d_.

## Vamos dividir **978** por **8** (Alternativa 2)

Vamos usar o método da Alternativa 2 (repartir a sobra), que é excelente para dividir números grandes mentalmente ou quando não queremos usar o algoritmo tradicional de **fazer a conta**:

### Passo 1: Escolha um "salto" fácil

Em vez de tentar adivinhar o quociente exato de cara, pegue um número redondo que você sabe que multiplicado por _8_ chega perto de _978_.  
 Sabemos que $8 × 100 = 800$.  
 Então, escrevemos: $978 = 8 × 100 + 178$.  
 Aqui, já garantimos que o quociente é pelo menos _100_, e agora só precisamos nos preocupar com a "sobra" de _178_.

### Passo 2: Divida a sobra

Agora pegamos o _178_ e vemos quantas vezes o _8_ cabe nele.  
 Pense na tabuada: $8 × 2 = 16$, logo $8 × 20 = 160$.  
 Podemos escrever: $178 = 8 × 20 + 18$.  
 Agora nossa conta está assim: $978 = 8 × 100 + 8 × 20 + 18$.

### Passo 3: Continue até o resto ser menor que o divisor

Ainda sobrou _18_, que é maior que o nosso divisor (_8_). Então, dividimos mais uma vez:  
 $18 = 8 × 2 + 2$.  
 Agora temos a decomposição completa:  
 $978 = 8 × 100 + 8 × 20 + 8 × 2 + 2$.

### Passo 4: Some os quocientes

Para achar o quociente final, somamos todos os grupos de _8_ que formamos:  
 **Quociente:** $100 + 20 + 2 = 122$  
 **Resto:** 2 (que é menor que 8, então paramos por aqui).

### Resumo do Cálculo

$978 = 8 × (100 + 20 + 2) + 2$  
 $978 = 8 × 122 + 2$

## Vamos dividir **978** por **8** (Alternativa 2)

A Alternativa 1 (conforme o texto da OBMEP) é focada em cercar o resultado através de estimativas e ajustes finos. Em vez de ir somando pedaços (como fizemos na Alternativa 2), você tenta "chutar" um quociente inteiro e vai testando os números vizinhos até chegar o mais próximo possível do dividendo, sem ultrapassá-lo:

### Passo 1: O "Chute" Inicial (Grande Aproximação)

Primeiro, pensamos em um número redondo que chegue perto de $978$.

- Sabemos que $8 \\times 100 = 800$ (ainda está longe).
- Sabemos que $8 \\times 200 = 1600$ (passou muito).
- Vamos tentar algo no meio, como $120$.
- $8 \\times 120 = 960$.

**Conclusão parcial:** O quociente é maior ou igual a **$120$**, pois $960$ é menor que $978$.

### Passo 2: O Ajuste Fino (Busca Exaustiva)

Agora que sabemos que o resultado está perto de $120$, vamos testando os próximos números de um em um (ou somando de $8$ em $8$ ao resultado anterior):

- **Testando 121:** $960 + 8 = 968$ (Ainda não chegou em $978$)
- **Testando 122:** $968 + 8 = 976$ (Chegou bem perto!)
- **Testando 123:** $976 + 8 = 984$ (**Passou!** Não temos $984$ objetos, só $978$)

### Passo 3: Identificar o Quociente e o Resto

O número mais próximo de $978$ que conseguimos atingir sem ultrapassar foi o **$976$**, que corresponde a $8 \\times 122$.

Agora, calculamos quanto sobrou (o resto):

$978 - 976 = 2$

**Resultado final:**

- **Quociente:** $122$
- **Resto:** $2$

## Qual é diferença real entre as duas?

- Na Alternativa 2, você vai "fatiando" o número e guardando os pedaços ($100 + 20 + 2$).
- Na Alternativa 1, você tenta adivinhar o "prédio inteiro" e depois vai subindo ou descendo os degraus (testando $121, 122...$) até encontrar o limite.
