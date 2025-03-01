# .start
у меня появилась мотивация  для написания кода!
сам код:
import turtle

turtle.left(90)

print("У вас есть лишь 100 действий для вашего рисунка!")

for i in range(10):
    a = input("Введите одну из команд (s - вниз, w - вверх, d - вправо, a - влево):\n")

    if a == 's':
        b = int(input("Введите Кол-ич повторений: "))
        for m in range(b):
            turtle.forward(-10)
    elif a == 'w':
        b = int(input("Введите Кол-ич повторений: "))
        for m in range(b):
            turtle.forward(10)
    elif a == 'd':
        turtle.right(45)
    elif a == 'a':
        turtle.left(45)

turtle.mainloop()
