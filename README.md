##Integer1◦
##. Дано расстояние L в сантиметрах. Используя операцию деления
##нацело, найти количество полных метров в нем (1 метр = 100 см).
##L = int(input("ведите число"))
##meters = L // 100
##print("Полных метров", meters)

##Integer2◦
##. Дана масса M в килограммах. Используя операцию деления нацело,
##найти количество полных тонн в ней (1 тонна = 1000 кг).

##N = int(input("ведите число"))
##kilo = N // 1000
##print("Киллограмм", kilo)

##Integer3◦
##. Дан размер файла в байтах. Используя операцию деления нацело,
##найти количество полных килобайтов, которые занимает данный файл
##(1 килобайт = 1024 байта).

##L = int(input("ведите число"))
##bait = L // 1024
##print("Полных байт", bait)

##Integer4◦
##. Даны целые положительные числа A и B (A > B). На отрезке длины A размещено максимально возможное количество отрезков длины B
##(без наложений). Используя операцию деления нацело, найти количество
##отрезков B, размещенных на отрезке A.
##A = int(input("ведите число"))
##B = int(input("ведите число"))
##if A > B:
##    T = A/B
##    print("T = ", T)

##Integer5◦
##. Даны целые положительные числа A и B (A > B). На отрезке длины A
##размещено максимально возможное количество отрезков длины B (без
##наложений). Используя операцию взятия остатка от деления нацело, найти
##длину незанятой части отрезка A.
##A = int(input("A = "))
##B = int(input("B = "))
##T = A%B
##print('T = ', T)

##Integer6◦
##. Дано двузначное число. Вывести вначале его левую цифру (десятки), а затем — его правую цифру (единицы). Для нахождения десятков
##использовать операцию деления нацело, для нахождения единиц — операцию взятия остатка от деления.

##number = int(input("ведите число"))
##digit10 = number // 10
##digit1 = number % 10
##print("Десятки", digit10)
##print("Единицы", digit1)

##Integer7◦
##. Дано двузначное число. Найти сумму и произведение его цифр
##number = int(input("ведите число"))
##digit10 = number // 10
##digit1 = number % 10
##T = digit10*digit10
##N = digit10+digit10
##print("T = ", T)
##print("N = ", N)

## Дано трёхзначное число. Вывести его цифры по отдельности.
##number = int(input("ведите число"))
##digit1 = number % 10
##print("Единицы", digit1)
##number = number // 10
##digit10 = number % 10
##print("Десятки", digit10)
##number = number // 10
##digit100 = number % 10
##print("Сотни", digit100)
##number = number // 10

##Integer8◦
##. Дано двузначное число. Вывести число, полученное при перестановке цифр исходного числа.
##N = int(input("ведите число"))
##d1 = N%10
##N = N//10
##d10 = N%10
##T = d1*10+d10
##print("T", T)

##Integer9◦
##. Дано трехзначное число. Используя одну операцию деления нацело,
##вывести первую цифру данного числа (сотни).
##N = int(input("ведите число"))
##T = N // 100
##print("T", T)

##Integer10◦
##. Дано трехзначное число. Вывести вначале его последнюю цифру
##(единицы), а затем — его среднюю цифру (десятки).
##number = int(input("ведите число"))
##digit1 = number % 10
##print("Единицы", digit1)
##number = number // 10
##digit10 = number % 10
##print("Десятки", digit10)
##number = number // 10

##Integer11◦
##. Дано трехзначное число. Найти сумму и произведение его цифр.
##number = int(input("ведите число"))
##digit1 = number % 10
##number = number // 10
##digit10 = number % 10
##number = number // 10
##digit100 = number % 10
##number = number // 10
##S = digit1+digit10+digit100
##N = digit1*digit10*digit100
##print("S", S)
##print("N",N)

##Integer12◦
##. Дано трехзначное число. Вывести число, полученное при прочтении исходного числа справа налево.

##number = int(input("ведите число"))
##digit1 = number % 10
##number = number // 10
##digit10 = number % 10
##number = number // 10
##digit100 = number % 10
##number = number // 10
##S = digit100+digit10*10+digit1*100
##print("S", S)

##Integer13◦
##. Дано трехзначное число. В нем зачеркнули первую слева цифру и
##приписали ее справа. Вывести полученное число.







