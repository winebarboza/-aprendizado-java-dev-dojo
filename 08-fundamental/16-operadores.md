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
## Operadores lógicos

Os operadores lógicos do Java são usados para criar expressões lógicas (verdadeiras ou falsas). Os operadores lógicos mais comuns são:

- "&&" 
(AND) retorna verdadeiro se ambas as expressões forem verdadeiras. 

- "||"
(OU) retorna verdadeiro se pelo menos uma das expressões for verdadeira.

- "!" 
(Não lógico): inverte o valor lógico da expressão. Exemplo: !(x < 5) retornaria verdadeiro se x não fosse menor que 5.

- "&"
(E lógico curto-circuitado): igual a &&, mas não avalia a segunda expressão se a primeira já for falsa.

- "|" 
(OU lógico curto-circuitado): igual a ||, mas não avalia a segunda expressão se a primeira já for verdadeira. Exemplo: (x < 5 | y/x > 2) se x for menor que cinco, y/x não será avaliado evitando um erro de divisão por zero.

- "^" 
(OU exclusivo): retorna verdadeiro se apenas uma das expressões for verdadeira. Exemplo: (x < 5 ^ y < 5) retornaria verdadeiro se x fosse menor que 5 ou y fosse menor que 5, mas não ambos.

## Atribuição

- **Igual ( = )**
Utilizado para atribuir valores para as variáveis.

- **Decrementa (-=)**
Utilizado para decrementar valor.
Exemplo:

```java
int bonus = 2000;
bonus -= 1000; //foi subtraído 1000 de 2000 e agora o bonus é igual à 1000.
```

- **Incrementa (+=)**
Utilizado para incrementar valor.
Exemplo:

```java
int bonus = 2000;
bonus += 1000; //foi somado 1000 à 2000 e agora o bonus é igual à 3000.
```