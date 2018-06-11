# Overflow
Свойство `overflow` управляет отображением контента блочного элемента, если он не помещается и выходит за края элемента.

Свойство имеет следующие значения:
* `visible` - значение по-стандарту. Выступающее содержимое не обрезается и показывается за пределами элемента.
* `hidden` - лишний контент обрезается.
* `scroll` - лишний контент не виден, но его можно просмотреть, прокрутив скроллбар.
* `auto` - если есть лишний контент, то добавляется скроллбар, а лишний контент обрезается.

## Overflow-x и overflow-y
Свойства аналогичны `overflow`, но задают параметры по вертикали (`overflow-y`) и горизонтали (`overflow-x`).