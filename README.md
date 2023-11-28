# ImportacaoeFuncao.py

#Eu criei o formulário e o pacote no python, com funções , importando os dados necessários para a resposta que o usuário desejava.
from precos import funcoes
valor= float(input('Digite o preço:'))
print(f'O dobro do preço é: {funcoes.dobro(valor)} ')
print(f'A metade do preço é: {funcoes.metade(valor)}')
print(f'10% a mais no preço é:{funcoes.aumentar(valor)}')
print(f'Se retirarmos 13% do preço o resultado é: {funcoes.retirar(valor)}')

#As funções eram:

def dobro (moeda_d):
    return moeda_d * 2
def metade (moeda_m):
    return moeda_m / 2
def aumentar (moeda_a):
    return moeda_a + ( moeda_a * 10 / 100)
def retirar (moeda_r):
    return moeda_r  - (moeda_r)
