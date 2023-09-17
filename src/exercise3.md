## Задание №3. Веб-хранилища №2



| **Хранилище**    | **Краткое описание**                                               | **Ключ**                               | **Значение**                                                         |
|------------------|------------------------------------------------------------|----------------------------------------|----------------------------------------------------------------------|
| **Local Storage**    | Счетчик Яндекс Метрики.                                | "_ym960630_il"                         | "Леонид Зюганов планирует стать официальным кандидатом в мэры Москвы от КПРФ15:11"      |
|                  | Содержит информацию о предыдущем просмотре видео.          | "video_prev_view"                      | "{"video_id":"-106879986_456258734","time":1687816138814}" |
|                  | Хранит ID текущего воспроизводимого Coub.                  | "embed_current_playing_coub"           | "coub_embed_5920089" |
|                  | Содержит данные бесплатного переводчика Linguee.           | "LMT_freeTranslator"                   | "{"confirmed":false,"confirmed__%expires":1689089812}" |
|                  | Хранит уникальный идентификатор пользователя на платформе Kion. | "kion.platform.uuid"              | "70c8e019-048d-4287-9431-bbb5e58fa4e3"                     |
| **Session Storage**  | Хранит данные пользовательской сессии.                 | "userSession"                          | "{"sessionLost":"{\"_value\":false,\"_persistAt\":1687840457285}","sessionRenewalTries":"{\"_value\":0,\"_persistAt\":1687840457310}","sessionLostWithTooManyRetries":"{\"_value\":false,\"_persistAt\":1687840457323}","_persist":"{\"version\":1,\"rehydrated\":true}"}" |
|                  | Сохраняет информацию о Third-party видео.                  | "__tt_embed__mounting"                 | "false" |
|                  | Содержит статистику сервера для сетевых запросов.          | "XHR_STATS_TRANSPORT_META_web"         | "1687840765003" |
|                  | Хранит историю посещенных страниц веб-сайта.               | "History.store"                        | "{"idToState":{"1687840363482007915543193519614":{"normalized":true,"title":"","url":"https://coub.com/coubnoob","hash":"/coubnoob","data":{},"id":"1687840363482007915543193519614","cleanUrl":"https://coub.com/coubnoob","hashedUrl":"https://coub.com/coubnoob"}},"urlToId":{"https://coub.com/coubnoob":"1687840363482007915543193519614"},"stateToId":{"{\"data\":{},\"title\":\"\",\"url\":\"https://coub.com/coubnoob\"}":"1687840363482007915543193519614"}}"|
|                  | Используется для отслеживания пользовательской активности. | "AF_BANNERS_SESSION_ID"                 | "1687841035200" |
___

### Добавление объектов в Local Storage и Session Storage

Результат выполнения команды в **Local Storage**

![1.1](/materials/1.1.png)

Состояние **Local Storage** после выполнения команды

![2.1](/materials/2.1.png)

Результат выполнения команды в **Session Storage**

![3.1](/materials/3.1.png)

Состояние **Session Storage** после выполнения команды

![4.1](/materials/4.1.png)