## PROJECT2: PRODUCT LANDING PAGE
JS6 + Babel, Scss, Gulp, Pug, Scrollmagic, GSAP, Jquery, Lodash

Это посадочная страница для продажи фильтров обратного осмоса. Разработан калькулятор чтобы клиент мог сравнить сколько он тратит денег на покупку воды с ценой фильтра.

Для анимации презентации продукта и цветовых переходов используется библиотека ScrollMagic с GSAP.

После заполнени формы, данные о конверсии отправляются в Google Analytics и Яндекс метрику, а пользователя перенаправляет на страницу благодарности с инструкцией. Тем временем он получает транзакционное письмо с реквизитами посредством Sendgrid API.

Email персонализируется и выщитывается время в течении которого активны спец предложения для повышения конверсии.
Для публикации я использовал VPS сервер с NGINX и PM2.  Fornt и back находятся на одном сервере, но на разных портах, с разрешением CORS запросов.


