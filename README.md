# Webdev

**[Watch here - webdev](https://druzhkova.github.io/Webdev/)**

| Крайний срок сдачи | Имя проекта |
|--------------------|-------------|
| 21.09.2020 23:59 | webdev |


# Домашнее задание: webdev

Сверстать страницу согласно макету:

Figma:

**[webdev. Figma](https://www.figma.com/file/EWG64LHNWmdi51cY0W1kqt/phototime?node-id=9%3A13)**

JPG:

**[webdev. JPG](https://github.com/rolling-scopes-school/tasks/blob/master/tasks/markups/level-1/webdev/webdev.jpg)**

Ключевым моментом является полное соответствие макету. Это достигается совпадением двух изображений при наложении слоя с картинкой поверх готового решения с помощью браузерного расширения **Pixel Perfect**. Уделите внимание следующим важным и распространенным моментам:

- Основные блоки должны быть идеально расположены на заданной ширине экрана (1600px).
- Изображения, логотипы (если они есть) должны быть идеально расположены в рамках логического контейнера.
- Иконки должны сохранять идеальное расстояние до соответствующего им текста.
- Если использован правильный шрифт, проверьте высоту текста — он должен соответствовать исходнику. Ширина может варьироваться. Но общепринятой практикой является добавление свойства межбуквенного интервала (`letter-spacing`) тексту заголовков, девиза (motto) или цитат.
- Если в строке несколько объектов визуально одинаковой ширины, то ширина содержащих их блоков должна быть одинаковой. Разница в несколько пикселей не имеет значения, важно совпадение размеров.
- Если в макете много слоев, лучше всего объединить слои в графическом редакторе и использовать изображение в качестве фонового.

*[Расширение PerfectPixel для Google Chrome](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?hl=en)*

Поддержка браузеров: **Google Chrome, Mozilla Firefox, Microsoft Edge (Windows) or Safari (MacOS)**.

В первую очередь мы разрабатываем для Google Chrome и используем Pixel Perfect для проверки соответствия. Затем проверяем, не «рушат» ли Mozilla Firefox, Microsoft Edge или Safari наши стили.

## Технические требования

❗
 - Нельзя использовать Bootstrap, jQuery, любые фреймворки и библиотеки
 - Можно использовать html, css и Normalize.

Ширина макета 1600px.
1. Либо позиционируем весь макет по центру с равными отступами по краям.
2. Либо растягиваем полосы в ширину на весь размер экрана, кроме изображений заднего фона блоков. 

«Интерактивный» означает, что у элемента появляется визуальный эффект или анимация (на ваше усмотрение: анимация курсора, изменение цвета заднего фона, затемнение, нижнее подчеркивание, изменение шрифта) при каких-либо действиях пользователя, например, при наведении курсора. Использовать JavaScript для обработки пользовательских событий в данном задании не обязательно. Обычно, такой эффект реализуют при помощи псевдокласса `:hover` и следующих свойств:
- `cursor: pointer`,
- `background`,
- `text-decoration: underline`,
- `color`.


#### 1. **Header** (`<header>` содержит только логотип и панель навигации):
- Интерактивная панель навигации. Должен быть подсвечен первый элемент.
- Логотип находится по центру.
- На странице обязательно должен присутствовать один элемент `<h1>`. Расположите его на свое усмотрение. Внутри должен быть текст `webdev`.
- Хедер "липким" делать не нужно. Т.е. при скролле он остается на своей позиции.
- Изображение должно быть подложено под текст.


#### 2. Блок **Your Life**
- Кнопка `get started` должна быть интерактивной.
- Кнопки (иконки) соц. сетей должны быть интерактивными.
- Изображение должно быть подложено под текст.


#### 3. Блок **Rappresent**
- В текстовом блоке есть важный текст, который выделен жирным. Для него нужно использовать логический элемент.
- Кнопка `get started` должна быть интерактивной.
- Картинка должна быть на своем месте.
  
  
#### 4. Блок **Our Community**
- `1`, `/`, `5` должны быть раздельными элементами.
- Стрелки должны быть интерактивными.
- Конструкция представляет из себя 2 многоколоночных макета.
  1. Двухколоночный. Слева иконка пользователя и слова. Справа колонка, которая в свою очередь является многоколоночных макетом с изображениями.
  2. Трехколоночный. Колонки - изображения, одинаковые по длине. Обратите внимание, что часть третьего изображения уходит за границы экрана. Соотвественно, его так же надо обрезать с помощью стилей.
  
  
#### 5. Блок **Implement**
- В текстовом блоке есть важный текст, который выделен жирным. Для него нужно использовать логический элемент.
- Кнопка `learn more` должна быть интерактивной.
- Картинка должна быть на своем месте.
  
  
#### 6. Блок **Subscribe**
- Изображение должно быть подложено под текст.
- Галочка на зеленом фоне должна быть интерактивной.
- Поле `your email` должно иметь валидацию на тип email.


#### 7. Блок **Download**
- `apple store`, `play store` и их иконки должны быть интерактивными.


#### 8. **Footer** (`<footer>` содержит текст, логотип и панель навигации):
- Между элементами меню есть разделители. 
- Интерактивная панель навигации.
