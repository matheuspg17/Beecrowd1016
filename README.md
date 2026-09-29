# Resolução exercício Beecrowd1016

## Descrição do problema
Dois carros (X e Y) partem em uma mesma direção. O carro X sai com velocidade constante de 60 Km/h e o carro Y sai com velocidade constante de 90 Km/h.

Em uma hora (60 minutos) o carro Y consegue se distanciar 30 quilômetros do carro X, ou seja, consegue se afastar um quilômetro a cada 2 minutos.

Leia a distância (em Km) e calcule quanto tempo leva (em minutos) para o carro Y tomar essa distância do outro carro.

## Como Funciona
1. O usuário insere a distância desejada (`dist`) como um número inteiro.
2. O código calcula o tempo multiplicando a distância por 2 (`dist * 2`), dado que cada quilômetro de afastamento leva exatamente 2 minutos.
3. O resultado obtido é armazenado na variável `minutos`.
4. O programa imprime o valor calculado e o concatena com o texto `" minutos"`.
