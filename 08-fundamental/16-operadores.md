## Aritiméticos

Operadores matemáticos básicos que temos:

- Soma representado pelo "+"
- Subtração representado pelo sinal de "-"
- Divisão representado pelo sinal de "/"
- Multiplicação representado pelo sinal de "*"

Exemplo de operação soma em Java:

```java
public static void main(String[]args){
    int macasVermelhas = 21;
    int macasVerdes = 12;
    int somaDeMacas = macasVermelhas + macasVerdes;

    System.out.println(somaDeMacas); // o resultado é 33
}
```
>O operador de "+" também é utilizado na concatenação de strings como demonstrado no exemplo a seguir:

```java
System.out.println("Maria possui "+macasVerdes+" maçãs verdes e João possui "+macasVermelhas+" maçãs vermelhas.");
```

Operador de resto é representado pelo sinal de "%".
```java
int resto = 4 % 2; //o resultado é zero, pois é o resto da divisão 4/2.

```
## Relacionais

Os operadores relacionais resultam em booleano.

- Sinais de menor que e maior que <>.

- Sinais de menor igual e maior igual <= >=.

- Sinal de igual ==.

- Sinal de diferente !=.

| Significado  | Símbolo   | 
|--------------|-----------|
|     menor    |     <     |
|     maior    |     >     |  
|  menor igual |     <=    |
|  maior igual |     >=    |
|    igual     |     ==    |
|  diferente   |     !=    |

```java
boolean isDezMaiorQueVinte = 10 > 20; //false

```