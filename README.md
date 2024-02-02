# Проект "Сложно сосредоточиться"
***
## Структура сайта
Семантически сайт поделен на несколько блоков и секций:
__Блок Header__ - шапка сайта. Здесь находятся кнопки выбора переключения тем сайта: "день", "авто", "неон". Функционал переключения реализован с помощью js;
__Блок main__ - Основное содержимое страницы;
__Блок footer__ - подвал сайта

***
## Функционал проекта
### 1. Организация файлов в проекте
Проект создан по методологии БЭМ, аайловая структура в реализована по схеме Nested:
* Каталог styles - содержит блоки проекта, модификаторы и элементы;
* Каталог scripts - содержит JS скрипты, используемые в проекте;
* Каталог pages - содержит файл Index.css, в котором указанны ссылки на все CSS стили проекта;
* Каталог fonts - содержит подключаемые шрифты.
* Каталог images - содержит картинки, используемые на сайте.

### 2. Используемые технологии
Все элементы страницы хранятся в родительском блоке `body`.
В проекте используется файл `variables.css`, в указываются переменные проекта, а именно - большинство цветов, шрифт, размеры текста для разных элементов и отступы.

В файлах `dark.css` и `light.css`указаны переменные для темной и светлой темы сайта соответственно.

В файле `globals.css` находятся глобальные стили для всего проекта.

В проекте используется  шрифт `IBM Plex mono` -  моноширинная гарнитура, созданная на основе IBM Plex Sans.

Благодаря адаптивной верстке сайт подстраивается под различные разрешения экрана. Основные брейкпоинты: 375px, 768px, 1024px.

Принцип работы скрипта:

1. Кнопка «День». При нажатии на кнопку для <html> добавляется класс theme-light. При этом должна отобразиться светлая тема.
2. Кнопка «Неон». При нажатии на кнопку для <html> добавляется класс theme-dark. При этом должна отобразиться тёмная тема.
3. Кнопка «Авто». При нажатии на кнопку для <html> добавляется класс theme-auto. При этом должна отобразиться та тема, которая выбрана у пользователя в системе. Сработает медиафича prefers-color-scheme.
Для нажатой кнопки устанавливается класс .header__theme-menu-button_active. Кнопка должна стать недоступна для клика.


### 4. Ссылки
Сайт - [Сложно сосредоточиться](https://sergey-pyschkin.github.io/slozhno-sosredotochitsya/)
Репозиторий - [Сложно сосредоточиться](https://github.com/sergey-pyschkin/slozhno-sosredotochitsya.git)

# slozhno-sosredotochitsya
