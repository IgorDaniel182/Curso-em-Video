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

n = int(input('digite um numero inteiro: '))
n1 = n+1
n2 = n-1
print('O sucessor do número escolhido é {} e o antecessor do número escolhido é {}'.format(n1, n2))

n = float(input('Digite um numero '))
n1 = n*n
n2 = n**3
n3 = n**2
print('O dobro do seu número é:{}, o triplo do seu número é:{} e o quadrado do seu número é:{}'.format(n1, n2, n3))

n1 = float(input('Digite sua primeira nota: '))
n2 = float(input('Digite sua segunda nota: '))
s = n1+n2
d = s/2
print('A sua nota é: {}'.format(d))

n = float(input('digite um numero em metros: '))
n1 = n*100
n2 = n*1000
print('O numero transformado para centímetros é {} e o transformado em milimetros é {}'.format(n1,n2)) 

n = int(input('Digite um número: '))
n0 = n*0
n1 = n*1
n2 = n*2
n3 = n*3
n4 = n*4
n5 = n*5
n6 = n*6
n7 = n*7
n8 = n*8
n9 = n*9
n10 = n*10
print('A tabuada do seu numero é:{},{},{},{},{},{},{},{},{},{}'.format(n0,n1,n2,n3,n4,n5,n6,n7,n8,n9,n10))

n = float(input('Quanto de dinheiro você tem na sua carteira? '))
n1 = n*3.37
print('Em dólares, o dinheiro que você tem é:',s,'Dólares')

n1 = float(input('Qual a medida da largura do objeto que você quer a área? '))
n2 = float(input('Qual a medida da altura do objeto que você quer a área? '))
a = n1*n2
l = a/2
print('A quantidade litros que você vai precisar de tinta para pintar toda a área é de: ', l)

n = float(input('Digite o preço de algum produto: ')) 
n1 = n*5
n2 = n1/100
n3 = n-n2
print('O preco do produto com desconto de 5% é de: {} reais'.format(n3))n = float(input('Digite seu salário: '))
n1 = n*15
n2 = n1/100
n3 = n+n2
print('O seu salário com 15% de aumento, é de:',n3)




