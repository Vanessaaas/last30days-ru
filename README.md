# last30days-ru

Скилл для Claude Code: собирает, что за последние 30 дней обсуждали по теме в русскоязычном интернете (Telegram, VK, DTF, Habr, VC.ru, Pikabu, YouTube/Rutube, каталог Яндекс Игр), и выдаёт отчёт с трендами, цифрами и ссылками. API-ключи не нужны.

Идея взята из [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill), адаптирована под рунет.

## Установка

```bash
git clone https://github.com/Vanessaaas/last30days-ru.git ~/.claude/skills/last30days-ru
```

Перезапустите Claude Code.

## Использование

```
/last30days-ru <тема> [--days=N] [--quick|--deep] [--preset=yandex-games] [--save]
```

Пример: `/last30days-ru тренды Яндекс Игр --deep --save`

Проверенные источники добавляйте в `sources.md`: скилл начинает поиск с них.
