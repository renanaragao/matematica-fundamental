# Múltiplos e Divisores

> Quando uma **divisão** é exata, o resto $r$ é igual a zero e a igualdade pode ser escrita assim:
> $$a = b \cdot q \quad$$
> Neste caso, dizemos que **$a$ é múltiplo de $b$**, ou que **$a$ é divisível por $b$**, ou ainda que **$b$ divide $a$**.

Veja que $a = a \cdot 1$ para todo $a \in \mathbb{N}$. Dessa forma, podemos dizer que $1$ é divisor de qualquer número natural. Podemos ainda concluir, observando essa mesma igualdade, que todo número natural é divisor de si mesmo. Da mesma forma, a igualdade $0 = a \cdot 0$ nos diz que o número $0$ é múltiplo de qualquer número natural.

# Números Primos

O número **1** possui apenas um divisor: ele mesmo. Para verificarmos isso, escrevemos $1 = b \cdot q$, com $b, q \in \mathbb{N}$. Então, $b$ não pode ser maior do que $1$, ou seja, $b$ só pode ser igual a $0$ ou igual a $1$. Se $b$ fosse igual a $0$, então $1 = b \cdot q = 0 \cdot q = 0$, o que não é possível. Logo, $b$ só pode ser igual a $1$.

Quanto ao número **zero**, ele tem uma quantidade infinita de divisores. Exceto o número zero, qualquer outro número natural tem uma quantidade **finita** de divisores.

Além disso, qualquer número natural $n$ diferente de $0$ ou $1$ tem pelo menos dois divisores: o número **1** e o **próprio $n$**. Um caso de especial importância é quando um número natural diferente de $1$ tem a menor quantidade possível de divisores.

## Definições

- **Número Primo:** Quando um número natural tem **exatamente dois** divisores (o 1 e ele mesmo).
- **Número Composto:** Se um número natural diferente de $0$ e de $1$ não é primo, dizemos que ele é composto.

Números compostos são exatamente aqueles que podem ser escritos como o produto de dois outros números naturais menores que eles.

**Exemplos:**

- **12** e **21** são compostos, pois $12 = 2 \cdot 6$ e $21 = 3 \cdot 7$.
- **23** é primo, pois a única forma de escrevê-lo como produto de dois naturais é $23 = 23 \cdot 1$, e nenhum dos fatores é menor do que $23$.

## O Número 2 e a Natureza dos Pares e Ímpares

O número **2** "paga um preço" por ser pequeno demais: não é possível formar duas colunas e duas linhas (um retângulo ou quadrado maior que 1x2) apenas com dois pontos. Por isso, **2 é o único número primo par**.

O número **0 é par**, pois $0 = 2 \cdot 0$, ou seja, 0 é um múltiplo de 2.

Números naturais que não são divisíveis por 2 são chamados de **ímpares**. Pares e ímpares se alternam na sequência dos naturais: um natural é par ou ímpar; se $n$ é ímpar, então $n + 1$ é par; se $n$ é par, então $n + 1$ é ímpar.

A partir desse fato, podemos concluir que há uma infinidade de números pares e, como todos os pares (exceto o 2) são compostos, há também uma **infinidade de números compostos**.

# Números Primos entre si

Dados dois ou mais números naturais, que não sejam todos iguais a zero, um divisor comum desses números é um número natural que divide todos esses números ao mesmo tempo.

Exemplos:

- Os divisores comuns de 15 e 48 são 1 e 3.
- Os divisores comuns de 16 e 48 são 1, 2, 4, 8 e 16.
- O único divisor comum de 15 e 16 é 1.
- O único divisor comum de 17 e 48 é 1.

O número 1 divide qualquer número natural, logo é divisor comum de quaisquer números naturais dados. Um caso especialmente importante é aquele em que o 1 é o único divisor comum.

> Quando 1 é o único divisor comum de dois ou mais números naturais, não todos nulos, dizemos que estes números são **primos entre si**, ou **relativamente primos**.

- Os números 3 e 8 são primos entre si, pois os divisores de 3 são {1, 3}, enquanto os divisores de 8 são {1, 2, 4, 8}. Logo, o único divisor comum de 3 e 8 é 1.
- Os divisores de 9 são {1, 3, 9} e os divisores de 12 são {1, 2, 3, 4, 6, 12}. Logo, os divisores comuns de 9 e 12 são 1 e 3. Como 1 não é o único divisor comum, estes números não são primos entre si.
- Os números 8 e 12 têm como divisores comuns os números 1, 2 e 4, logo não são primos entre si.
- O único divisor comum de 8, 9 e 12 é 1, logo 8, 9 e 12 são primos entre si.
- De acordo com o exemplo 10 (a), 15 e 48 não são primos entre si, pois 3 é um divisor comum desses números.
- De acordo com o exemplo 10 (c), 15 e 16 são primos entre si.
