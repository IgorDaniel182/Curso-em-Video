# Curso-em-Video
Desafios e Exercícios do Curso em Video 

nome = input('Escreva seu nome:')
print('Olá!', nome , 'Prazer em te conhecer')

dia = input('Digite o dia em que você nasceu:')
mes = input('Digite o mes em que voce nasceu:')
ano = input('Digite o ano em que voce nasceu:')
print('Você nasceu no dia {} do mes {} do ano {}, correto?'.format(dia ,mes ,ano))

n1 = int(input('Digite um número:'))
n2 = int(input('Digite mais um número:'))
s = n1+n2
print('A soma vale:', s)

n1 = int(input('Digite um número:'))
n2 = int(input('Digite mais um número:'))
s = n1+n2
#print('A soma entre', n1 , 'e' , n2 ,'é:', s )
print('A soma entre {} e {} é {}'.format(n1, n2, s))

n1 = int(input('Digite um numero:'))
n2 = int(input('Digite outro numero:'))
s = n1+n2
print('A soma dos seus numeros é:' , s,)

n = input('digite algo:')
print('oque você colocou é algo:' ,n.isupper(), 'em relacao a ser maiusculo') 
print('oque você colocou é algo:' ,n.isalnum(), 'em relacao a ser numero')
