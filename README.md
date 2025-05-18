# Sakura

[![license](https://img.shields.io/github/license/code-418-dpr/Sakura)](https://opensource.org/licenses/MIT)
[![release](https://img.shields.io/github/v/release/code-418-dpr/Sakura?include_prereleases)](https://github.com/code-418-dpr/Sakura/releases)

Шаблон

<details>
  <summary><h2>Демо</h2></summary>
   Здесь будут скриншоты, возможно даже видео.
</details>

## Особенности реализации

- веб-приложение
    - [x] хорошо смотрится как на десктопных, так и на мобильных устройствах
- Telegram-бот:
    - ...

## Архитектура

Проект состоит из микросервисов, предназначенных для развёртывания в Docker Compose:

- [веб-приложение](https://github.com/code-418-dpr/Sakura-web)
- [Telegram-бот](https://github.com/code-418-dpr/Sakura-bot)
- PostgreSQL — база данных
- Traefik — обратный прокси

## В планах

- [ ] ...

## Установка

> [!NOTE]
> Мы отказались от использования `git submodules` и `git subtree` из-за периодически возникающей путаницы при
> отслеживании изменений в монорепозиториях. Данный репозиторий представляет собой единую точку для работы с проектом,
> лишённую этих недостатков.

0. Клонируйте репозиторий и перейдите в его папку.
1. Клонируйте репозитории сервисов, входящих в состав проекта по SSH (рекомендуется):

```shell
git clone git@github.com:code-418-dpr/Sakura-web.git services/Sakura-web
git clone git@github.com:code-418-dpr/Sakura-bot.git services/Sakura-bot
```

или по HTTPS:

```shell
git clone https://github.com/code-418-dpr/Sakura-web.git services/Sakura-web
git clone https://github.com/code-418-dpr/Sakura-bot.git services/Sakura-bot
```

После этого вы можете вносить изменения в каждый из сервисов по-отдельности (в соответствии с инструкциями, описанными в
соответствующих README).

## Запуск и модификация

0. Установите проект по инструкции выше.
1. Создайте файл `.env` на основе [.env.template](.env.template) и задайте все указанные там параметры.
2. Установите Docker.
3. Теперь запускать проект **на сервере** можно командой:

```shell
docker compose --profile server up -d --build
```

При модификации сервисов проекта и их тестировании может потребоваться создание файлов .env для каждого из них. Однако,
при запуске всех сервисов в одном контейнере (из этого репозитория) их не должно быть. Чтобы не удалять их, для запуска
сервисов **на локальном устройстве** можно воспользоваться следующим набором команд:

```shell
mv ./services/Sakura-web/.env ./services/Sakura-web/_.env
mv ./services/Sakura-bot/.env ./services/Sakura-bot/_.env 
docker compose --profile local up -d --build
mv ./services/Sakura-web/_.env ./services/Sakura-web/.env 
mv ./services/Sakura-bot/_.env ./services/Sakura-bot/.env
```
