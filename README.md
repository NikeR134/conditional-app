# Conditional приложение

Spring Boot приложение выбирает профиль по свойству `netology.profile.dev` и возвращает его через `GET /profile`.

Для запуска:

```bash
mvn spring-boot:run
```

При значении `true` ответ будет `Current profile is dev`. При значении `false` ответ будет `Current profile is production`.
