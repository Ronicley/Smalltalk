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

- whileTrue --> [ comparação ] whileTrue: [ Interação se a comparação for verdadeira ] .
* EX: |x|. x:= 3. [x>0] whileTrue: [Transcript cr show: x. x:= x-1.].
- whileFalse --> [ comparação ] whileFalse: [ Interação se a comparação for falsa ] .
* EX: |x|. x:= 3. [x<0] whileFalse: [Transcript cr show: x. x:= x-1.].
