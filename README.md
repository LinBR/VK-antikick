# vk-antikick
Простенький антикик, который не позволяет вас кикнуть из конфы или ваших друзей, при условии, что инвайты открыты.

## Подробное описание
С помощбю данного антикика при кике вашего друга, его будет добавлять или друг вас. Главное, чтобы этот человек был у вас в друзьях и у него былы открыты приглашения, как и инвайты в беседе.

## Как пользоваться?
Перед тем, как пользоваться скриптом, нам нужно создать конфиг с токенами и айди людей, что мы будем добавлять(с айди необязательно)  
Для этого после запуска скрипта выбираем Создание конфига и вводим количество аккаунтов, что будут добавлять и далее либо токены этих аккаунтов, либо пароли и логины(ввод пароля и логина работает нестабильно и также он не работает с теме аккаунтами, где стоит двухфакторная аутентификация)  
P.s: токен можно получить тут: https://vkhost.github.io/ (там нам нужно выбрать кейт мобайл)  
После того, как закончим с токенами, вводим айди людей, которых мы будем добавлять при кике или вводим 0, если только тех, чей токен мы ввели(также хочу подметить, что айди тех, чей токен мы вводили, вводить не надо)  
Также вы можете отредактировать свой конфиг, добавя туда ещё айди или токен, для этого выбирайте Редактирование конфига.
А что если я хочу пересоздать свой конфиг?  
Для вас есть специальный выбор в редактировании конфига Удаление и создание нового конфига  
После того, как мы создали конфиг, мы можем запускать антикик. На этом настройка заканчивается. И ещё, если вы создали конфиг один раз, больше его создавать не надо.

## Как скачать?
### TERMUX
1. Для скрипта нужен питон, скачиваем  
pkg install python 
2. Чтобы скачать скрипт, нужен гит, его тоже скачиваем  
pkg install git
3. Теперь скачиваем сам скрипт  
git clone https://github.com/LinBR/vk-antikick
4. Переходим в папку со скриптом  
cd vk-antikick
5. Скачиваем модули, что использует скрипт  
 pip install -r requirements.txt
6. Запуск скрипта  
python antikick.py
### Linux
1. Скачиваем скрипт  
git clone https://github.com/LinBR/vk-antikick
2. Переходим в папку со скриптом  
cd vk-antikick
3. Скачиваем все зависимости, которые использует бот  
 pip install -r requirements.txt
4. Запуск скрипта
python antikick.py
## Автор
Telegram: https:/t.me/Lin089  
Discord: sueta.....#8453  
Vk: sosatb
