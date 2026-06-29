#exercicio "O localizador de duplicatas"

numeros = []
for i in range(6): #basicamente ira "girar" ate o numero determinado em ()
    numero = int(input("Digite o {i+1} . numero: "))
    numeros.append(numero) 

#outra forma de fazer o codigo acima ^
#numeros = [int(input("Digite o {i+1} . numero: ")) for i in range(6)]

x = int(input("\nQual o numero deseja pesquisar?"))
ocorrencias = numeros.count(x)
print("-"*30)
if ocorrencias > 0:
    print(f"O numero {x} aparece `{ocorrencias} vez(es) na lista.") 
    print(f"Sua primeira aparição foi no índice: {numero.index(x)}")
else:
    print(f"O numero {x} nao foi encontrado na lista.")
