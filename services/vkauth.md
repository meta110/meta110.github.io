---
layout: page
title: "Авторизация Вконтакте"
subtitle: "Получение авторизационного кода"
app_id: 7275612
scope: "offline,groups,ads,stats"
---
Чтобы получить ключ доступа к статистике Вконтакте, внимательно выполните следующие действия.
## Шаг 1. Разрешите доступ к статистике вашего рекламного кабинета Вконтакте
Пройдите по ссылке на [страницу авторизации Вконтакте](https://oauth.vk.com/authorize?client_id={{ page.app_id }}&display=popup&scope={{ page.scope }}&response_type=code&v=5.103&redirect_uri={{ site.url }}{{ page.url }}) и нажмите кнопку "Разрешить".

![Предоставление доступов Вконтакте](/img/vk_grant_access.png){: .center-block :}

## Шаг 2. Получите токен для работы приложения {#step2}
{: .box-note}
**Note:** Ваш код доступа: <span id="code"></span>
Пройдите по ссылке и получите токен <a id="link2" href="">вторая ссылка</a>
