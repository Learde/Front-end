# Рамки
## Border Style
Свойство `border-style` определяет то, какой тип рамок будет отображен.

Существуют следующие значения:
* dotted
* dashed
* solid
* double
* groove
* ridge
* inset
* outset
* none
* hidden

## Border Width
Свойство `border-width` определяет ширину всех четырёх рамок.

Это свойство может иметь четыре значения для каждой стороны (задаются в следующем порядке: верхняя рамка, правая рамка, нижняя рамка, левая рамка)

## Border Color
Свойство `border-color` задаёт цвет рамки.

Может иметь следующие значения:
* Доступные названия цветов
* HEX значение
* RGB значение
* transparent (прозрачный цвет)

Можно задать четыре значения, логика такая же, как и у `border-width`.

## Индивидуальные свойства для каждой из сторон
Все вышеописанные свойства можно задавать отдельно для каждой из сторон. Для этого необходимо после `border-` написать название одной из сторон. Пример:
```css
p {
    border-top-style: dotted;
    border-right-style: solid;
    border-bottom-style: dotted;
    border-left-style: solid;
}
```

## Короткая запись
Следующие три свойства можно записать через пробел в одно - `border`:
* `border-width`
* `border-style`
* `border-color`

Пример:
```css
p {
    border: 5px solid red;
}
```

Таким же образом можно задавать свойства для каждой из сторон:
```css
p {
    border-left: 6px solid red;
    background-color: lightgrey;
}
```

## Округлые рамки
Для того, чтобы сделать края округлыми - необходимо задать свойство `border-radius`:
```css
p {
    border: 2px solid red;
    border-radius: 5px;
}
```


