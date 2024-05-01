- Создай репозиторий goit-markup-hw-07.
- Склонируй созданный репозиторий и скопируй в него файлы предыдущей работы.
- Настрой GitHub Pages и добавь ссылку на живую страницу в шапку GitHub-репозитория.

**Структура файлов проекта**

_Критерии приёма работы наставником_

_Проект_

- Выполнен рефакторинг HTML-кода проекта используя методологию BEM.
- Выполнен рефакторинг CSS-кода проекта используя препроцессор SASS.
- В корне проекта создана папка sass, в которой лежат все файлы стилей препроцессора.
- В папке sass есть файл main.scss - главный файл в котрый импортируются все SASS-фрагменты (partials, файлы \_имя.scss).
- Палитра цветов макета и наборы шрифтов вынесены в переменные в файле variables.scss, который лежит в папке sass/utils. Можно использовать CSS или SASS переменные (по желанию).
- Для каждого компонента создан отдельный файл-фрагмент стилей в папке sass/components. Например \_page-header.scss, \_logo.scss и т. д.
- В файлах index.html и portfolio.html подключен минифицированный файл стилей main.min.css из папки css.

_Разметка_

- Правильное именование классов блоков по методологии BEM.
- Правильное именование классов элементов по методологии BEM.
- Правильное именование классов модификаторов по методологии BEM.
- Правильное именование классов примесей по методологии BEM.
- Имена классов по методологии BEM понятные и описательные, на английском языке.

_Оформление_

- Использована вложенность селекторов.
- Максимальная вложенность селекторов - 2 уровня.
- Оператор конкатенации (&) использован для описания псевдоклассов и псевдоэлементов.
