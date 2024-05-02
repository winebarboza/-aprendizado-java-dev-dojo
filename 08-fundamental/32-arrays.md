# Arrays[]

Array é uma variável que armazena um conjunto de dados com quantidade fixa.

>Arrays são considerados objetos na memória

A declaração de um Array em Java é feita com a definição do seu tipo, o nome dado ao Array e também a sua inicialização com a quantidade de espaços que serão alocados na memória.

>Não se pode dar um new em arrays de tipos primitivos.

```java
String nomes = new String[4]; //Array do tipo String que armazena 3 nomes.

nomes[0] = "José"; //agora a posição 0 do array nomes terá o valor "José"
```
Também podemos declarar um Array e definir a quantidade de valores que ele terá depois:

```java

String [] nomes;

String nomes = {"José", "Rafaela","Carla Rayane", "Marcus"};

```
Acessando um elemento do Array nomes:

>Você não pode acessar uma posição que não existe

```java
System.out.println(nomes[0]); //José

```

## Valores de inicialização do tipo de Array

- Para arrays de tipos primitivos byte, short, long, float e int: 0

- Para arrays do tipo char: ' ' que indica um *espaço em branco*.

- Para boolean o valor de inicialização é: false.

- Para String o valor é: null.

## Arrays - Dinâmicos

Arrays possuem tamanhos fixos e não podem ser aumentados ou diminuídos uma vez declarados.

## Foreach

Normalmente, usamos a estrutura for-each para que o laço for percorra todo o array, — essa é uma das suas principais funcionalidades, ele basicamente funciona da mesma forma que o laço for.

A sintaxe do Java forEach loop consiste na identificação do tipo de estrutura dos dados utilizados, seguidos por dois pontos (:) — posteriormente, usamos a identificação do array ou da coleção que queremos utilizar, assim:
```java
for(<Tipo> <identificação> : <array ou coleção>) {
        <comando>
}
```

*Sintaxe:*
```java
int[] numero ={1,2,3,4};

for(int num: numeros){
    System.out.println(num)
}
```