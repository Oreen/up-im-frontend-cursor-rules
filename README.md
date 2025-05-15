# Cursor Rules for NextJS Projects

Репозиторий с централизованными правилами для IDE Cursor для NextJS проектов.

## Содержимое

- `typescript-react.json` - Правила для TypeScript и React в NextJS

## Как использовать

### Добавление в проект

```bash
# В корневой директории вашего проекта
mkdir -p .cursor
git submodule add https://github.com/your-username/cursor_rules_nextjs_rules .cursor/rules
```

### Обновление правил

```bash
# Обновление submodule до последней версии
git submodule update --remote .cursor/rules
git add .cursor/rules
git commit -m "Update cursor rules"
```

### Для новых клонов

```bash
# После клонирования основного репозитория
git submodule init
git submodule update
```

## Содержимое правил

Правила включают стандарты кодирования для:
- TypeScript/JavaScript
- React/NextJS
- HTML/CSS/SCSS
- Соглашения по именованию
- Структура компонентов и проекта 