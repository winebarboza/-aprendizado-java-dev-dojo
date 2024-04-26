## Estrutura condicional -IF

A estrutura condicional if é uma condição que traduzindo para o português significa "se".
Ela determina o que o será executado de acordo com a condição estabelecida pelo dev, exemplo:

**"Se chover, não irei pra escola"**

```java
boolean chover = true;
if(chover == true){
    System.out.println("não irei pra escola")
}

```
### Estrutura Else

Essa estrutura é executada caso a condição não caia no if.

**"Se chover, não irei pra escola, não choveu? irei pra escola"**

```java
boolean chover = true;
if(chover == true){
    System.out.println("não irei pra escola");
}else{
    System.out.println("Irei pra escola");
}
```
### Operador ternário

Operador ternário é uma estrutura condicional simples.

- (boolean)? bloco de código 1 : bloco de código 2.

```java 
Int projetos = 10;
String msg = projetos < 20? "Você fez muitos projetos!" : projetos > 20? "Você fez poucos projetos";
```
> However, please note that it’s not recommended to use such deeply nested ternary constructs in the real world. This is because it makes the code less readable and difficult to maintain.

### Switch case

Estrutura condicional que testa condições de forma simples.

```java
import java.util.Scanner;
public class Switch {
 public static void main(String[] args) {
  Scanner entrada = new Scanner(System.in);
  System.out.println("Digite o número referente ao mês desejado");
  int numero = entrada.nextInt();
   switch (numero) {
     case 1:
       System.out.println("O mês é Janeiro!");
       break;
     case 2:
       System.out.println("O mês é Fevereiro!");
       break;
     case 3:
       System.out.println("O mês é Março!");
       break;
     case 4:
       System.out.println("O mês é Abril!");
       break;
     case 5:
       System.out.println("O mês é Maio!");
       break;
     case 6:
       System.out.println("O mês é Junho!");
       break;
     case 7:
       System.out.println("O mês é Julho!");
       break;
     case 8:
       System.out.println("O mês é Agosto!");
       break;
     case 9:
       System.out.println("O mês é Setembro!");
       break;
     case 10:
       System.out.println("O mês é Outubro!");
       break;
     case 11:
       System.out.println("O mês é Novembro!");
       break;
     case 12:
       System.out.println("O mês é Dezembro!");
       break;
     default:
       System.out.println("Não existe um mês correspondente ao número escolhido! Digite um número entre 1 a 12.");
    }
  }
}
```