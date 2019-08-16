## @158 #03_rep L3 - Trilhas - OBI 2005
## @qxcode

![](__capa.jpg)

## Motivação

Nos finais de semana Paulo faz longas caminhadas pelas bonitas trilhas que atravessam as matas  
vizinhas à sua cidade. Recentemente Paulo adquiriu um aparelho de GPS (siglas do inglês Sistema  
de Posicionamento Global) e com ele mapeou as mais belas trilhas da região. Paulo programou o  
GPS para armazenar, a intervalos regulares, a altitude do ponto corrente durante o trajeto. Assim,  
após percorrer as trilhas com o seu GPS, Paulo tem informações que permitem por exemplo produzir  
gráficos como os abaixo:  
  
Paulo tem uma nova namorada, e quer convencê-la a passear junto com ele pelas trilhas. Para o  
primeiro passeio juntos, Paulo quer escolher uma trilha "fácil”. Segundo o seu critério, a trilha mais  
fácil é a que, em um dos sentidos do percurso, exige o menor esforço de subida. O esforço exigido em  
um trecho de subida é proporcional ao desnı́vel do trecho.  

## Ação

Dadas as informações colhidas por Paulo sobre distâncias e altitudes de um conjunto de trilhas, você  
deve escrever um programa que determine qual é a trilha que exige o menor esforço de subida.  
  
### Entrada

- A primeira linha da entrada contém um número inteiro N que indica o número de trilhas. Cada uma
das N linhas seguintes contém a descrição de uma trilha (1 ≤ N ≤ 100). As trilhas são identificadas por
números de 1 a N . A ordem em que as trilhas aparecem na entrada determina os seus identificadores
(a primeira trilha é a de número 1, a segunda a de número 2, a última a de número N ). A descrição
de uma trilha inicia com um número inteiro M que indica a quantidade de pontos de medição da
trilha (2 ≤ M ≤ 1000), seguido de M números inteiros Hi representando a altura dos pontos da
trilha (medidos a intervalos regulares e iguais para todas as linhas). Paulo pode percorrer a trilha em
qualquer sentido (ou seja, partindo do ponto de altitude H1 em direção ao ponto de altitude HM , ou
partindo do ponto de altitude HM em direção ao ponto de altitude H1 ).
A entrada deve ser lida do dispositivo de entrada padrão (normalmente o teclado).
  
### Saída

- Seu programa deve produzir uma única linha na saı́da, contendo um número inteiro representando o  
identificador da melhor trilha, conforme determinado pelo seu programa. Em caso de empate entre  
duas ou mais trilhas, imprima a de menor identificador.  
A saı́da deve ser escrita no dispositivo de saı́da padrão (normalmente a tela).  
  
Olimpı́ada Brasileira de Informática - OBI2005 - Modalidade Programação Nı́vel 1  
  
## Restrições

1 ≤ N ≤ 100  
2 ≤ M ≤ 1000  
0 ≤ Hi ≤ 1000

## Exemplos

```
>>>>>>>> 01
5
10 60 60 70 70 70 70 80 90 90 100
4 498 500 498 498
5 200 190 180 170 160
2 1000 900
4 20 20 20 20
========
5
<<<<<<<<
```

#

<!---
>>>>>>>> 02
10
42 51 94 74 39 85 62 89 37 5 11 96 2 4 64 3 87 13 22 93 35 70 10 22 23 53 48 89 67 72 74 16 25 96 94 78 41 61 25 73 51 42 28
73 99 50 26 74 83 37 62 22 12 87 32 48 12 62 62 30 21 61 56 66 6 50 53 53 50 0 10 14 73 64 14 55 27 13 82 19 46 0 28 55 7 95 76 75 54 63 40 65 25 26 73 10 25 74 70 39 91 38 84 31 25 94 36 0 57 39 48 98 58 62 62 33 18
89 108 110 106 102 104 100 107 108 102 101 101 102 100 109 100 106 104 106 104 102 108 105 106 102 106 106 108 106 102 108 109 106 103 106 102 105 109 105 100 105 106 110 109 103 101 103 103 103 107 104 105 100 107 107 108 101 105 100 107 103 109 110 110 101 100 103 101 101 103 107 109 105 103 103 104 107 109 102 110 110 100 110 107 104 105 108 105 100 102
82 75 41 53 79 60 7 50 87 63 3 24 81 64 24 86 42 38 87 92 89 79 3 36 0 92 69 18 70 44 77 76 33 32 6 62 29 94 41 2 32 8 3 1 46 20 39 66 73 97 27 21 80 53 87 41 57 28 99 38 72 6 44 1 70 44 71 48 22 73 61 47 78 4 43 33 58 23 53 64 42 92 41
25 58 17 80 80 41 34 100 64 63 60 9 25 43 25 57 18 50 36 75 37 38 2 43 31 28
67 96 94 92 94 97 92 93 98 99 97 94 92 92 92 96 95 92 92 92 100 90 94 92 95 91 98 99 91 96 92 98 97 98 91 99 94 98 92 98 90 97 97 92 99 98 96 92 99 98 90 96 94 93 92 100 92 93 93 95 100 92 96 94 90 96 99 96
15 103 108 102 104 100 102 102 106 109 101 101 110 107 103 105
96 53 100 44 58 2 76 77 41 52 52 14 41 49 0 59 32 99 61 10 14 5 98 7 46 79 15 65 17 87 63 25 65 74 95 64 82 4 4 31 34 89 57 11 87 10 9 96 52 81 15 41 30 48 18 56 37 75 30 85 60 43 85 92 56 65 67 42 65 0 2 65 38 28 41 95 21 57 37 21 58 56 73 13 57 86 74 14 72 71 45 63 75 9 43 93 83
14 93 98 100 92 91 99 94 99 100 93 91 99 90 93
84 42 83 15 64 30 26 53 31 5 85 85 54 0 16 33 43 85 49 77 81 7 74 12 13 11 27 78 85 29 37 28 43 35 38 88 95 49 32 15 86 32 81 63 97 39 22 5 86 96 22 33 1 18 52 91 44 40 95 45 7 69 86 28 78 51 38 16 6 55 10 53 87 16 40 35 37 40 51 72 31 0 92 50 71
========
7
<<<<<<<<

