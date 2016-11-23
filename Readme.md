[API] No Pay No Save
===================

Описание основных эндпоинтов.

Адрес:
> http://nopaynosave.ipacmanx.ru/api/

----------

register
--------------------------------
Регистрация пользователя.
> /register?email=&pass=&name=&vk=

email - адрес электронной почты
pass - пароль
name - имя
vk - айди в вк, для фото

----------


login
--------------------------------
Авторизация пользователя.
> /login?email=&pass=

email - адрес электронной почты
pass - пароль

----------

status
--------------------------------
Обновить текущую информацию
> /status

----------

history
--------------------------------
Обновить текущую информацию
> /history?from=to=offset=limit=

from - с какого периода
to - по какой период
offset - пропуск на странице
limit - количество на странице

----------

inMoney
--------------------------------
Добавление доходов.
> /inMoney?title=1&summ=0&descr=text&cat=

title - заголовок
summ - количество денег
descr - описание
cat - паттерн или категория

----------------

outMoney
--------------------------------
Добавление расходов.
> /outMoney?title=1&summ=0&descr=text&cat=

title - заголовок
summ - количество денег
descr - описание
cat - паттерн или категория

----------------

inUsualMoney
--------------------------------
Добавление постоянных доходов.
> /inUsualMoney?title=1&date=&summ=0&descr=text&cat=

title - заголовок
summ - количество денег
descr - описание
date - дата поступления
cat - паттерн или категория

----------------

outUsualMoney
--------------------------------
Добавление постоянных расходов.
> /outUsualMoney?title=1&date=summ=0&descr=text&cat=

title - заголовок
summ - количество денег
descr - описание
date - дата снятия
cat - паттерн или категория
