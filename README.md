# Кейс от Фгану НИИ Специализированные вычислительные устройства защиты и автоматика 

## Реализованная функциональность

- **Авторизация/регистрация**
- **Аутентификация по коду (почта)**
- **Система вывода пользователей, вакансий, предложений, городов, названий площадок, резюме, постов, навыков (перечислены все страницы, что были сделаны)**
- **Настроены связи между таблицами (промежуточные таблицы)**
- **SMTP (yandex)**
- **Были прописаны сидеры для БД**
- **PWA**
- **Логика вывода вакансий/пользователей/предложений**
- **WebSockets (pusher)**
- **Чат**

## Особенность проекта заключается в следующем

- **SMTP**: Регистрация с рабочей аутентификацией по почте (сверстано даже письмо).
- **PWA**: Гугл фича не только гугла, но и наша, в нашем проекте.
- **БД настроены через связи, никакого хлама, только Eloquent ORM**
- **Чат**
- **WebSockets (pusher)**

## Основной стек технологий

- **HTML (Bootstrap), SASS, JavaScript, Vue.js**
- **PHP 8, MySQL**
- **Laravel**
- **Webpack, Babel**
- **Git**

## Демо

Демо сервиса будет доступно по адресу: ( неактуально ).
Реквизитов тестового пользователя не предусмотрено, простая регистрация по коду из почты.

## Среда запуска

1. Развертывание сервиса производится на Ubuntu.
2. Требуется поддержка PHP 8.1+.
3. Требуется установленная СУБД MySQL.

## Выполнение миграций

Для заполнения базы данных системной информацией выполните в корневой папке сервиса:
```bash
php artisan migrate --seed
