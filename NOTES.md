# Примечание об ограничениях GitHub Free

Практическое задание требует одновременно:

- приватный репозиторий (`Private`);
- защиту основной ветки `main` (branch protection);
- запрет прямых коммитов и обязательное ревью.

На бесплатном тарифе GitHub (Free) branch protection и repository rulesets
недоступны для приватных репозиториев: API возвращает

```text
403 Upgrade to GitHub Pro or make this repository public to enable this feature.
```

Поэтому для демонстрации работающего механизма репозиторий переведён в `Public`.
Все остальные требования выполнены: правило защиты `main`, обязательный Pull Request,
минимум один ревьюер, `Include administrators`, запрет прямых коммитов.

Для приватного варианта достаточно подключить GitHub Pro (бесплатно для студентов
через GitHub Student Developer Pack), переключить видимость репозитория в `Private`
и заново применить правило защиты ветки.
