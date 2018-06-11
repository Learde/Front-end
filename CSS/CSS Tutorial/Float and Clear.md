# Float and clear
## Float
Свойство `float` определяет, по какой стороне будет выравниваться элемент, при этом остальные элементы буду тего обтекать с других сторон.

Может иметь следующие значения:
* left - Выравнивает элемент по левому краю. Остальные элементы обтекают его по правой стороне.
* right - Выравнивает элемент по правому краю. Остальные элементы обтекают его по левой стороне.
* none - Обтекание и выравнивание не задаётся.
* inherit - Наследует значение родителя.

## Clear
Свойство `clear` устанавливает, с какой стороны элемента запрещено обтекание другими элементами.

Может иметь следующие значения:
* none - Обтекание работает с правого и левого края.
* both - Обтекание отключается одновременно с правого и левого края.
* left - Отменяет обтекание с левого края.
* right - Отменяет обтекание с правого края.
* inherit - Наследует значение родителя.

## Clearfix
При использовании `float`, иногда возникают различные проблемы, такие как: схлопывание блоков, "плавающие" элементы, иногда блоки не расширяются и прочее. Для решение многих проблем существует clearfix.

Код clearfix'a:
```CSS
.clearfix:after {
    content: "";
    display: table;
    clear: both;
}
```