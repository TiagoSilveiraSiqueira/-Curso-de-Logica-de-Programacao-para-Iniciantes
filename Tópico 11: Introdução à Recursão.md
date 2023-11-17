# Explicação:
Recursão é um conceito em que uma função pode chamar a si mesma. <br /> 
Isso é útil para resolver problemas que podem ser divididos em partes menores idênticas.<br /> 

# Exemplo de Código (Fatorial usando Recursão):

def fatorial(n):<br /> 
    if n == 0:<br /> 
        return 1<br /> 
    else:<br /> 
        return n * fatorial(n - 1)<br /> 

resultado = fatorial(5)<br /> 
print("Fatorial de 5 é", resultado)<br /> 

Neste exemplo, a função "fatorial" calcula o fatorial de um número usando recursão.<br /> 

# Exercício:
Tente criar uma função recursiva que calcule a soma dos primeiros "n" números naturais.
