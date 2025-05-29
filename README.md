# Функция возведения числа в куб
def step3(number):
  # n = number * number * number 
  return number ** 3  # # возвращать полученное число number в кубе

numbers = [1, 2, 4, 5, 8]
numbers_step3 = [] # [1, 8, 64, 125, 512]
for num in numbers:
  num_step3 = step3(num)
  numbers_step3.append(num_step3)
print(numbers_step3) # [1, 8, 64, 125, 512]
