## Pacote ou Package

O Java é uma linguagem bastante orientada a pacotes, eles ajudam a agrupar as classes que possuem coisas em comum.

### Convenções de nomenclatura

1. Minúsculas
Os nomes dos pacotes devem ser digitados em letra minúscula.

2. Reverse Domain Name
Utilizar o domínio da empresa ao contrário como parte do nome do pacote.

`
br.devdojo.com.my.project.models;
`
3. Evitar palavras reservadas
Evitar usar palavras reservadas da linguagem nos nomes dos pacotes.

`
//evitar
 package com.example.myproject.interface;
`
`
//preferir
package com.example.myproject.interfaces;
`

> Cada projeto possui um padrão próprio que mais atende as necessidades da equipe que está trabalhando nele, não se apegue muito a nomes pois cada empresa tem seu próprio padrão de nomenclatura.

### Criando pacotes

Para indicar que uma classe pertence a um determinado pacote, a primeira linha de código deve indicar isso da seguinte maneira:

`
package nomedopacote;

`
O nome do pacote será o que diferencia duas classes de nomes iguais vindas de pacotes diferentes, não havendo conflitos entre elas.
