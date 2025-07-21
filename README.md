#print ('Привет')
#inverter_string = 'пОРШЕ'
#print(str.swapcase(inverter_string))
#a = [1, 2, 3, 4]
#print(a)
#lang_name = 'Кабачки полезны для здоровья'
#print(lang_name[0])
#print(lang_name[10])
#print(lang_name[1])
#print(lang_name[-7])
#empty = []

#letters = list('яблоко')
#print(letters)

#vegetables = ['яблоко', 'помидоры', 'морковь']
#print(vegetables[2])
#print(vegetables[0])

#xbckf = [1,2,3]
#first, second, third = xbckf
#print(first)
#print(second)
#print(third)

#nums = [4, 2, 9, 0, 5]
#list.remove(nums,4)
#print(nums)
#list.sort(nums)
#print(nums)



#digits = (1,2,3,4,5)
#print(digits)

#letters = tuple('Машина')
#print(type(letters), letters)


#letters = ('RGB', 255,0,128)
#mode, r, g, b = letters
#print(mode, r, g, b)



#empty = dict()
#print('пЕчатаем пустой словарь:', empty)
#vegetables = dict(
#    Помидоры =6.5,
#    Огурцы=4.3,
#    Баклажаны=2.8,
#)





#print(f"Задача № 1 Snake_case -> CamelCase")
#line = "max_value_of_array"
#line_new = "".join(line.title().split("_"))
#print(line_new)

#print(f"Задача № 2 Уникальный порядок")
#list_dub = [1, 4, 2, 5, 4, 7, 4]
#list_clean = []
#for el in list_dub:
#    if el not in list_clean:
#        list_clean.append(el)
#print(list_clean)

#print(f"Задача № 3 Топ-3 продаж")
#sales = (3.4, 6.5, 1.2, 7.8, 2, 6)
#sales_sorted = sorted(sales, reverse=True)
#print(
#    tuple(
#        [
#            i
#            for i in range(len(sales))
#            if (sales[i] == sales_sorted[0])
#            or (sales[i] == sales_sorted[1])
#            or (sales[i] == sales_sorted[2])
#        ]
#    )
#)





#print(f"Задача № 4 Заказ-чек")
#cart = [
#    ("яблоко", 3, 50),
#    ("груша", 2, 80),
#    ("банан", 1, 180),
#    ("помидор", 5, 50),
#    ("огурец", 3, 90),
#]
#
#cart_dict = {}
#for product in cart:
#    cart_dict[product[0]] = product[1] * product[2]
#print(cart_dict)
#total_sum = sum(list(cart_dict.values()))
#print(total_sum)