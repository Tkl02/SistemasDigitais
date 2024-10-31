# Sistemas Digitais (HDL)

Este é um trabalho para apresentar a evolução do aprendizado a respeito de sistemas digitais mais especificamente na criação de HDL ou Hard Description Lenguage.

<hr>

## Sumario 
- Portas Logicas.
- Codificadores e Decodificadores.
- Multiplexadores e Demultiplexadores
- Flip-Flops.
- Contadores e Registradores.
- Conversores A/D e D/A

<hr>

## portas logicas

Quando falamos sobre portas lógicas, temos os seguintes exemplos: **AND, OR, NOT, NAND, NOR, XOR e XNOR**. Cada uma possui características específicas, com diferentes usos e aplicações. A seguir, faremos um breve resumo sobre o funcionamento e as principais utilidades de cada uma.

### Porta AND
AND
Retorna 1 (verdadeiro) apenas se todas as entradas forem 1.<br>
Exemplo: 1 AND 1 = 1; 1 AND 0 = 0.<br><br>
![](assets/Captura%20de%20tela%202024-10-30%20134812.png)  ![](assets/Captura%20de%20tela%202024-10-30%20144844.png)

### Porta OR
OR
Retorna 1 se pelo menos uma das entradas for 1.<br>
Exemplo: 1 OR 0 = 1; 0 OR 0 = 0.<br><br>
![](assets/Captura%20de%20tela%202024-10-30%20134825.png)  ![](assets/Captura%20de%20tela%202024-10-30%20144910.png)

### Porta NOT
NOT
Inverte o valor da entrada (porta unária).<br>
Exemplo: NOT 1 = 0; NOT 0 = 1.<br><br>
![](assets/Captura%20de%20tela%202024-10-30%20134926.png)  ![](assets/Captura%20de%20tela%202024-10-30%20150624.png)

### Porta NAND
NAND (NOT AND)
É o inverso da porta AND, retornando 0 apenas se todas as entradas forem 1.<br>
Exemplo: 1 NAND 1 = 0; 1 NAND 0 = 1.<br><br>
![](assets/Captura%20de%20tela%202024-10-30%20134934.png)  ![](assets/Captura%20de%20tela%202024-10-30%20150955.png)

### Porta NOR
NOR (NOT OR)
É o inverso da porta OR, retornando 1 apenas se todas as entradas forem 0.<br>
Exemplo: 0 NOR 0 = 1; 1 NOR 0 = 0.<br><br>
![](assets/Captura%20de%20tela%202024-10-30%20134940.png)  ![](assets/Captura%20de%20tela%202024-10-30%20151458.png)

### Porta XOR
XOR (Exclusive OR)
Retorna 1 se apenas uma das entradas for 1 (diferentes).<br>
Exemplo: 1 XOR 0 = 1; 1 XOR 1 = 0.<br><br>
![](assets/Captura%20de%20tela%202024-10-30%20134950.png)  ![](assets/Captura%20de%20tela%202024-10-30%20144939.png)

### Porta XNOR
XNOR (Exclusive NOR)
É o inverso da porta XOR, retornando 1 se as entradas forem iguais.<br>
Exemplo: 1 XNOR 1 = 1; 1 XNOR 0 = 0.<br><br>
![](assets/Captura%20de%20tela%202024-10-30%20134958.png)  ![](assets/Captura%20de%20tela%202024-10-30%20151740.png)

<hr>

## Codificadores e Decodificadores.

Um codificador (ou encoder) é um circuito digital combinacional que converte uma entrada ativa em um código binário correspondente. Ele possui várias linhas de entrada e algumas linhas de saída, e sua função principal é traduzir uma entrada específica em uma representação binária menor.

