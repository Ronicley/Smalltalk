# Smalltalk

## Hello World:

- Transcript show: 'Hello World'.

---
## Comandos para manipulação do Transcript:

- Transcript clear.
- Transcript cr.

---

## Declaração de Variável:

- |variavel|
- variavel := valor desejado .
- variavel := #(x y z) .
---

## Condicional:

ifTrue e ifFalse

- comparação ifTrue: [ Ação se a comparação for verdadeira ] .
- comparação ifFalse: [ Ação se a comparação for falsa ] .

---

## Laço de repetição:

whileTrue, whileFalse, timesRepeat, to do, to do by e array do

- whileTrue --> [ comparação ] whileTrue: [ Iteração se a comparação for verdadeira ] .
  * EX: |x|. x:= 3. [x>0] whileTrue: [Transcript cr show: x. x:= x-1.].
- whileFalse --> [ comparação ] whileFalse: [ Iteração se a comparação for falsa ] .
  * EX: |x|. x:= 3. [x<0] whileFalse: [Transcript cr show: x. x:= x-1.].
- timesRepeat --> numero de vezes a repetir timesRepeat: [ Ação ] .
  * EX: 10 timesRepeat: [ Transcript show: 'Exemplo'; cr. ] .
- to do --> numero para começar a repetição to: ultimo numero da repetição do: [:numero da vez| Iteração] .
  * EX: 0 to: 10 do: [:i| Transcript show: i; cr.] .
- to do by --> numero para começar a repetição to: ultimo numero da repetição do: quantidade de passo da repetição [:numero da vez| Iteração] .
  * EX: 0 to: 10 by: 2 do: [:i| Transcript show: i; cr].
