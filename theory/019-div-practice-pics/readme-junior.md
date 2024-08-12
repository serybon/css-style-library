# Техническое задание для создания сайта "Котомемоизация"

## Junior перейти на [senior](./readme-senior.md)

**Легенда:**
В волшебной стране существует загадочное место — КотоСайт, дом мемных котов. Недавно его волшебство начало угасать, и обитатели КотоСайта обратилась к новому специалисту за помощью. Ему поручено восстановить магию сайта, используя частично готовый код, оставленный его коллегами.

**Техническое задание:**
 
1. **Общее оформление:**
   - Установить фон body цвета #000.
   - Задать отступы margin для body: 0px.

2. **Контейнер с мемом (.meme-container):**
   - Установить отступы margin в 30px.
   - Добавить внутренние отступы padding в 20px.
   - Задать цвет фона background-color: #555.
   - Задать цвет текста color: #fff.
   - Центрировать текст text-align: center.
   - Задать шрифт текста font-family: monospace.
   - Задать размер шрифта font-size: 20px.
   - Добавить белую границу толщиной 10px border: 10px solid white.

3. **Изображение мемного кота (img):**
   - Добавить белую границу толщиной 3px border: 3px solid white.

4. **Адаптация:**
   - Стили должны обеспечивать адаптивное отображение на различных устройствах.

**Примечание:**
Внесите необходимые изменения в код, чтобы восстановить волшебство КотоСайта и порадовать его обитателей.

```html
<!DOCTYPE html>
<html lang="ru">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Котомемоизация</title>
</head>

<body>

  <div class="meme-container">
    <img class="meme-image" src="https://loremflickr.com/320/240?lock=7" alt="Мемный кот">

  </div>

</body>

</html>
```