>>>>>>>> 03
10
45 18 31 80 64 32 17 18 27 36 1 53 80 84 51 43 47 98 36 41 51 92 30 23 75 77 39 62 33 10 91 6 100 85 70 14 99 71 89 7 27 37 56 24 100 34
60 6 25 5 94 84 9 23 28 7 83 14 89 78 25 45 88 56 74 15 87 21 75 45 93 71 19 91 19 2 35 23 51 38 39 84 51 13 38 11 85 22 100 95 30 93 93 63 27 63 15 42 17 24 59 5 28 13 67 71 94
88 100 110 106 108 106 107 105 101 105 104 105 106 107 100 102 100 107 100 101 100 106 106 101 107 108 106 107 107 110 105 103 101 107 108 103 109 100 109 105 104 106 101 104 101 107 109 107 105 105 105 101 102 106 108 103 100 103 103 102 108 107 110 101 101 106 105 105 100 109 109 104 109 105 101 102 107 106 102 105 101 104 105 103 100 107 103 105 104
67 104 109 104 100 105 106 104 102 105 109 104 110 102 108 102 100 109 108 102 105 110 100 107 109 108 106 103 102 102 107 101 104 102 109 110 100 103 108 109 101 105 104 101 110 100 101 103 107 102 104 108 108 106 104 106 107 101 107 105 105 100 105 100 109 106 104 101
59 102 110 101 101 102 102 107 101 110 105 109 107 100 100 102 103 100 101 105 102 109 103 108 106 110 103 108 104 105 102 110 110 106 107 109 105 103 106 107 107 100 105 107 106 106 102 100 103 109 106 108 103 107 102 106 101 102 106 109
99 31 40 36 65 81 62 91 98 31 10 0 58 72 31 43 28 3 7 36 81 99 69 56 82 75 94 26 93 31 99 79 28 100 59 13 22 46 7 92 35 69 62 28 28 96 15 40 40 64 20 48 4 38 75 65 34 83 33 28 47 33 7 74 26 64 35 38 2 56 32 51 91 57 23 66 58 72 32 55 37 37 27 50 52 94 76 50 47 19 84 10 52 30 10 5 95 22 64 83
34 92 94 99 97 95 96 91 90 91 96 94 91 92 91 92 98 91 90 94 100 96 95 92 90 93 95 99 90 94 90 95 93 92 94
27 71 85 60 32 10 97 49 14 10 8 69 84 81 35 55 73 80 22 18 20 19 86 78 61 27 80 52
54 91 94 94 92 99 100 97 96 96 100 96 91 99 97 94 91 94 99 96 95 93 100 96 98 95 98 95 94 95 91 100 97 98 96 98 100 98 99 96 100 95 92 97 95 99 90 96 90 94 96 96 96 93 96
82 100 103 109 100 103 104 106 108 102 101 105 108 109 104 103 101 107 110 103 110 109 106 103 108 110 106 107 109 106 110 109 105 107 109 103 109 109 103 106 106 100 108 107 104 110 110 108 101 104 110 110 107 107 107 103 106 102 109 103 103 105 108 106 104 100 104 109 100 108 101 102 104 106 103 106 107 107 110 103 105 108 106
========
7
<<<<<<<<
--->