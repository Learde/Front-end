# Элементы формы
## Элемент `<input>`
Элемент `<input>` самый важный элемент формы. Он может быть отображен различными способами, исходя из того, какое значение атрибута `type` установлено.

## Элемент `<select>`
Элемент `<select>` определяет выпадающий список.

Элемент `<option>` определяет возможные варианты для выбора.

По стандарту, первый элемент списка выбранный. Для установления выбранного элемента, необходимо использовать атрибут `selected`

Пример:
```html
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab" selected>Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select> 
```

### Видимые значения
Используйте атрибут `size`, если необходимо установить число элементов, которые будут видны.

### Мультиселект
Для того, чтобы включить мультиселект, необходимо использовать атрибут `multiple`.

## Элемент `textarea`
Элемент `textarea` определяет многострочное поле для ввода текста. Его размеры можно устанавливать или используя атрибуты `rows` и `cols`, или CSS свойства `width`, `height`.

## Элемент `<button>`
Элемент `<button>` определяет кликабельную кнопку.

### **Следующие элементы являются новыми и поддерживаются не во всех браузерах.**

## Элемент `<datalist>`
Элемент `<datalist>` указывает список предварительно определенных параметров для элемента `<input>`. Пользователи будут видеть раскрывающийся список предварительно определенных параметров по мере ввода данных.
Атрибут `list` элемента `<input>` должен совпадать с атрибутом `id` элемента `<datalist>`.

## Элемент `<output>`
Элемент `<output>` представляет результат вычисления (например, выполненный скриптом).

## Упражнения(3)
1. [Упр.1](https://codepen.io/Learde/pen/ZoRGeO)
2. [Упр.2](https://codepen.io/Learde/pen/erKNWd)
3. [Упр.3](https://codepen.io/Learde/pen/NMzqjQ)