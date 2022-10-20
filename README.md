#60 Нарисуйте квадрат
импорт  черепахи

диапазон  в  i  для (0, 4):
    черепаха.переслать(100)
    черепаха.справа(90)

turtle.exitonclick ( выход )()

#61 Нарисуйте треугольник
импорт  черепахи

диапазон  в  i  для (0, 3):
    черепаха.вперед(50)
    черепаха.справа(120)

turtle.exitonclick ( выход )()

#62 Нарисуйте круг
импорт  черепахи

черепаха.круг (100)

turtle.exitonclick()


#63 Нарисуйте в один ряд три квадрата, разбелённых промежутками.Заполните их тремя разными цветами
импорт  черепахи

turtle.setup(1800,500) #устанавливаю размер окна для рисования
turtle.color("black", "red") #устанавливаю цвет контура чёрный, цвет заливки будущей фигуры - красный
turtle.begin_fill()
диапазон  в  i  для (0, 4):
    черепаха.переслать(100)
    черепаха.справа(90)
turtle.end_fill()

range in i for(0,1): #ставлю цикл для промежутка между квадратами
    черепаха.переслать(100)
    черепаха.справа(90)
turtle.penup() #делаю перо невидемым
черепаха.переслать(100)
черепаха.слева(90)
черепаха.переслать(100)

turtle.pendown() #делаю перо видимым
turtle.begin_fill()
turtle.color("black", "yellow") #устанавливаю цвет контура чёрный, цвет заливки второй фигуры - жёлтый
диапазон  в  i  для (0, 4):
    черепаха.переслать(100)
    черепаха.слева(90)
turtle.end_fill()

черепаха.переслать(100)
turtle.penup() #делаю перо невидимым
черепаха.переслать(100)
черепаха.слева(90)

turtle.pendown() #делаю перо видимым
turtle.begin_fill()
turtle.color("black", "green") #устанавливаю цвет контура чёрный, цвет заливки третьего квадрата - зелёный
диапазон  в  i  для (0, 4):
    черепаха.переслать(100)
    черепаха.справа(90)
turtle.end_fill()

turtle.exitonclick()


#64 Нарисуйте пятиконечную звезду
импорт  черепахи

диапазон  в  i  для (5):
    черепаха.переслать(100)
    черепаха.справа(144)
turtle.exitonclick()


#65 Нарисуйте цифры, изображённые ниже, начиная от нижней точки цифры 1
импорт  черепахи

turtle.setup(1800,500) #устанавливаю размер окна для рисования
turtle.left(90) #рисуем цифру 1
черепаха.переслать(100)
черепаха.справа(90)

turtle.penup() # Делаю перо невидемым
черепаха.forward(100) #перевожу перо для рисования цифры 2

turtle.pendown() #делаю перо видимым
черепаха.переслать(100)
черепаха.справа(90)
черепаха.вперед(60)
черепаха.слева(270)
черепаха.переслать(100)
черепаха.слева(90)
черепаха.переслать(40)
черепаха.слева(90)
черепаха.переслать(100)


turtle.penup() # Делаю перо невидемым
черепаха.forward(100) #перевожу перо для рисования цифры 3

turtle.pendown() #делаю перо видимым
черепаха.переслать(100)
черепаха.слева(90)
черепаха.переслать(50)
черепаха.справа(270)
черепаха.переслать(50)
черепаха.справа(180)

turtle.penup()
черепаха.переслать(50)
черепаха.справа(270)
turtle.pendown()

черепаха.переслать(50)
черепаха.слева(90)
черепаха.переслать(100)

turtle.exitonclick()

#66 Нарисуйте 8-угольник, все стороны которого окрашены в разные цвета
# (цвета случайно выбираются из списка возможных)
импорт  черепахичерепаха
импортировать  случайным образомСлучайный

= цвет ["желтый", "синий", "красный", "зеленый", "коричневый", "фиолетовый"]

turtle.begin_fill()

диапазон  в  i  для (0, 8):
    случайное  =  число.выбор (цвет)
    черепаха.цвет (номер, "белый")
    черепаха.переслать(100)
    черепаха.справа(45)

turtle.end_fill()

turtle.exitonclick()


#67 Нарисуйте следующий узор
импорт  черепахи

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.справа(45)

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.слева(45)

черепаха.справа(90)

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.справа(45)

черепаха.справа(90)

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.слева(45)

черепаха.слева(45)

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.справа(45)

черепаха.слева(45)

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.слева(45)

черепаха.справа(90)

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.справа(45)

черепаха.слева(135)

диапазон  в  i  для (0, 8):
    черепаха.переслать(50)
    черепаха.слева(45)


turtle.exitonclick()

#68 Нарисуйте узор, который меняется при каждом запуске программы.
#Используйте функцию random для выбора количества линий, длины каждой линии и каждого угла поворота.
import  черепахи
импортировать  случайным образом

= linii [4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,30,40,50,60,70,80,90]
=  ygol [30,45,50,90,135,150,180,270,360]
=ленлин[25,50,60,70,80,90,100,120,150,130,110,140,160,170,180,190,200]

случайный = linii1.выбор(linii)
случайный = ygol1.выбор(ygol)
случайный = lenlin1.выбор(lenlin)

диапазон  в  i  для (linii1):
    черепаха.нападающий (ленлин1)
    черепаха.справа (ygol1)


turtle.exitonclick()
