Сценарий 1: Участие в традиционной лотерее с новыми механиками 
Пользователь просматривает доступные лотереи, основанные на традиционных 
правилах, но с добавлением новых игровых механик. Он выбирает игру, изучает 
правила, смотрит когда будет ближайший розыгрыш тиража и какой текущий 
суперприз. После приобретает билет (механизм оплаты реализовывать не 
обязательно). Розыгрыш проходит, после чего пользователь заходит на платформу, 
проверяет свои билеты и видит результаты, узнавая величину своего выигрыша.
 
Сценарий 2: Взаимодействие с бонусной валютой 
Пользователь зарабатывает бонусную валюту, выполняя действия на платформе: 
покупая билеты традиционной лотереи, обменивая проигрышные или иные способы, 
которые вы реализуете. После этого он тратит её на внутриигровые преимущества, 
такие как дополнительные лотерейные билеты, доступ к эксклюзивным бонусным 
розыгрышам или иными способами, улучшая свой опыт на платформе.

Сценарий 3: Участие в инновационной игре 
Пользователь запускает инновационную игру, где сочетаются тактика, стратегия и 
элемент случайности. В процессе он зарабатывает и тратит бонусную валюту.

Сценарий 4: Управление VIP-статусом 
Пользователь заходит в раздел VIP-статуса и видит свой текущий уровень, а также 
преимущества следующего, такие как доступ к эксклюзивным играм, ускоренная 
обработка запросов в поддержку и иные преимущества, которые вы придумаете. 
Решив улучшить статус, он покупает его за некоторое количество единиц бонусной 
валюты. После этого он сразу замечает изменения. 

Сценарий 5:  Административные функции 
Администратор входит в систему и открывает config файл, где может изменять 
параметры существующих игр, созданных на платформе. Например, он увеличивает 
стоимость билета в традиционной лотерее с 100 до 130 рублей или ускоряет 
накопление бонусной валюты в инновационной игре, либо иные параметры, которые 
будут предусмотрены вашей разработкой, позволяющие управлять механикой игры.

Сценарий 1: Участие в традиционной лотерее с новыми механиками 
- [x] лотереи только для вип
- [x] традиционные правила
- [ ] игровые механики
	- [ ] выбор игры
	- [ ] ознакомление с правилами
	- [ ] ближайший розыгрыш тиража
- [x] отображение суперприза
- [ ] приобретает билет
- [ ] видит результаты, узнавая величину своего выигрыша

Сценарий 2: Взаимодействие с бонусной валютой 
- [ ] зарабатывает бонусную валюту, выполняя действия на платформе
- [x] покупая билеты традиционной лотереи
- [ ] обменивая проигрышные
- [ ] тратит её на внутриигровые преимущества, такие как
- [ ] дополнительные лотерейные билеты
- [x] доступ к эксклюзивным бонусным розыгрышам
- [ ] улучшая свой опыт на платформе

Сценарий 3: Участие в инновационной игре 
- [ ] инновационную игру, где сочетаются тактика, стратегия и элемент случайности
- [ ] он тратит бонусную валюту

Сценарий 4: Управление VIP-статусом 
- [x] в раздел VIP-статуса и видит свой текущий уровень, 
- [ ] преимущества следующего
	- [x] доступ к эксклюзивным играм
	- [ ] ускоренная обработка запросов в поддержку 
- [ ] он покупает статус за некоторое количество единиц бонусной валюты

Сценарий 5:  Административные функции 
- [ ] открывает config файл, где может изменять параметры существующих игр
- [ ] увеличивает стоимость билета в традиционной лотерее с 100 до 130 рублей
- [ ] ускоряет накопление бонусной валюты в инновационной игре
- [ ] позволяющие управлять механикой игры

- Киллер-фитчи:
- [ ] Система фокуса - Сакура (цветущая/завядает/засохшая) референс Forest: Будь состредоточеным - в зависимости от активности
- [ ] Всплывающие ачивки - react-hot-toast
- [ ] Ачивки в профиле
- [ ] Бегущая строка для доверия
- Ю касса
- Розыгрыш товаров, кроме денег
- Учесть категории участников (студенты, пенсионеры, родители с детьми)
- Побольше геймификации
- [ ] Колесо фортуны
- Ежедневные билеты
- Пробные билеты - бесплатные просто за ачивки
- **Чат с поддержкой**
- Квест цепочки и миссии на неделю
- Реферальная программа
- кэшбек
- отправка уведомлений на почту

Моки:

Неавторизованный
- [ ] лендинг:
	- [ ] навбар: юр документы
	- [x] сакура ветки
	- [x] базовая инфа о платформе
	- [x] бегущая строка
	- [x] FAQ
	- [x] футер: ссылки, 
- [x] каталог
	- [x] навбар
	- [x] фильтры, поиск
	- [x] плитки:
		- [x] обложка
		- [x] инфо
		- [ ] призовой фонд (деньги, физические),
		- [x] правила, 
		- [x] кнопка участвовать (редирект на вход)
- [ ] документы
	- [ ] закон о лотераях
	- [ ] правила сервиса текстом
Пользователь
- [ ] каталог
	- [ ] ==приобрести лепесток (билет) - выбор валюты==
- [ ] профиль
	- [x] личные данные (статус вип/обычный)
	- [ ] ачивки
	- [ ] статистика
	- [x] баланс руб/бонусов
	- [ ] ==история платежей - МОК==
	- [ ] ==вывести средства==
	- [ ] пригласить друга
- [ ] Главная (миссии)
	- [ ] НАША САКУРА
	- [ ] Призы
	- [ ] колесо фортуны
	- [ ] цепочка квестов
	- [ ] рекомендованные лотереи
	- [ ] прогресс ачивок
	- [ ] кликер
- [ ] **Чат с поддержкой** to do
Админ
- [ ] каталог плитки
	- [ ] редактировать существующую лотерею
	- [ ] редактировать правила игры
	- [ ] создание лотереи
		- [x] название, описание
		- [x] тип игра/лотерея
		- [x] обложка
		- [x] призовой фонд (физ/бонусные)
		- [x] количество победителей
		- [x] количество участников
		- [x] квота на вип
		- [x] валюта (сумма, игровая/реальная)
		- [x] временные ограничения
		- [ ] финансы (чистая прибыль и другие параметры)
- [ ] статистика
	- [ ] диаграммы
	- [ ] финансовый отчет
	- [ ] скачать PDF, Excel
## ИГРЫ
- [ ] Сапёр кубики
- [ ] 1 на 1 100+100 против 200
- [ ] Орёл решка
- [ ] Маскот


1. ~~Навбар~~
2. Каталог
3. База
4. Лендинг
5. Админка
6. Создание лотереи у админа
7. Профиль
8. Чат с поддержкой
9. Главная (МИССИИ)
10. Документы
11. Статистика

50-70% от общего числа средств, должен выполняться автоматический расчет и динамическая адаптация (на основе проданных билетов)

- [ ] сакура
- [ ] цепочка квестов
- [x] однорукий бандит
- [x] стирание защитного слоя
- [ ] высчитывать чистую прибыль
- [ ] реферальная система

тиеит прайс должен быть в двух копиях виртуальная
пополнение счета