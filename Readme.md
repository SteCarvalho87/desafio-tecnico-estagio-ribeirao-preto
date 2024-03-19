# Teste técnico para vaga de Estágio Ribeira Preto 2024 na Job Rotation

Desafios técnicos de lógica de programação. Cada pasta do repositório contém a resolução do desafio com o número correspondente. São eles: 

1) Observe o trecho de código abaixo:
```
int INDICE = 13, SOMA = 0, K = 0;

enquanto K < INDICE faça

{

K = K + 1;

SOMA = SOMA + K;

}

imprimir(SOMA);
```
Ao final do processamento, qual será o valor da variável SOMA?<br>
O valor de SOMA será 91.
<br>
<br>
<br>

2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.<br>
IMPORTANTE:
Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;

<br>
<br>
<br>

3) Descubra a lógica e complete o próximo elemento:
a) 1, 3, 5, 7, 9 - números ímpares <br>
b) 2, 4, 8, 16, 32, 64, 128 - o número seguinte é o número atual somado a ele mesmo<br>
c) 0, 1, 4, 9, 16, 25, 36, 49 - o número atual somado ao próximo número ímpar(0+1,1+3,4+5,9+7,16+9,25+11,36+13)<br>
d) 4, 16, 36, 64, 100 - o número 4 multiplicado pela sequencia anterior <br>
e) 1, 1, 2, 3, 5, 8, 13 - sequencia fibonacci <br>
f) 2,10, 12, 16, 17, 18, 19, 200 - os nomes começam com a mesma letra <br>

<br>
<br>
<br>

4) Você está em uma sala com três interruptores, cada um conectado a uma lâmpada em uma sala diferente. Você não pode ver as lâmpadas da sala em que está, mas pode ligar e desligar os interruptores quantas vezes quiser. Seu objetivo é descobrir qual interruptor controla qual lâmpada.
Como você faria para descobrir, usando apenas duas idas até uma das salas das lâmpadas, qual interruptor controla cada lâmpada?

Acendo o 1º interruptor e deixo uns minutos aceso. Depois apago e acendo o 2º interruptor. <br>
Visita nº1:
- se a lampada estiver acesa corresponde ao 2º interruptor;
- se a lampada estiver quente e apagada corresponde ao 1º interruptor
- se a lampada estiver apagada e fria, corresponde ao 3º interruptor.

Visita nº2: 
- Se eu tiver descoberto o 2º interruptor, basta verificar se está quente ou fria para descobrir os outros 2;
- Se eu tiver descoberto o interruptor nº1, basta verificar se está acesa ou apagada.
- Se eu tiver descoberto o interruptor nº 3, basta verificar se está acesa ou apagada.


<br>
<br>
<br>

5) Escreva um programa que inverta os caracteres de um string.
IMPORTANTE:
a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;<br>
b) Evite usar funções prontas, como, por exemplo, reverse;<br>

## Tecnologias utilizadas

* [Linguagem-C](https://learn.microsoft.com/pt-br/cpp/c-language/?view=msvc-170)

## Dependencias utilizadas

[CodeBlocks:](https://www.codeblocks.org/downloads/) para edição dos arquivos em C.<br>
[Visual-Studio-Code:](https://code.visualstudio.com/download) Para edição e leitura das demais linguagens.<br>


## Como rodar o projeto

<strong>Desafios em C:</strong> Basta clicar 2 vezes no arquivo com final ".exe" para ver a execução do programa. O código pode ser visualizado com o Visual Studio Code ou utilizando o aplicativo CodeBlocks.<br>