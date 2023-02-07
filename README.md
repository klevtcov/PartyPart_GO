# PartyPart

## Rewrite бота на GO


### Описание продукта
Телеграмм-бот, предназначенный для легкого учета финансов в компании людей.
Предположим, вы с друзьями решили собраться вместе:
* Андрей купил вино за 1050 рублей и мандарины за 240
* Пётр купил сыр за 500 и виноград за 370
* Анна заказала суши за 1450
* Вероника выбрала пиццу за 560
* Сергей опаздывал на мероприятие и не успел купить ничего

Вы вносите эти затраты в бота и он выдаёт вам кто должен довнести в общую кассу, а кто забрать из неё.

### Использованные технологии
* 
* sqlite3
* Telegramm

### Использованные библиотеки
* telebot - api для работы с Телеграмм
* sqlite3 - лёгкая бессерверная база данных
* datetime - работа с временем и датами
* typing - позволяет делать аннотацию типов
* re - обработка регулярных выражений

### Реализованные функции
* Вывод справки и информации о боте
* Добавление трат участников
* Отображение всех строк с затратами
* Удаление конкретных затрат
* Вывод общего итога с рассчетом баланса

### Панель администратора
* Вывод списка пользователей
* Просмотр и удаление любых трат
* Полный перезапуск базы

### TODO
* Переписать логику программы: Один юзер - одна комната, на Много Юзеров - много комнат 
* Добавить комментарии к вводимым суммам
* Добавить запрос на подтверждение при удалении записей
* Добавить время последней активности пользователя