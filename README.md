# Verificacao-Proteina
Este programa em Java recebe uma fita de DNA e retorna se esta é uma proteína ou não, com base nas seguintes informações: 

O genoma de um organismo armazena todas as informações genéticas necessárias para construir e manter esse organismo. É o conjunto completo de DNA do organismo.
O DNA é composto por uma série de nucleotídeos abreviados como:
A: Adenina\n
C: Citosinan\n
G: Guanina\n
T: Timina\n
Então, uma fita de DNA pode parecer algo como ACGAATTCCG.
Uma proteína tem as seguintes qualidades:
1. Contém um "códon": ATG.
2. Termina com um "códon de parada": TGA.
3. Entre eles, cada códon adicional é uma sequência de trêsnucleotídeos.
Por exemplo:
ATGCGATACTGA é uma proteína porque tem o códon de início ATG, o códon de parada TGA e o comprimento é divisível por 3.
ATGCGATAGA não é uma proteína porque o comprimento da sequência não é divisível por 3, então a terceira condição não é satisfeita.
