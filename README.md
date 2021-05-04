<img src="https://botfaqtor.ru/docs/landing/img/logo.svg" alt="drawing" width="160" align="left"> <img src="https://botfaqtor.ru/docs/landing/img/gtm.png" alt="drawing" width="50" align="right"><br></br>
<br>

Шаблон для google tag manager создан для удобного размещения кода Botfaqtor на сайт.

-------------------------
:link: Страница сервиса: https://botfaqtor.ru

:speech_balloon: Документация: https://botfaqtor.ru/docs/gtm-template

-------------------------
**Входные данные:**
- _siteId_<br>Идентификатор сайта, который можно получить в личном кабинете Botfaqtor. Представляет собой положительное целое число. Обязательное поле.

**Методы:**
- _injectScript(url, onSuccess, onFailure[, cacheToken])_<br>Добавляет на страницу тег скрипта для асинхронной загрузки предоставленного URL. Обратные вызовы имеют вид экземпляров функции, упакованных в осуществляющие вызовы функции JavaScript.

- _encodeUriComponent(str)_<br>Возвращает закодированный унифицированный идентификатор ресурса (URI) с экранированными специальными символами. Возвращаемая строка представляет собой результат кодирования полученной строки в формат URI.

**Разрешения:**
- _Добавление скриптов на страницу_<br>Позволяет загрузить только скрипт сервиса Botfaqtor на сайт.

**Необходимые триггеры:**
- _All Pages_<br>Для работы скрипта мониторинга на всех страницах целевого сайта.

-------------------------

**Скриншоты:**

<img src="https://botfaqtor.ru/docs/gtm-template/screen-gtm.png" alt="drawing" width="900"/>
