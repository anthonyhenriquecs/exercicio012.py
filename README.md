# exercicio012.py
#Escreva um programa que leia um valor em metros e o exiba convertido em centímetros e milímetros.

m = float(input('Dgite a medida: '))
cm = m * 100
mm = m * 1000
print(' EM CENTIMETROS: {:.0f} '
      'EM MILIMETROS: {:.0f}'.format(cm,mm))
