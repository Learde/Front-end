# Fonts
Разница между шрифтами с засечками и без:

![fonts](https://www.w3schools.com/css/serif.gif)

## Font Family
Свойство `font-family` устанавливает шрифт. Если шрифтов несколько (не загрузился один, шрифт переключается на второй), они указываются через запятую. Если название шрифта состоит из несколько слов, то название шрифта заключается в кавычки.

## Font Style
Свойство `font-style` зачастую используется для установления наклонного шрифта (значение *italic*).

## Font Size
Свойство `font-size` устанавливает размер шрифта. Задавать можно абсолютные и относительные размеры.

### Размер в px
Можно установить размер шрифта в px. Это абсолютный размер, пользователь не может изменять размер текста.

### Размер в em
А можно установить размер шрифта в em. 1em = 16px, значит, что универсальная формула для высчитывания значения в em: `pixels/16=em`. Это относительный размер шрифта.

## Font Weight
Свойство `font-weight` часто используется для установления жирного шрифта (значение *bold*)

## "Отзывчивый" размер шрифта
Возможно устанавливать шрифт в `vw`. 1vw = 1% от ширины страницы. То есть размер будет изменяться, относительного размера окна браузера.

## Font Variant
Свойство `font-variant` определяет, должен ли текст отображаться в прописных буквах. (значение *small-caps*)
