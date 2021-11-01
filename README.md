# Telegram Bot для запоминания хорошей и плохой еды. 


Оглавление: 
- [Постановка задачи](#task)
- [Возможности бота](#features)
- [Развертывание](#deploy)
- [Ссылки и реклама](#adv)



## <a name="task">Постановка задачи</a>

**Проблема**: Купил пельмешки - оказались вкусные, а через месяц уже не можешь вспомнить, какие именно покупал. Так же с кетчупом и майонезом для них.

**Задача**: Создать telegram bot, в который можно отправлять фотки еды, продуктов в магазине и отмечать, хорошие они или плохие. 

**Используемые технологии**: Python, PostgreSQL, Heroku


## <a name="features">Возможности бота</a>

1. Создание оценки: отправляем фото, выбираем оценку, выставляем категорию,добавляем описание - информация сохнаряется в базе данных
2. Просмотр оценки: 
    + По команде \list - выводится 5 последнх оценок
    + При отправке #пельмени выводятся последние оценки по категории
    + При отправке цифры выводятся последние оценки
3. Бот мультиязычный. В настройках можно указать язык бота. Используется Python-библиотека gettext
4. Оценку можно редактировать и удалять
5. (В будущем) можно объединять оценки с другим пользователем



## <a name="deploy">Развертывание</a>
Бот задеплоен на Heroku

## <a name="adv">Ссылки и реклама</a>
Ссылка на бота: [https://t.me/GoodBadFoodBot](https://t.me/GoodBadFoodBot)

Исходный код размещен по ссылке https://github.com/jashilko/BadGoodFoodBot

Если вам нужны [телеграм боты](https://tlgrm.ru/docs/bots) для решения бизнес-задач, пишите run@kostya.run
