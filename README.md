# Go-IT-HTML-CSS-materials

# Прекурс
https://www.loom.com/share/ec6066944e6447999cbb18f426e83baa

# Розбір прекурса
https://www.loom.com/share/b1d5954265f14f2e9f75f663c7ed23a5

# валідатор
 https://validator.w3.org/

# Сквош
 https://squoosh.app/

# Специфікація
https://developer.mozilla.org/ru/docs/Web/HTML

# Emmet комбінації
https://docs.emmet.io/cheat-sheet/

# Сервіс для перевірки на правильну вкладеність тегів
https://caninclude.glitch.me/

# відео з розбором структури header
https://www.loom.com/share/05e7818e710448508fa4bd070fba1f8e
https://github.com/SergeyKorobka/goit-markup-example-01

# Відео, як створити репо на основі попереднього  
https://www.loom.com/share/1164f1d17cb34e778328c7214c3fbc69

# Слова, які часто використовуються в CSS-класах
https://github.com/YK911/basic-dictionary

# Посилання на тренажер по HTML і CSS
https://typatest.pp.ua/pages/Onlajn-trenazher-HTML-i-CSS.html

#  відео, де розбираємо роботу зі стилями текстового контенту header
https://www.loom.com/share/ff8b3685b0fa4ea193505757e923476f
Посилання на репозиторій https://github.com/SergeyKorobka/goit-markup-example-02

# Для правильного приховування заголовків використовуємо паттерн – visually-hidden.
// HTML
<h2 class="visually-hidden">Title<h2>

// CSS
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  border: 0;
  padding: 0;
  white-space: nowrap;
  clip-path: inset(100%);
  clip: rect(0 0 0 0);
  overflow: hidden;
}

# Як виявити розмір контейнера на макеті - https://www.loom.com/share/d0dbb05b78904333a265f9b094ae46ee
Все, що потрібно знати про CSS Margin https://habr.com/ru/post/465839/
Особливості inline-block елементів - https://css-tricks.com/fighting-the-space-between-inline-block-elements/
Повний посібник з Flexbox - https://css-tricks.com/snippets/css/a-guide-to-flexbox/
Гра по Flexbox - http://flexboxfroggy.com/#uk
Ще одна гра на вивчення флексів https://mastery.games/flexboxzombies/
Генератор nth-child https://nthchild.kawalekkodu.pl/en/

# відео-розбір, в якому працюємо з геометрією та позиціонуванням елементів в header:
https://www.loom.com/share/76d6285349c44d47a5284aca6728b0a8
Посилання на репозиторій:
https://github.com/SergeyKorobka/goit-markup-example-03

# Модуль 4
Добірка цікавих градієнтів - [Handpicked beautiful color gradients](https://uigradients.com/#Reef)
Ще один цікавий оптимізатор картинок – [Online Image Сompressor](https://imagecompressor.com/)
Position - https://css-tricks.com/almanac/properties/p/position/
CSS Transition - https://www.youtube.com/watch?v=8kK-cA99SA0&feature=youtu.be
Готовий CSS код різних анімацій тексту - https://animate.style/
Футбольне поле (приклад position: absolute) https://codepen.io/mpadalko/pen/PomeroW?editors=1100
Position: Sticky https://codepen.io/mpadalko/pen/LYNqpGG
Генератор трикутників https://www.cssportal.com/css-triangle-generator/
Приклади з трансформ https://codepen.io/nazarelen/pen/EaNbLX?editors=1100
Генератор cubic-bezier https://cubic-bezier.com/#.22,.84,.88,.03
Посилання на репозиторій:
https://github.com/Olexiy-repin/html-css-112/tree/module-04-lesson-01

Додаткові матеріали:
Бібліотека Animate.css https://animate.style/
Бібліотека AOS (Анімациї на скрол): https://michalsnik.github.io/aos/
Приклад анімації shake іконок: https://codepen.io/mpadalko/pen/GRWEWMZ?editors=1100
Приклад анімації heartbeat: https://codepen.io/mpadalko/pen/JjbErPB?editors=1100

як експортувати іконки, додавати їх до спрайту та підключати. Також як додавати іконки в існуючий спрайт. І в бонус сніппет який буде розгортати структуру svg>use
https://www.loom.com/share/1f948ffc8ea849529be1f2a3bca88142
Посилання на сніппет - https://gist.github.com/SergeyKorobka/0b8df417938de97e2a0bf34dc18b237d (інструкція по підключенню в відео)
Посилання на розширення XML Format - https://marketplace.visualstudio.com/items?itemName=mikeburgh.xml-format

код сніппету
"svg": {
    "scope": "html",
    "prefix": "svg",
    "body": [
    "<svg class=\"$2\" width=\"$3\" height=\"$4\">",
    "  <use href=\"$1\"></use>",
    "</svg>"
    ],
    "description": "media min"
  }

# Модуль 5

Тримайте відео з реалізацією модального вікна - https://www.loom.com/share/61ec4e9119e34240949a90c4dd8bea21
Посилання на репозиторій - https://github.com/SergeyKorobka/goit-markup-example-05
Посилання на скрипт для відкриття модального вікна - https://gist.github.com/SergeyKorobka/031b7e6d986052b13acbce17d52852c9

# Модуль 6

Responsive images - https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
Лайфхак, як прописати шлях в srcset - https://www.loom.com/share/8c48d3f9818a4ad081c2c6ac3ddfd2ff
Зразок ретінізації фонового зображення - https://prnt.sc/Hf7VaTZAsEQa

Почнемо адаптацію нашого проекта під різні розміри екрану:muscle::skin-tone-2:
Відео розбір, в якому працюємо з header та mobile menu - https://www.loom.com/share/bcac119269fe463680e3aad72163d33d
Посилання на репозиторій - https://github.com/SergeyKorobka/goit-markup-example-06

# TEAM PROJECT

Шаблон бандлера Vite - https://github.com/goitacademy/vanilla-app-template
Команди для роботи в терміналі - https://gist.github.com/SergeyKorobka/2f534c8eeefa6c5494a735564b09612e
Відео по роботі з гітом в команді - https://youtu.be/wFY5HVuQBgw?si=ffDLPUZz7vMmMFhN
Приклад валідації інпута - https://codepen.io/SergeyKorobka/pen/WNWeKVp
Приклад фліп картки - https://www.w3schools.com/howto/howto_css_flip_card.asp
Скрипт для мобільної менюшки, яка закривається при натисканні на якірні посилання - https://codepen.io/SergeyKorobka/pen/zYmojKV
Бібліотека анімації при скролі - https://michalsnik.github.io/aos/
