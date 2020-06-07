# Learning-Python
'''
Repositório para aprendizado de Python

Iniciando no mundo do Python com os primeiros comandos
para me familiarizar com a linguagem e na utilização do
GitHub.
'''

print("hello world")


#manipulando 'listas'
 'Marcus'
lista = [1,34,'string',nome,[1,2,3]]
print(lista[0])
print(lista[1])
print(lista[2])
print(lista[3])
print(lista[4])

lista = ["casa","carro","comida"]
print(lista)
lista[1] = "camelo"
print(lista)
print(lista + [1,2,3])
print(lista * 2)
print('casa' in lista)
print('carro' in lista)

print(lista)
lista.append('carro')
print(lista)
print(len(lista))
lista.insert(0, "camisa")
print(lista)

print(lista.index("comida"))
print(max(lista))
print(min(lista))
print(lista.count('comida'))
lista.remove('comida')
print(lista)
lista.reverse()
print(lista)

numeros = list(range(2,50,4))
print(numeros)


#função 'input'
anoatual = int(input("Digite o ano atual: "))
anonasc = int(input("Digite o ano em que nasceu: "))
idade = anoatual - anonasc
idade = str(idade)
print("Você possui " + idade + " anos!")



