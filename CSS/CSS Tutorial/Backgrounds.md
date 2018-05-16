# Фон
## Цветной фон
Свойство `background-color` устанавливает цвет в качестве фона элемента:
```css
body {
    background-color: lightblue;
}
```

В качестве цвета можно использовать:
* Допустимые имена цвета - e.g. "red"
* HEX значения - e.g. "#ff0000"
* RGB значения - e.g. "rgb(255,0,0)"

## Картинка в качестве фона
Для того, чтобы использовать картинку в качестве фона элемента, необходимо использовать свойство `background-image`:
```css
body {
    background-image: url("paper.gif");
}
```

## Повторение картинок
По стандарту, `background-image` повторяет картинки по вертикали и горизонтали.

Для того, чтобы картинка повторялась исключительно по горизонтали, необходимо указать свойство `background-repeat: repeat-x;`.
Если только по вертикали: `background-repeat: repeat-y;`

Если необходимо полностью выключить повторение картинок, указываем значение `no-repeat`: `background-repeat: no-repeat;`

## Позиционирование фона
Для того, чтобы расположить фон в определённом месте, используется свойство `background-position`. Далее пример, где фон располагается в правом верхнем углу:
```css
body {
    background-image: url("img_tree.png");
    background-repeat: no-repeat;
    background-position: right top;
}
```

## Фиксированный фон
Если необходимо сделать так, чтобы фон не прокручивался вместе с элементами, указываем свойство `background-attachment` со значением `fixed`
```css
body {
    background-image: url("img_tree.png");
    background-repeat: no-repeat;
    background-position: right top;
    background-attachment: fixed;
}
```

## Короткая запись свойств
Все свойства фона, если это необходимо, можно записать в одно - в свойство `background`. Пример:
```css
body {
    background: #ffffff url("img_tree.png") no-repeat right top;
}
```
