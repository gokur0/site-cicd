# Учебное портфолио — CI/CD

Простой многостраничный сайт-портфолио для лабораторной работы № 6.

[![Deploy static site](https://github.com/gokur0/site-cicd/actions/workflows/deploy.yml/badge.svg)](https://github.com/gokur0/site-cicd/actions/workflows/deploy.yml)

## Состав проекта
- `index.html` — главная страница
- `projects.html` — учебные проекты
- `about.html` — описание CI/CD-процесса
- `style.css` — адаптивные стили
- `.github/workflows/deploy.yml` — проверка HTML и деплой на GitHub Pages

## Публикация
Workflow запускается при каждом `push` в ветку `main`, проверяет HTML с помощью HTMLHint и публикует сайт на GitHub Pages.

В репозитории откройте **Settings → Pages** и установите **Source: GitHub Actions**.

После успешного запуска сайт будет доступен по адресу:
`https://gokur0.github.io/site-cicd/`

> Адрес заработает после включения Pages и успешного выполнения workflow.