# SvelteKit на Deno

Пример приложения [SvelteKit](https://svelte.dev/docs/kit) на [Deno](https://deno.com/).

## Параметры деплоя

Выберите рантайм **Deno**, фреймворк **SvelteKit** и тип приложения **frontend**. Для frontend будет опубликована статическая сборка.

| Параметр | Значение |
| --- | --- |
| Фреймворк | SvelteKit |
| Версия Deno | 2.7.14 |
| Тип приложения | `frontend` |
| Команда сборки | `deno task build` |
| Директория сборки | `build` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
deno install --allow-scripts

# сборка для продакшн
deno task build
```
