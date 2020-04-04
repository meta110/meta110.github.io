---
layout: page
title: "Авторизация Вконтакте"
subtitle: "Получение авторизационного кода"
app_id: 7275612
scope: "offline,groups,ads,stats"
---
## Шаг 1. Разрешите доступ к статистике вашего рекламного кабинета Вконтакте
Пройдите по ссылке на [страницу авторизации Вконтакте](https://oauth.vk.com/authorize?client_id={{ page.app_id }}&display=popup&scope={{ page.scope }}&response_type=code&v=5.103&redirect_uri={{ site.url }}{{ page.url }}) и нажмите кнопку "Разрешить"

<a id="link1" href="https://oauth.vk.com/authorize?client_id={{ page.app_id }}&display=popup&scope={{ page.scope }}&response_type=code&v=5.103&redirect_uri={{ site.url }}{{ page.url }}">страницу авторизации Вконтакте</a>

<p id="code"></p>
## Шаг 2. Получите токен для работы приложения
Пройдите по ссылке <a id="link2" href="">вторая ссылка</a>
