# Desafio Resto da Divisão:
Escreva um programa que leia 2 valores X e Y e que imprima todos os valores entre eles cujo resto da divisão dele por 5 for igual a 2 ou igual a 3.

## Entrada
O arquivo de entrada contém 2 valores positivos inteiros quaisquer, não necessariamente em ordem crescente.

## Saída
Imprima todos os valores conforme exemplo abaixo, sempre em ordem crescente.
 
## solução:
```
X = int(input())  
Y = int(input())  

if (Y > X):  
    for i in range(X + 1, Y ):  
      if (i % 5 == 2) or (i % 5 == 3):  
        print(i)  
elif (X > Y):  
    for i in range(Y + 1, X):  
      if (i % 5 == 2) or (i % 5 == 3):  
        print(i)  

```
