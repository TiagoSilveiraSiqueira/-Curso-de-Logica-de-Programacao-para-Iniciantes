# Explicação:
A resolução de problemas práticos é uma parte fundamental da programação. <br /> 
É onde você aplica todos os conceitos que aprendeu para criar soluções para desafios do mundo real.

# Exemplo:
Suponha que você deseje criar um programa que calcule a média de notas de estudantes. <br /> 
Você pode pedir ao usuário que insira as notas, calcular a média e exibir o resultado.

# Cálculo da média de notas de estudantes
quantidade_de_notas = int(input("Quantas notas você deseja calcular? "))<br /> 
notas = []

for i in range(quantidade_de_notas):
    nota = float(input("Insira a nota {}: ".format(i + 1)))<br /> 
    notas.append(nota)

media = sum(notas) / len(notas)<br /> 
print("A média das notas é:", media)<br /> 

Neste exemplo, o programa pede ao usuário para inserir um número de notas, coleta essas notas, calcula a média e a exibe.

# Exercício:
Pense em um problema prático que você gostaria de resolver. <br /> 
Pode ser algo relacionado à sua vida diária. <br /> 
Tente projetar um programa simples para resolver esse problema. <br /> 
Se precisar de ajuda, sinta-se à vontade para compartilhar o problema aqui, e posso ajudar na criação do programa.
