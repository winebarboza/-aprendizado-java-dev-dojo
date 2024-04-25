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