# Margin
Свойство `margin` устанавливает величину отступа от каждого края элемента. Отступом является пространство от границы текущего элемента до внутренней границы его родительского элемента.

## Отступы для каждой из сторон
С помощью следующих свойств можно указать отступы для каждой из сторон:
* `margin-top`
* `margin-right`
* `margin-bottom`
* `margin-left`

Значение можно задавать следующих типов:
* auto - браузер сам высчитывает отступ
* length - значение в px, pt, cm, etc. Значение может быть как положительным, так и отрицательным числом.
* % - устанавливает отступ в процентах (от ширины родительского элемента)
* inherit - наследует значение родителя

## Короткая запись
Для сокращения кода можно собрать все четыре свойства в одно - `margin`.

Свойства записываются через пробел. Порядок слева направо: top, right, bottom, left.

Пример:
```css
p {
    margin: 25px 50px 75px 100px;
}
```

Разрешается использовать одно, два, три или четыре значения, разделяя их между собой пробелом. Эффект зависит от количества значений:

![table](http://skrinshoter.ru/i/180518/U7XpCOLw.png)

## Значение auto
Если указать значение auto, то браузер автоматически расположит элемент в центре по горизонтале.

## Проблема отступов
У двух элементов, расположенных рядом друг с другом, вертикальные отступы будут не суммироваться, а объединяться. Объединение происходит следующим образом: выбирается наибольший из отступов. Например, два отступа 20px и 50px, установится отступ к 50px.

Такая проблема не работает:
* для элементов, у которых на стороне схлопывания задано свойство `padding`;
* для элементов, у которых на стороне схлопывания задана граница;
* на элементах с абсолютным позиционированием, т.е. таких, у которых `position` установлено как `absolute`;
* на плавающих элементах (для них свойство `float` задано как left или right);
* для строчных элементов;
* для `<html>`.
