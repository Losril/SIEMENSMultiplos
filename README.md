# SIEMENSMultiplos
A solução foi realizada a partir do conhecimento de que se um número é divisível
por 3 com resto 0 então o mesmo é seu múltiplo, a condição vale para o número 5
da mesma forma. Dessa forma, se um número for divisível por ambos com resto 0
é um mútiplo comum entre eles.

Utilizei um for para criar uma lista de inteiros, pois é maneira mais rápida e
prática possível. Na lista temos 99 posições sendo i[0] = 1 e i[99] = 100.

A utilização do if, else if e else, foi necessária para que os prints fossem
executados de maneira correta, pois era preciso que houvessem condições testando 
cada posição da lista para avaliar quais números deveriam ser substituidos por 
"Foo" -múltiplos de 3-, "Baa" -múltiplos de 5- e "FooBaa" -múltiplos em comum
de 3 e 5.
