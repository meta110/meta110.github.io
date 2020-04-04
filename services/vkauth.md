---
layout: page
title: "Авторизация Вконтакте"
subtitle: "Получение авторизационного кода"
app_id: 7275612
scope: "offline,groups,ads,stats"
---
Чтобы получить ключ доступа к статистике Вконтакте, внимательно выполните следующие действия.
## Шаг 1. Разрешите доступ к статистике вашего рекламного кабинета Вконтакте
Пройдите по ссылке на [страницу авторизации Вконтакте](https://oauth.vk.com/authorize?client_id={{ page.app_id }}&display=popup&scope={{ page.scope }}&response_type=code&v=5.103&redirect_uri={{ site.url }}{{ page.url }}#step2) и нажмите кнопку "Разрешить":

![Предоставление доступов Вконтакте](https://github.com/meta110/meta110.github.io/blob/master/img/vk_grant_access.png?raw=true){: .center-block :}

## Шаг 2. Получите токен для работы приложения {#step2}

{: .box-note}
**Ваш код доступа:** <span id="code"></span>

Чтобы получить токен <a id="link2" href="javascript: void(0)">пройдите по ссылке</a> (ссылка неактивна, если код доступа не был получен).

Сохраните токен доступа, как выделено на изображении:

![Сохранение токена Вконтакте](https://github.com/meta110/meta110.github.io/blob/master/img/vk_access_token?raw=true){: .center-block :}

{: .box-warning}
**Внимание:** Если вместо токена вы увидите предупреждение:

![Время действия кода закончилось](https://github.com/meta110/meta110.github.io/blob/master/img/vk_access_expired?raw=true){: .center-block :}

Это означает, что время действия кода доступа закончилось. Перезагрузите [эту страницу по ссылке]({{ site.url }}{{ page.url }}) и попробуйте снова.
