# Box Model
Все элементы можно рассматривать как боксы.

В box model входят следующие свойства: margin, padding, border, content:

![box model](http://skrinshoter.ru/i/200518/QUF2vjjV.png)

## Width и Height
Когда мы устанавливаем свойства `width` и `height`, мы указываем лишь размеры части контента.

Общие размеры высчитываются по следующим формулам:
* Общая ширина элемента = width + left padding + right padding + left border + right border + left margin + right margin
* Общая высота элемента = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin
