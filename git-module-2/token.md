# Генерація Github токена

1. Переходимо за посиланням https://github.com
2. Клікаємо на аватарці, вибираємо "Settings"

![github-settings](./github-settings.png)

3. На вкладці ["profile"](https://github.com/settings/profile) вибираємо "Developer settings"

![developer-settings](./developer-settings.png)

4. Клікаємо на ["Personal access tokens"](https://github.com/settings/tokens)

![personal-access-tokens](./personal-access-tokens.png)

* Натискаємо на кеопку "Generate new token"
* Заповнюємо поля:
  * Note: "bootcamp"
  * Expiration: 90
  * Вибираємо "repo" checkbox
  * Клікаємо на "Generate token"

![new-token](./new-token.png)

5. Копіюємо токен та зберегаємо в надійному місці, повторно скопіювати його буде наможливо

![generated-token](./generated-token.png)

6. Переходимо до вашого форку репозиторія

![clone-repo](./clone-repo.png)

* Копіюємо посилання `https://github.com/<посилання на ваш репозиторій>.git`
* Додаємо токен до посилання `https://<ваш токен>@github.com/<посилання на ваш репозиторій>.git`
* В корні проекта виконуємо команду `git remote set-url origin <посиляння з токеном>`
