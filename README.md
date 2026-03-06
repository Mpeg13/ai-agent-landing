# OpenClaw Workspace

Рабочее пространство Оскара - AI помощника Максима.

## О проекте

Это workspace содержит все файлы, скрипты и настройки для работы Оскара как AI помощника. Здесь хранятся:

- Конфигурационные файлы
- Скрипты автоматизации
- Документация
- Проекты и задачи
- Навыки (skills)

## Структура

```
workspace/
├── skills/                    # Навыки OpenClaw
│   ├── github/               # Навык для работы с GitHub
│   ├── sportit-outreach-automation/ # Автоматизация рассылок
│   └── ...                   # Другие навыки
├── memory/                   # Ежедневные заметки и память
├── sportit-new-website/     # Проект нового сайта Sportit
├── video-production/        # Видео продакшн проекты
├── *.py                     # Python скрипты
├── *.md                     # Документация
└── *.csv                    # Данные контактов
```

## Навыки (Skills)

### GitHub Skill
Навык для работы с Git и GitHub. Включает:
- Скрипты для настройки
- Шпаргалки по Git
- Автоматизацию бэкапов

### Sportit Outreach Automation
Навык для автоматизации email рассылок для Sportit.

## Проекты

### Sportit Новый Сайт
Разработка нового сайта для Sportit с современным дизайном и функциональностью.

### Email Кампании
Автоматизированные email рассылки для привлечения клиентов.

### Видео Продакшн
Создание видео контента для маркетинга.

## Использование

### Git команды
```bash
# Статус репозитория
git status

# Добавить изменения
git add .

# Создать коммит
git commit -m "Сообщение"

# Отправить в GitHub
git push origin main
```

### Полезные скрипты
```bash
# Бэкап workspace в GitHub
./skills/github/scripts/backup-workspace.sh

# Инициализация нового проекта
./skills/github/scripts/init-project.sh
```

## Конфигурация

### Git настройки
```bash
git config --global user.name "Оскар (OpenClaw Assistant)"
git config --global user.email "assistant@openclaw.ai"
```

### GitHub аутентификация
Для работы с GitHub требуется Personal Access Token с правами `repo`.

## Лицензия

Приватный репозиторий. Все права защищены.

## Контакты

- **Владелец**: Максим Харитонов
- **Ассистент**: Оскар (OpenClaw AI Assistant)
- **Создано**: 2026-02-24