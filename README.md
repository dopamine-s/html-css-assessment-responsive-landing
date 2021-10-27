# Тестовое задание на верстку сайта

Ссылка на макет:
https://www.figma.com/file/LQUQLYVPK192rw3wQq4QzA/html-css-assessment-responsive-landing

---

## Допустимые технологии:

- HTML5;
- CSS-препроцессор (LESS или SASS);
- Сборка осуществляется при помощи актуальной версии Gulp;
- JavaScript (ES2015+);
- Для верстки не используются сторонние библиотеки и компоненты. Однако, допускаются использование JavaScript-библиотеки для реализации слайдеров (например, Swiper).

---

## Требования к верстке:

1. Выполнена верстка всех разрешений макета: мобильный, планшет, десктоп, десктоп для широкоформатных мониторов; 
2. Выполнена верстка всех дополнительных элементов интерфейса: поп-апов, слайдов в слайдере и т.д.; 
3. Использованы семантические HTML-теги;
4. Для картинок в разметке указаны размеры и прописаны осмысленные `alt`-атрибуты;
5. Реализованы состояния интерактивных элементов (`hover`, `focus`, `active`, `disabled` и т.л.). Если они не обозначены в макете, реализация остается на усмотрение верстальщика; 
6. Верстка должна одинаково отображаться во всех современных браузерах:
   - Google Chrome;
   - Mozilla Firefox;
   - Safari;
   - Microsoft Edge. 
7. Реализован Pixel Perfect. Допускаются незначительные отличия от макета:
   - 5 пикселей по вертикали;
   - 10 пикселей по горизонтали.
8. В верстке использована адаптивная и ретиновая графика. Вся графика должна быть оптимизирована. Форматы графики должны быть выбраны правильно, с учетом требований макета;
9. Для декоративных интерактивных SVG-элементов использованы SVG-спрайты;
10. Декоративные шрифты подключены локально через директиву `@font-face`; 
11. Вёрстка проходит тест на переполнение контентом;
12. В верстке использована методология БЭМ, отсутствует глобальная стилизация тегов, `#id`, отсутствуют `!important`; 
13. **Бонус-задание:** Реализована “резина”;
14. **Бонус-задание:** Реализована логика открытия и закрытия поп-апов, работы слайдеров при помощи JavaScript.

---

## Оформление:

- Код должен быть хорошо отформатирован, легко читаем;
- Отсутствуют закомментированные участки кода, мусор, ненужные файлы;
- Все JavaScript-скрипты написаны с использованием современного синтаксиса (ECMAScript 2015+).

---

## Запуск проекта:

- Все зависимости проекта должны быть указаны в файле `package.json`. Команда `npm i` должна установить всё необходимое для того, чтобы сборка проекта работала;
- Сборка проекта выполняется командой `build`;
- Запуск проекта выполняется командой `start`.

---

## Отправка задания:

1. Задание принимается в виде пул-реквеста в GitHub из вашего личного репозитория в этот репозиторий Webtime.Studio;
2. Заполнение шаблона пул-реквеста является **обязательным** – он автоматически 
активируется, когда вы создадите `pull request` из вашего репозитория в этот; 
3. В репозитории не должно присутствовать папки с готовой сборкой проекта (должна быть занесена в `.gitignore`);
4. Все файлы и папки должны быть осмысленно именованы на английском языке, в названиях отсутствуют пробелы;
5. При сборке или запуске проекта не должно возникать ошибок.

