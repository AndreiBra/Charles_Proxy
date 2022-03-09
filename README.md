# Charles-Proxy

## Функции сниффера Charles Proxy

Перехват, анализ, подмена трафика и другие инструменты которые  использовались в Charles Proxy можно посмотреть ниже, а здесь практическая часть по изучению Charles

### Rewrite
— это инструмент, позволяющий создавать правила, которые изменяют запросы и ответы, когда те проходят через Charles Proxy. Например, можно добавлять и изменять заголовок, искать и заменять текст в теле ответа или запроса, и т.д.
### Map Local
— инструмент, который позволяет использовать локальные файлы, словно они являются частью сервера.
### Throttle Settings
— функция, позволяющая задавать разные параметры скорости соединения с выбранным доменом.
### Map Remote
— позволяет переадресовать запросы с одного URL «Map From» на другой «Map To». Подменяет хост, путь целиком или только параметры в зависимости от вашей задачи. В примере ниже подменён запрос с prod-сервера на dev-сервер.
### Block List
— позволяет блокировать определённые доменные имена. Когда веб-браузер попытается запросить любую страницу из заблокированного доменного имени, она заблокируется. Можно выбрать либо «Drop connection», либо возврат 403 ошибки.
### Breakpoint
— это некая точка остановки запроса. Когда обнаруживается запрос из заданного списка, для дальнейшего ручного взаимодействия с параметрами запроса открывается отдельное окно. В нём перейдите к ручному изменению запросов и ответов. Удобно использовать эту функцию, когда тестируете API или разные ответы сервера.
