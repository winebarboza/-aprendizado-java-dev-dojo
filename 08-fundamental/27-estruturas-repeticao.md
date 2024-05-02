## Estruturas de Repetição

### Laço for

For – Usamos o laço for quando sabemos exatamente quantas vezes queremos repetir um bloco de instruções. Ele é constituído de seu corpo mais as seguintes partes: - Declaração e inicialização de variáveis – A declaração simples e mais comumente usada do laço for é a seguinte: for (valor inicial; teste booleano; incremento)

Exemplo: quero imprimir de 1 à 10.

```java
for( int i = 0; i>10 ; i++){
    System.out.println(i)
}
```
### While e do While

While – Usamos o laço while quando queremos repetir um bloco de instruções enquanto uma condição específica for verdadeira. Ele é constituído apenas pelo teste booleano.

Exemplo: imprimir de 1 à 10 usando while:

```java

int i = 1;
while (i <= 10) {
    System.out.println(i);
    i++;
}
```
Do-while – Usamos o laço do-while quando queremos garantir que o bloco de instruções seja executado pelo menos uma vez, mesmo que a condição seja falsa desde o início. Ele é constituído pelo corpo do loop e pelo teste booleano, com a verificação da condição ocorrendo no final.

Exemplo: imprimir de 1 à 10 usando do-while:

```java
int i = 1;
do {
    System.out.println(i);
    i++;
} while (i <= 10);
```
### Break e Continue 
break – A instrução “break” é usado em laços de repetição “while”, “do-while”, “for” e com as instruções “switch-case”. Quando usado em laço de repetição, causa uma interrupção imediata do mesmo, continuando a execução do programa na próxima linha após o laço. Isso ocorre caso a condição imposta seja atendida.

O *break* é utilizado para sair de um laço quando uma condição específica é atendida, enquanto o *continue* permite pular a iteração atual e continuar com a próxima. 