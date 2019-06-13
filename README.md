# MT_JFLAP
maquina de Turing simulando um automato de pilha no programa Jflap

# Testes
Exemplos de entrada.

## Para máquina 1

leu a empilha A leu b desempilha A

com um estado:
q1a1ea111eq1#q1a1a111a111a111q1#q1a11a111eeq1#q1a11a111eeq1#$a1a1a11a11

com mulltiplos estados:
q1a1ea111eq11#q11a1a111a111a111q11#q11a11a111eeq111#q111a11a111eeq111#$a1a1a11a11

para com palvra aceita e pilha vazia #A
q1a1ea111eq11#q11a11a111eeq111#$a1a11 

para com palavra aceita e pilha cheia #R
q1a1ea111eq11#q11a11a111a111a1111q111#$a1a11


## Para máquina 2

* Linguagem: a^nb^n - Entrada: q1a1eep1q11#q11a1p1p1p1q11#q11a11p1eeq111#q111a11p1eeq111#q111eeeef$a1a1a11a11
