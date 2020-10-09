# Чатик

Сервис, где люди могут пообщаться

# В работе использовались:

- HTML
- Stylus
- TS
- БЭМ
- Docker
- Mocha/Chai

# Heroku

https://chatttik.herokuapp.com/

# Какие есть страницы

- Регистрация ("/reg")
- Авторизация ("/auth")
- Сам чат ("/chat")
- Страница для ошибки 500 ("/error")
- Страницы для ошибки 404 ("/not-found")
- Информация о пользователе ("/user-info")
- Создать новый чат ("/new-chat")
- Поменять пароль ("/pass")

# Установка

Перед началом работы необходимо проверить наличие установленного node.js и npm

Скопируйте проект на компьютер:

```
git clone https://github.com/kirpinev/mf.messenger.praktikum.yandex.git
```

Установите зависимости:

```
npm install
```

# Сборка для разработки

```
npm run dev
```

# Сборка для продакшена

```
npm run build
```

# Локальный сервер

```
npm run start
```

# Тестирование

```
npm run test
```
