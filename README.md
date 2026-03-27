<p align="center">
  <img src="assets/kabanchikom.png" alt="Выгоревший кабанчик" width="400">
</p>

# burnt-out-claude-spinner

Спиннер Claude Code для выгоревших.

Вместо стандартных `Thinking...`, `Analyzing...`, `Pondering...` будет крутиться **"Как же всё заебало..."**, **"А кто-то сейчас на Мальдивах..."** и ещё 30 фраз от агента, который больше не может.

> Форк [claude-code-spinner](https://github.com/i1kazantsev/claude-code-spinner) от [@neserioznoeit](https://t.me/neserioznoeit). Респект за идею и оригинал.

## Установка через Claude Code

```bash
git clone https://github.com/dalamber/burnt-out-claude-spinner.git
cd burnt-out-claude-spinner
```

Запусти Claude Code и выполни:

```
/install-spinner
```

## Ручная установка

Скопируй содержимое `spinners.json` в `~/.claude/settings.json`:

```json
{
  "spinnerVerbs": {
    "mode": "replace",
    "verbs": ["Как же всё заебало...", "А кто-то сейчас на Мальдивах...", "..."]
  }
}
```

## Хук на Stop

Звуковой хук из оригинала тоже работает — см. [оригинальный репозиторий](https://github.com/i1kazantsev/claude-code-spinner) или выполни `/install-hook`.

## Лицензия

MIT

## Оригинал

Идея и реализация: [i1kazantsev/claude-code-spinner](https://github.com/i1kazantsev/claude-code-spinner) / Телега: [Несерьезный айтишник](https://t.me/neserioznoeit)
