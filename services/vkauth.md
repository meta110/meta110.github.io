---
layout: page
title: "Авторизация Вконтакте"
subtitle: "Получение авторизационного кода"
app_id: 7275612
scope: "offline,groups,ads,stats"
---
## Шаг 1
Пройдите по ссылке на [страницу авторизации Вконтакте](https://oauth.vk.com/authorize?client_id={{ page.app_id }}&display=popup&scope={{ page.scope }}&response_type=code&v=5.103&redirect_uri={{ site.url }}{{ page.url }})

<p id="code"></p>
