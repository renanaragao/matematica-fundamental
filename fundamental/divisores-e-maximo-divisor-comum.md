# Divisores e Máximo Divisor Comum

## Divisores

**Divisores** são números inteiros que, multiplicados entre si, são como resultado outro número inteiro.

Exemplo: Quais são os divisores de 6? 2 e 3 são divisores de 6, por que $2 . 3 = 6$. 1 e 6 também são divisores de 6 por que $1 . 6 = 6$. Portanto os divisores de 6 são: 1, 2, 3 e 6.

Exemplo: Emílio precisa organizar cadeiras de filas para uma reunião de clube de teatro da escola. São esperados 30 alunos. De quantas maneiras diferentes Emílio pode dispor as cadeiras para que cada fila tenha o mesmo número de cadeiras? (Isso é o mesmo que dizer: "Encontre o númerod de divisores de 30.")

| Números de Fila | Cadeiras |
| --------------- | -------- |
| 1               | 30       |
| 2               | 15       |
| 3               | 10       |
| 5               | 6        |
| 6               | 5        |
| 10              | 3        |
| 15              | 2        |
| 30              | 1        |

Os divisores de 30 são 1, 2, 3, 5, 6, 10, 15 e 30. Existem portanto, oito modos diferentes de dispor as cadeiras.

Para descobrir os divisores de um número inteiro, usamos algumas regras práticas para certos números:

- Regra do 2: Um número é divisível por 2 se for par, ou seja, se terminar em 0, 2, 4, 6 ou 8.
  - Exemplos: 14 (termina em 4, é par), 38 (termina em 8, é par).
- Regra do 3: Um número é divisível por 3 se a soma de seus algarismos for divisível por 3.
  - Exemplos: 123 (1+2+3=6, 6 é divisível por 3), 402 (4+0+2=6, 6 é divisível por 3).
- Regra do 5: Um número é divisível por 5 se terminar em 0 ou 5.
  - Exemplos: 25 (termina em 5), 40 (termina em 0).
- Regra do 9: Um número é divisível por 9 se a soma de seus algarismos for divisível por 9.
  - Exemplos: 729 (7+2+9=18, 18 é divisível por 9), 81 (8+1=9, 9 é divisível por 9).
- Regra do 10: Um número é divisível por 10 se terminar em 0.
  - Exemplos: 70 (termina em 0), 120 (termina em 0).

Essas regras facilitam a identificação rápida de divisores comuns em números inteiros.

_Existem regras de divisibilidade para outros números primos, mas elas geralmente são mais complexas do que as regras para 2, 3, 5, 9 e 10. Por exemplo, para o número 7, uma regra comum é: dobre o último dígito do número, subtraia esse valor do restante do número, e se o resultado for divisível por 7, então o número original também é. Para o número 11, soma-se alternadamente os algarismos (um positivo, outro negativo) e verifica-se se o resultado é divisível por 11. Para outros primos maiores, as regras existem, mas tendem a ser menos práticas para uso manual no dia a dia._

## Números primos

**NÚMERO PRIMO** é um número que possui apenas dois divisores: o próprio número e 1. Exemplos de números primos: 2, 3, 7 e 13.

Os números primos são fundamentais para algoritmos de criptografia porque possuem propriedades matemáticas que tornam certos cálculos fáceis em uma direção e extremamente difíceis na direção oposta. Por exemplo, é simples multiplicar dois números primos grandes, mas fatorar o resultado para descobrir quais primos foram usados é computacionalmente difícil. Essa assimetria é a base de algoritmos como o RSA, que dependem da dificuldade de fatoração de grandes números para garantir a segurança das informações. Assim, os primos ajudam a criar chaves criptográficas seguras, protegendo dados contra acessos não autorizados.

No contexto do RSA, a segurança depende da dificuldade de fatorar um número grande em seus fatores primos. Por exemplo, suponha que alguém escolha os primos pequenos 5 e 11. Multiplicando, temos:

5 × 11 = 55

Se alguém só conhece o número 55, pode tentar descobrir seus fatores primos. Como 55 é pequeno, é fácil testar divisores: 55 ÷ 5 = 11, então 5 e 11 são os fatores primos.

No RSA real, os números usados são muito maiores (centenas de dígitos), tornando a fatoração praticamente impossível com os computadores atuais. Mas o princípio é o mesmo: se alguém conseguir fatorar o número composto, pode quebrar a criptografia.

Na criptografia como o RSA, utiliza-se números primos grandes porque a multiplicação de dois primos gera um número composto que só pode ser decomposto de volta nesses dois fatores primos. Se fossem usados números não primos (ou seja, compostos), haveria múltiplas combinações possíveis de fatores, tornando o sistema inseguro, pois alguém poderia encontrar outros conjuntos de fatores além dos originais. Os primos garantem que a fatoração só pode resultar nos dois números secretos escolhidos, aumentando a segurança do algoritmo.

## Divisores comuns

Quando um número é divisor de dois (ou mais) números, ele é chamado de **DIVISOR COMUM**.

Exemplo: Quais são os divisores comuns de 12 e 18?

Os divisores de 12 são 1, 2, 3, 4, 6, 12.
Os divisores de 18 são 1, 2, 3, 6, 9 e 18.
Os divisores comuns de 12 e 18 são 1, 2, 3 e 6.

O maior divisor que os números partilham é chamado de **MÁXIMO DIVISOR COMUM** ou **MDC**. O MDC de 12 e 18 é 6.
