# Telegram_coin_bot
![Бот для добывания криптовалюты, выполняя задания ботов dogeclick
](cfce13b13a2a.png)

Бот для добывания криптовалюты, выполняя задания ботов [dogeclick](https://dogeclick.com/)

Для работы трабуется установить [Selenoid](https://github.com/aerokube/selenoid) и зависимости проекта

## План действий

0. Создать аккаунт телеграм и начать диалог с ботом из конгломерата [dogeclick](https://dogeclick.com/)
1. Вносим в скрит SozdanieBD.py данные Telegram аккаунта и запускаем его. Тем самым мы создаем базу аккаунтов и добавляем в нее запись с ботом. Повторяем этот пункт столько раз, сколько аккаунтов у нас есть.
2. Запускаем скрипт Sozdanie_Clienta.py тем самым генерируем фаил-клиент для всех наших Telegram ботов
3. Для старта главной программы запускаем скрипт go.py они будут работать до тех пор пока мы их не остановим. Если в процессе возникнет ошибка цикл перезапустится и все равно продолжит работу начиная с первого бота
4. Если мы хотим узнать сколько заработал каждый бот. Останавливаем пункт 3 и запускаем скрипт Balans.py и ждем завершения, скрипт выведет сколько заработал каждый бот и итоговую ссумму

## Что еще важно помнить.
### Лимиты Telegram (актуально на июнь 2020)

* Количество участников в группе = 200 человек

* Количество участников в супер-группе = 200 000 человек

* Максимальный размер передаваемого файла = 1.5 ГБ

* Количество закрепленных чатов\каналов\ботов = 5 штук

* Лимит отправки сообщений\спама с 1 аккаунта = 49 сообщений

* Количество публичных каналов (с ссылкой @) которые можно создать на 1 канале = 10 штук

* Количество ботов, которое можно создать через botfather на 1 аккаунт = 20 штук

* Длинна публичной ссылки (Начинается с @) канала\аккаунта = от 5 до 32 символов

* Название канала\супергруппы = от 1 до 255 символов

* Описание канала\супергруппы = от 1 до 255 символов

* Количество людей которых можно пригласить в канал = 200 человек! (Внимание! это лимит на канал а не на аккаунт, если у вас на канале уже 180 подписчиков, пригласить вы сможете лишь 20 человек!)

* Количество людей, которых можно пригласить в супергруппу = 200 000 человек (50 человек с 1 аккаунта!)

* Суммарное количество чатов / групп / супергрупп / каналов в ленте аккаунта = 500 штук

* Количество участников, которое может увидеть администратор / создатель канала / супергруппы = 200 человек

* Количество символов в 1 сообщение = 500 символов

* Размер поста в Telegra.ph = до 32798 знаков

* Количество аккаунтов в официальном мобильном приложении (мультиаккаунт) = 3 аккаунта

* Спам (запрет писать сообщения) = от 48 часов до вечного

* Срок блокировки номера телефона = 6 месяцев (Если ваш аккаунт заблокировали, зарегистрировать новый аккаунт на этот же номер телефона можно будет не раньше чем через пол года)

##Поддержать автора:
[Donation Alerts](https://www.donationalerts.com/r/black_triangle)
Bitcoin: 1AWBMoeV8UEybQi4QrQMmeFX1sXvRLDeCn
Ethereum: 0xB151c82A264eF0EA848c120444173658BFA18Cf9
DASH: XcNtFGW1ydGLudvTPWoBvPZZxG844EvksR
Zcash: t1hCJwasRozdkoaK9HLpngoEVPQhEZpxdFT
Monero: 41iNuQsc6GjZofH3XkKwNYVSXVsrjipfVjjNR3nbsL5XjJMFTfykW1T6CkYz1StdXH2t8dhnjUTT9FwEPpbsFVxjHuuYabQ
