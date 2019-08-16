## @152 #05_str L3 - OBI 2015 - Fase 2 - Nível 1 - Letras
## @qxcode

![](__capa.jpg)

## Motivação

Uma _cadeia de caracteres_ é uma sequência de letras do alfabeto. Uma cadeia de caracteres _crescente_ é uma sequência de letras onde a próxima letra (da esquerda para a direita) nunca ocorre antes no alfabeto do que a letra anterior. Por exemplo ABBD é crescente, enquanto ABBAD não é crescente.

Uma _subsequência_ de uma cadeia de caracteres é uma cadeia de caracteres que pode ser obtida a partir da remoção de zero ou mais caracteres da cadeia de caracteres original. Por exemplo ANNA é uma subsequência de BANANAS. Outro exemplo seria ANNS, que tambem é uma subsequência crescente de BANANAS.

Dada uma cadeia de caracteres S, escreva um programa para determinar o tamanho da maior subsequência de S que é uma cadeia de caracteres crescente.

### Entrada

A entrada consiste em uma única linha, contendo uma cadeia de caracteres S.

### Saída

Seu programa deve produzir uma única linha, contendo um único inteiro, o tamanho da maior subsequência de S que é uma cadeia de caracteres crescente.

## Restrições

*   A cadeia de caracteres de entrada contém letras maiúsculas do alfabeto, de A até Z.
*   1 ≤ comprimento(S) ≤ 3 x 105.

## Informações sobre a pontuação

*   Em um conjunto de casos de teste valendo 20 pontos: comprimento(S) ≤ 20.
*   Em um conjunto de casos de teste valendo 30 pontos: comprimento(S) ≤ 3000.

## Exemplos

```
>>>>>>>>
BANANAS
========
4
<<<<<<<<

>>>>>>>>
AAXBBXZZX
========
7
<<<<<<<<

>>>>>>>>
AAA
========
3
<<<<<<<<
```

#

<!---
>>>>>>>> 01
LDAPJFUCKKNCJFDRYKOO
========
7
<<<<<<<<

>>>>>>>> 02
AZZZZAAAAZAZZAZZZAZA
========
12
<<<<<<<<

>>>>>>>> 03
ZAZZZZZZZZZZAZZZAZZZ
========
17
<<<<<<<<

>>>>>>>> 04
ZAAAZZZAAAAZAAZAZZAA
========
12
<<<<<<<<

>>>>>>>> 05
VSNNPBZDIIJEDJYOSHSH
========
9
<<<<<<<<

>>>>>>>> 06
OMDURMSZYZEYTWQZRPVQ
========
6
<<<<<<<<


>>>>>>>> 07
PIRCHIRKSEUOKCBBOCMC
========
6
<<<<<<<<

>>>>>>>> 08
VHOGWMFNOBTJRXSRMVVK
========
8
<<<<<<<<

>>>>>>>> 09
ASYHGLIRVWSFYDBAAPJY
========
8
<<<<<<<<

>>>>>>>> 10
TPNETFUVCKKLJMDMKKZC
========
8
<<<<<<<<

>>>>>>>> 11
NPONLLXMRFOUPTRAXZTZ
========
9
<<<<<<<<

>>>>>>>> 12
ABCDEFGHIJKLMNOPQRST
========
20
<<<<<<<<

>>>>>>>> 13
AZZZAAZZAAAZAZAZAZAZ
========
11
<<<<<<<<
--->