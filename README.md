<h1 align="center">Spermack</h1>

<p align="center">Скрипт по подключению Клода Слаки к Таверне</p>

---
<br>
<br>
<br>

Допиленный код у бургеров: https://github.com/AmmoniaM/Spermack

# Настройка Слаки

Нужно зарегаться на Слаке.
Затем нужно добавить Клода https://slack.com/apps/A04KGS7N9A8-claude
Также аноны говорят что нужно принять лиц. соглашение Клода

# Настройка скрипта

Скачиваем репу, заходим в проект

Открываем в проекте файл config.js в редакторе. Там есть 4 значения, я объясню их по порядку:



## TOKEN:
В воркспейсе жмем F12, и пишем сообщение в чат (любой), во вкладке сеть ищем запрос chat.postMessage, заходим в него. Жмем запрос (FF)/ полезные данные (Chromium), ищем там токен начинающийся с xoxc- . Копируем его полностью и вставляем в TOKEN
![image](https://user-images.githubusercontent.com/129290831/234063889-99ecb1d5-d3f8-43a3-8fca-1e7a3e481134.png)


## COOKIE:
Копируем куки **ЗАКОДИРОВАННЫМИ** в url: заходим в workspace и нажав F12 переходим в хранилище (FF)/ приложение (Chromium), ищем куки под названием d, со значением начинающимся на xoxd- . Копируем его значение полностью и вставляем в COOKIE
![image](https://user-images.githubusercontent.com/129290831/234064337-4e5d9c7c-2da9-49ad-85e5-e22847ce471c.png)

## TEAM_ID:
Заходим на главную своего воркспейса, и в левом верхнем углу жмем на стрелочку вашего кумерского ООО, там будет ссылка, типа coomer.slack.com . Копируем то что до первой точки (coomer) и вставляем в TEAM_ID 

## CLAUDE:
Заходим в личку к Клоду, копируем то что в конце адреса браузера после последнего слэша. Вставляем в CLAUDE

**Алсо способ от анона**
![image](https://user-images.githubusercontent.com/129290831/234062310-b2ea0dd2-20fa-41e3-bfaa-d5cfc8dfbe28.png)



# Как подключить к таверне?



Запускаем батник start.bat, копируем адрес в консоли в реверс прокси, выбираем GPT-4, выключаем стриминг если включен. ???. COOM
