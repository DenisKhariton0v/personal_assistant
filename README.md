# personal_assistant
#12 6 2023
bot = "ботик"
print(f"здравcтвуйте меня зовут {bot}")
name = input("как вас завут ? ")
print(f"приятно познакомится {name}")
old = int(input("сколько вам лет?"))
print(f"а через 10 лет вам будет {old + 10}")
raseuser = float(input("какой у вас рост ? "))
print(f"wow мой рост 0.53 метра вы выше меня на {raseuser - 0.53} метров")
print("Вас зовут",name,",ваш возраст",old,"ваш рост",raseuser)
answer = input("""мой функционал таков:
1 - рассказать анекдот
2 - дать совет
3 - будильник
что вы выберите?""")
if answer == "1" or answer == "рассказать анекдот":
    print("русалка захлебнулась")
elif answer == "2" or answer == "дать совет":
    answer2 = input("""на каую тему хотите совет
    1 - финансы 
    2 - жизнь 
    3 - здоровье""")
    if answer2 == "1" or answer2 == "финансы":
        print("не имей 2 рубля а имей 100 рублей")
    elif answer2 == "2" or answer2 == "жизнь":
        print("не имей 2 рубля а имей 100 рублей")
    elif answer2 == "3" or answer2 == "здоровье":
        print(
            "пока вы лежите на диванах они зарабатывают миллионы ,а как  зарабатывать на диване я расскажу в своем тг"
        )
    else:
        print("не имей 2 рубля а имей 100 рублей")

elif answer == "3" or answer == "будильник":
    print("устанавлен будильник на 34 августа")
else:
    print("eror 999 для снятия скажите 3 цифры с обратной стороны карты")
