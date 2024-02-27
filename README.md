# -5
Задание №2 Урок №5 Логические и  условные операторы
word = input("Введите слово из маленьких латинских букв: ")
vowels = "aeiou"
consonants = 0
vowels_count = 0
has_a = False  
has_e = False
has_i = False 
has_o = False
has_u = False
for ch in word:
  if ch in vowels:
    vowels_count += 1
    if ch == 'a':
      has_a = True
    elif ch == 'e':
      has_e = True  
    elif ch == 'i':
      has_i = True
    elif ch == 'o':
      has_o = True
    elif ch == 'u':
      has_u = True
  else:
    consonants += 1
print("Количество гласных букв:", vowels_count)
print("Количество согласных букв:", consonants)
print("Буква a:", has_a)  
print("Буква e:", has_e)
print("Буква i:", has_i)
print("Буква o:", has_o)
print("Буква u:", has_u)
