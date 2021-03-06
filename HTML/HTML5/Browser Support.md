# Поддержка браузеров
Все современные браузеры поддерживают HTML5, но всё ещё остаются старые, которые не имеют такой возможности. Но это можно исправить.

## Определение семантических элементов как элементов блока
В HTML5 добавили 8 новых семантичных блоков. Все они блочные. Для сохранения правильного поведения в старых браузерах, необходимо установить для всех этих элементов CSS-свойство: `display: block`.

## Добавление новых элементов в HTML
Можно добавить новые элементы на страницу HTML. В следующем примере на страницу добавляется новый тег `<myHero>`:
```html
<!DOCTYPE html>
<html>
  <head>
    <script>document.createElement("myHero")</script>
    <style>
    myHero {
        display: block;
        background-color: #dddddd;
        padding: 50px;
        font-size: 30px;
    }
    </style>
  </head>
  <body>

    <h1>A Heading</h1>
    <myHero>My Hero Element</myHero>

  </body>
</html> 
```

## Проблемы с IE8
Решение, описанное выше, пригодно для браузеров IE9+, но более старые не поддерживают его.

Тем не менее, есть способ справиться и с этой проблемой. Для этого можно использовать HTML5Shiv, который восстановит работу HTML5 в старых браузерах.

## Синтаксис HTML5Shiv
Устанавливается в теге `<head>`:
```html
<head>
  <!--[if lt IE 9]>
    <script src="/js/html5shiv.js"></script>
  <![endif]-->
</head> 
```
