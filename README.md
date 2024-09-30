# module-12
print('Сумма чисел.')
def summa_n():
  summa = 0
  n = int(input('Введите число: '))
  for num in range(1, n + 1):
    summa += num
  print('Я знаю, что сумма чисел от 1 до ', n, 'равна: ', summa)
summa_n()
