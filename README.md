Projeto da cadeira de Sistemas Digitais do 2° Período do CIN-UFPE, feitos pelos alunos Eduardo  Gabriel de Souza Pedroza(egsp), Mateus Rafael Correia de Melo(mrcm), Matheus Enrico Carmo dos Santos Barros(mecsb), Ryann André Dias da Silva(rads).
1 VISÃO GERAL
Aqui está o PDF, do circuito da ULA completa:

[uladefinitiva.pdf](https://github.com/user-attachments/files/21329034/uladefinitiva.pdf)

SOMADOR:
Foram usados dois condicionadores de sinal, que preparam o numero para a soma, transformando ele em uma representação em complemento de 2 apenas se for negativo.

As portas XOR decidem se o bit vai ser invertido ou não de acordo com o bit de sinal. Analisando a tabela verdade da porta XOR, quando o bit de sinal é 0, a saída vai ser o proprio bit do input. Quando a saida for 1, o bit é invertido. Exemplo 1XOR1 = 0.
Após esse processo de inversão, formando o complemento de 1 se o numero for negativo, é feita a soma com 000X, sendo X o bit de sinal, que entra como Carry IN do primeiro somador de 1 bit. Se o numero for positivo (X = 0), o número vai ser somado com 0000 e portanto não vai ser alterado.
