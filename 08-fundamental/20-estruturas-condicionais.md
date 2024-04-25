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
### Estrutura Else If

Essa estrutura é executada caso a condição não caia no if.

**"Se chover, não irei pra escola"**

```java
boolean chover = true;
if(chover == true){
    System.out.println("não irei pra escola");
}else{
    System.out.println("Irei pra escola");
}
```