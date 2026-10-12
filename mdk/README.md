# МДК: 20 простых сайтов

Откройте `index.html` в браузере. Каждый из 20 каталогов содержит отдельный сайт из одной страницы. Сайты работают без сборки, JavaScript и внешних библиотек. Оформление находится в `style.css`.

Весь текст находится в исходном HTML: страницы подходят для учебного парсинга. Кодировка UTF-8, язык `ru`. Идентификаторы уникальны в пределах страницы, классы обозначают типы данных. Общие селекторы: `#site-title`, `#main-content`, `#site-footer`. В каждом сайте есть свои селекторы для содержимого.

| Сайт | Структура | Примеры CSS-селекторов |
| --- | --- | --- |
| [Новости города](01-news/index.html) | Статьи с датами | `.news-item, .news-title, .news-date` |
| [Магазин канцтоваров](02-shop/index.html) | Карточки товаров | `.product, .product-name, .price` |
| [Расписание занятий](03-schedule/index.html) | Таблица с заголовками | `#schedule .lesson, .subject, .room` |
| [Рецепт блинов](04-recipe/index.html) | Список ингредиентов и шагов | `.ingredient, .step` |
| [Анна — дизайнер](05-profile/index.html) | Профиль со списком характеристик | `#profile-details dt, #profile-details dd` |
| [Частые вопросы](06-faq/index.html) | Раскрывающиеся вопросы | `.question summary, .answer` |
| [Кафе «Уют»](07-cafe/index.html) | Меню по категориям | `.menu-item, .item-name, .price` |
| [Книжная полка](08-library/index.html) | Вложенный список книг | `.book, .book-title, .author` |
| [День творчества](09-event/index.html) | Событие с программой | `#event-date, .venue, .program-item` |
| [Времена года](10-gallery/index.html) | Галерея с подписями | `.season, figcaption` |
| [Контакты мастерской](11-contacts/index.html) | Адрес и контактные ссылки | `.contact-link, .weekday` |
| [Уроки HTML](12-course/index.html) | Основной материал и боковая панель | `.lesson, .sidebar` |
| [Отзывы о кружке](13-reviews/index.html) | Цитаты с авторами | `.review-text, .review-author` |
| [Прогулка по городу](14-travel/index.html) | Маршрут с внутренней навигацией | `.stop, .route-link` |
| [Наша команда](15-team/index.html) | Список участников с ролями | `.member-name, .member-role` |
| [Словарь веб-терминов](16-dictionary/index.html) | Список определений | `.term, .definition` |
| [Тарифы учебного клуба](17-plans/index.html) | Сравнение тарифов | `.plan-name, .price, .features li` |
| [История музея](18-museum/index.html) | Хронология событий | `.milestone, .year` |
| [Анкета читателя](19-survey/index.html) | Форма с подписями и группами полей | `#reader-name, #genre, .radio-input` |
| [План на день](20-tasks/index.html) | Список задач с флажками | `.task, .task-checkbox` |

Форма анкеты — учебная: при отправке открывается та же страница с параметрами в URL. Сервера для сбора ответов нет. Флажки плана на день не сохраняются после перезагрузки.
