<img src="https://botfaqtor.ru/docs/landing/img/logo.svg" alt="drawing" width="150"/>

<img src="https://botfaqtor.ru/docs/landing/img/gtm.png" alt="drawing" width="13"/>  Шаблон для google tag manager создан для удобного размещения кода Botfaqtor на сайт.

-------------------------
:link: Страница сервиса: https://botfaqtor.ru

:speech_balloon: Документация: https://botfaqtor.ru/docs/gtm-template

-------------------------
**Входные данные:**
- _siteId_<br>Идентификатор сайта, который можно получить в личном кабинете Botfaqtor. Представляет собой положительное целое число. Обязательное поле.

**Методы:**
- _injectScript(url, onSuccess, onFailure[, cacheToken])_<br>Добавляет на страницу тег скрипта для асинхронной загрузки предоставленного URL. Обратные вызовы имеют вид экземпляров функции, упакованных в осуществляющие вызовы функции JavaScript.

**Разрешения:**
- _Добавление скриптов на страницу_<br>Позволяет загрузить только скрипт сервиса Botfaqtor на сайт.

**Необходимые триггеры:**
- _All Pages_<br>Для работы скрипта мониторинга на всех страницах целевого сайта.
