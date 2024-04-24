## Tipos primitivos
>dica: utilizar comando psvm + alt para gerar classe main.

Nós temos 8 tipos primitivos em Java, os tipos primitivos indicam o **tipo da variável** e quanto de memória ela precisará alocar.

- int, double, float, char, byte, short, long e boolean.

São declarados em letra minúscula:

```java
int idade = 26;

```
## Convenção de nomes de variáveis

- Na criação de variáveis a primeira letra do nome da variávei deverá ser minúscula e as seguintes palavras devem começar com letra maiúscula.

 Exemplo:

```java
public class Aula02TiposPrimitivos{
    public static void main(String[]args){
       int idadeDoUsuario = 27; 
    }
}
```
- O nome não deve conter espaços em brancos.
- O nome não deve começar com caracteres especiais.

## Casting

Na linguagem Java nós podemos atribuit um novo tipo para uma variável, isso é chamado de casting.

Exemplo:

```java
public class Aula02TiposPrimitivos{
    public static void main(String[]args){
       int idadeDoUsuario = (float) 27; 
    }
}
```
>Aqui nós alteramos um inteiro para o float.

