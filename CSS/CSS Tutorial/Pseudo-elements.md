# Pseudo-elements
Псевдо-элементы используются для стилизации определённых частей элемента.

Синтаксис:
```css
selector::pseudo-element {
    property:value;
}
```

## ::first-line
Псевдо-элемент `::first-line` используется для стилизации первой строки текста.

Задаётся только для блочных элементов. Следующие свойства применимы к `::first-line`:
* font 
* color 
* background 
* word-spacing
* letter-spacing
* text-decoration
* vertical-align
* text-transform
* line-height
* clear

## ::first-letter
Псевдо-элемент `::first-letter` используется для стилизации первой буквы текста.

Задаётся только для блочных элементов. Следующие свойства применимы к `::first-letter`:
* font
* color 
* background
* margin
* padding
* border
* text-decoration
* vertical-align (только если float задан как none)
* text-transform
* line-height
* float
* clear

## ::before
Псевдо-элемент `::before` может использовать для добавления контента перед контентом элемента.

```css
h1::before {
    content: url(smiley.gif);
}
```

## ::after
Псевдо-элемент `::after` может использовать для добавления контента после контента элемента.

```css
h1::after {
    content: url(smiley.gif);
}
```

## ::selection
Псевдо-элемент `::selection` позволяет стилизовать ту часть элемента, которая выбранна пользователем.

Следующие свойства применимы к `::selection`:
* color
* background
* cursor
* outline
