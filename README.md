# 🔢 Construyendo una calculadora del área de un polígono
Desarrollando una herramienta que permita calcular el área, el perímetro y la diagonal de diferentes polígonos.

Este código define dos clases: Rectangle y Square. La clase Rectangle permite calcular área, perímetro, diagonal, mostrar una representación con asteriscos, y determinar cuántas veces otro rectángulo cabe dentro. También se pueden modificar sus dimensiones. La clase Square hereda de Rectangle y ajusta sus métodos para que ancho y alto siempre sean iguales, manteniendo la definición de un cuadrado.

## ▭Rectangle
rect = Rectangle(4, 6)  # Crea un rectángulo de ancho 4 y alto 6  
print(rect)  # Rectangle(width=4, height=6)  

set_width  
rect.set_width(10)  
print(rect)  # Rectangle(width=10, height=6)

set_height  
rect.set_height(3)  
print(rect)  # Rectangle(width=10, height=3)

get_area  
print(rect.get_area())  # 10 * 3 = 30  

get_perimeter  
print(rect.get_perimeter())  # 2 * (10 + 3) = 26


get_diagonal  
print(rect.get_diagonal())  # √(10² + 3²) ≈ 10.44

get_picture  
small_pic = Rectangle(5, 2)  
print(small_pic.get_picture())  
``` *****  ```  
``` *****  ```  

get_amount_inside  
outer = Rectangle(10, 10)  
inner = Rectangle(2, 5)  
print(outer.get_amount_inside(inner))  # (10//2)*(10//5) = 5 * 2 = 10


## 🔲Square
sq = Square(5)  
Crea un cuadrado con lado 5  
print(sq)  # Square(side=5)

set_side  
sq.set_side(7)  
print(sq)  # Square(side=7)

set_width (también modifica la altura)  
sq.set_width(3)  
print(sq)  # Square(side=3)

set_height (también modifica el ancho)  
sq.set_height(6)  
print(sq)  # Square(side=6)

## :bar_chart: Resultado Final
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Construyendo-una-calculadora-del-area-de-un-poligono/main/images/calculadora-area-poligino.PNG">
</div>
<br>

