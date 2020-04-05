---
layout: page
title: "Авторизация Яндекс"
subtitle: "Получение доступа к сервисам"
app_id: "764f4af41256427ba87965a7ed31ea3d"
bigimg:
  - "/img/VK_dogs.png" : "Гав-гав!"
---
Чтобы получить ключ доступа (access token) к сервисам Яндекс

[Получить токен авторизации](https://oauth.yandex.ru/authorize?response_type=token&client_id={{ page.app_id }}&redirect_uri={{ site.url }}{{ page.url }})

{% include social-share.html %}