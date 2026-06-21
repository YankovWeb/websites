# Websites

Лендингове за YankovWeb, хоствани на GitHub Pages.

| Проект | Линк |
|---|---|
| Adria | [https://yankovweb.github.io/websites/adria](https://yankovweb.github.io/websites/adria) |
| Kafene Mirela | [https://yankovweb.github.io/websites/kafene-mirela](https://yankovweb.github.io/websites/kafene-mirela) |
| Test Cafe Sofia | [https://yankovweb.github.io/websites/test-cafe-sofia](https://yankovweb.github.io/websites/test-cafe-sofia) |

## Deployment

Всеки проект е поддиректория с `index.html`. За деплой:

```bash
./deploy-websites.sh <project-name>
```

Скриптът:
1. Клонира/обновява репото `YankovWeb/websites`
2. Копира проектната директория
3. Генерира/обновява README.md с таблица на всички проекти
4. Commits и push-ва към `main`

README.md автоматично се регенерира при всеки deploy.
