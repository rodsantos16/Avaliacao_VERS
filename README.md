# Avaliacao_VERS
#Considerando a matriz abaixo, crie um laço for para calcular a média de uso de CPU por linha e imprima os resultados com 2 casas decimais

uso_cpu = [[20, 25, 40, 50, 45, 60, 55, 35, 70, 65],[30, 35, 50, 60, 40, 55, 60, 45, 50, 55],[15, 20, 30, 25, 35, 40, 45, 50, 55, 60],[10, 15, 25, 35, 45, 50, 55, 60, 65, 70]]

for linha in range(len(uso_cpu)):
  for coluna in range(len(uso_cpu[linha])):
    print(f'[{uso_cpu [linha] [coluna]}]', end='')
  print()

  media_linha_1 = 0
for coluna in range(len(uso_cpu[0])):
  media_linha_1 += uso_cpu[0] [coluna] / (len(uso_cpu[0]))
print(f'A média dos valores primeira linha é {media_linha_1}')

media_linha_2 = 0
for coluna in range(len(uso_cpu[1])):
  media_linha_2 += uso_cpu[1] [coluna] / (len(uso_cpu[1]))
print(f'A média dos valores segunda linha é {media_linha_2}')

media_linha_3 = 0
for coluna in range(len(uso_cpu[2])):
  media_linha_3 += uso_cpu[2] [coluna] / (len(uso_cpu[2]))
print(f'A média dos valores segunda linha é {media_linha_3}')

media_linha_4 = 0
for coluna in range(len(uso_cpu[3])):
  media_linha_4 += uso_cpu[3] [coluna] / (len(uso_cpu[3]))
print(f'A média dos valores segunda linha é {media_linha_4}')


#Crie uma função chamada alerta_uso que recebe como parâmetro uma lista com os valores de uso de CPU de uma região. 
#A função deve retornar True se algum valor ultrapassar 85% de uso, e False caso contrário. Teste a função para todas as regiões da matriz.


regiao1 = []
for linha in uso_cpu:
    regiao1.append(linha[0])

print(regiao1)
