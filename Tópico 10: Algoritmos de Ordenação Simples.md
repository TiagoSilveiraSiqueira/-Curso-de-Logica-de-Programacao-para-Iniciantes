# Explicação:
Algoritmos de ordenação são usados para organizar uma lista de itens em uma determinada ordem. <br /> 
Um exemplo simples é o algoritmo de bolha. <br /> 
Ele compara os pares de itens adjacentes e os troca até que a lista esteja ordenada.

# Exemplo de Código (Algoritmo de Bolha):

def ordenar_bolha(lista):<br /> 
    n = len(lista)<br /> 
    for i in range(n):<br /> 
        for j in range(0, n - i - 1):<br /> 
            if lista[j] > lista[j + 1]:<br /> 
                lista[j], lista[j + 1] = lista[j + 1], lista[j]<br /> 

# Exemplo de uso
numeros = [64, 34, 25, 12, 22, 11, 90]<br /> 
ordenar_bolha(numeros)<br /> 
print("Números ordenados:", numeros)<br /> 

Este código ordena uma lista de números usando o algoritmo de bolha.<br /> 

# Exercício:
Tente criar uma função que ordene uma lista de palavras em ordem alfabética.
