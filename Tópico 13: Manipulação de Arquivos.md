# Explicação:
A manipulação de arquivos permite que você leia e escreva dados em arquivos. <br /> 
É útil para salvar informações e ler dados de arquivos existentes.

# Exemplo de Código (Leitura de Arquivo):

# Leitura de um arquivo
arquivo = open("exemplo.txt", "r")<br /> 
conteudo = arquivo.read()<br /> 
arquivo.close()<br /> 
print("Conteúdo do arquivo:")<br /> 
print(conteudo)<br /> 

Neste exemplo, lemos o conteúdo de um arquivo chamado "exemplo.txt".

# Exercício:
Tente criar um arquivo de texto, escrever algumas linhas nele e depois ler o conteúdo do arquivo.
