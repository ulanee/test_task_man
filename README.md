# Тестовое задание на позицию фронтэнд разработчика
### Общие данные

- Приложение должно быть разработано с использованием React.

- Важно придерживаться дизайна макета.

- Сделать необходимо адаптивно, упор на мобильную версию приложения.

- Плюсом будет использование TypeScript.

- Дополнительно напишите, как вы тестировали результат своей работы. Какие используете инструменты и как осуществляете тестирование.

- Не использовать бибиблиотеки для реализации календаря

### Описание задачи

Необходимо реализовать страницу web-приложения.
Функционал следующий:
1. вверху страницы находится поле с датой. При открытии страницы там отображается сегодняшняя дата, при нажатии на стрелки слева или справа дата меняется на предыдущий или следующий день соответственно. Если дата сегодняшняя, то стрелка справа неактивна, чтобы избежать перемещения в будущее;
2. ниже даты находится поле с данными за выбранный день. В тестовом задании сам текст в этом поле не имеет значения, важен цвет. При открытии конкретного дня в первый раз отображаются все три надписи как на макете, но пользователь должен будет выбрать одну из них и, с этого момента, в этом дне отображается только выбранная пользователем надпись. Кроме того, необходимо реализовать возможность изменить ранее сделанный выбор.
3. при нажатии на дату из первого пункта, открывается всплывающее окно, в котором отображается календарь. При выборе даты в календаре, в поле 1 устанавливается выбранная дата, а текст меняется на тот, что ранее выбран пользователем или дефолтное значение (все три надписи). Кроме того, во всплывающем календаре каждый день подчеркнут чертой определенного цвета. Этот цвет должен совпадать с выбранным пользователем в этот день или в дефолтном случае быть серым.

Не используйте в своей реализации какие-либо базы данных. Всё, что нужно сохранить, складывайте в json-файлы.

### Макеты
 .
<img height="300px" src="/src/imgs/page.png" alt="Основная страница">
<img height="300px" src="/src/imgs/floating.png" alt="Всплывающее окно">


### Для начала 

Чтобы начать выполнение тестового задания:
1. Создайте проект
2. Выполните все указанные задачи
3. Загрузите проект на GitHub
4. Отправьте нам ссылку на ваш проект.
