## Francês é Fresco
### Juntar palavras

![]( cover.jpg)

## Motivação

Já percebeu que, ao final de uma palavra, quando temos uma vogal que combina com a próxima palavra nós juntamos as duas?

Isso tem um nome legal, em francês se chama **liaison**. Em português eu acho que não tem um nome legal assim.

## Ação

Que tal fazer um código que faz isso? Dado uma entrada de texto (max 100 char), apenas com minúsculo e espaço, faça o liaison das palavras. Há apenas um espaço entre as palavras e não existe espaço no começo ou fim da frase.

Se tiver 3 ou mais vogais juntas, então junte todas. 

**Exemplos:** 

amo o orvalho -> amorvalho

o gago disse e e e eu te amo -> o gago disseu te amo

### Entrada

*   Um texto. (max 100 char)

### Saída

*   O liaison das palavras.

## Exemplos

```
>>>>>>>>
a porta amassou
========
a portamassou
<<<<<<<<

>>>>>>>>
carla almeida alencar
========
carlalmeidalencar
<<<<<<<<

>>>>>>>>
a carla a ama
========
a carlama
<<<<<<<<

>>>>>>>>
o orvalho ouviu uniformemente e eu uivei
========
orvalhouviuniformementeuivei
<<<<<<<<
```

#
