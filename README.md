# K0uzer

Делаю веб-интерфейсы и изучаю Go. Здесь собраны проекты по фронтенду, сборке приложений и учебные упражнения, на которых разбираюсь с устройством языка и серверной разработкой.

[Изучаю Go](#сейчас-изучаю-go) · [Go-проекты](#учебные-проекты-на-go) · [Веб-проекты](#веб-проекты) · [Другие профили](#другие-профили)

**Технологии:** Go · TypeScript · JavaScript · React · Next.js · Webpack · SCSS · C#.

## Сейчас изучаю Go

- Срезы, строки, функции, замыкания и обработку ошибок.
- Структуры, методы, интерфейсы, композицию и generics.
- Табличные тесты, JSON, `net/http` и CRUD API.

## Учебные проекты на Go

Каждое упражнение вынесено в отдельный репозиторий. В README указаны назначение, команды запуска и результаты проверок.

- [TextAnalyzer](https://github.com/K0uzer/TextAnalyzer) — CLI-анализатор текста: слова, руны, частоты и топ слов; есть табличные тесты. Счётчик строк считает символы `\n`.
- [http](https://github.com/K0uzer/http) — HTTP CRUD API задач на `net/http`, JSON и хранение в памяти. Данные сбрасываются при остановке сервера.
- [interfaces](https://github.com/K0uzer/interfaces) и [embedding](https://github.com/K0uzer/embedding) — работа с `io.Reader`, подсчёт слов и обёртка над `io.Writer`, добавляющая временную метку.
- [filterOdd](https://github.com/K0uzer/filterOdd) — фильтрация нечётных чисел с переиспользованием исходного массива; тесты проверяют результат и работу с памятью.
- [generics](https://github.com/K0uzer/generics) — упражнения с `Set`, `Reduce` и функциональными опциями; пока не собирается из-за неиспользуемых переменных.
- [json](https://github.com/K0uzer/json) — заготовка чтения и записи статьи с JSON-тегами; реализация пока не завершена и не собирается.

Это учебная коллекция в разном состоянии, а не набор готовых сервисов. На момент проверки 22 ноября 2026 года из 27 папок 18 проходят `go test ./...` и `go vet ./...`, восемь содержат существующие ошибки, одна остаётся пустой заготовкой. Успех `go test` в папках без тестов означает только проверку сборки.

## Веб-проекты

- [webpack](https://github.com/K0uzer/webpack) — сборка для React, TypeScript и SCSS.
- [ReactWebpackBeginningProd](https://github.com/K0uzer/ReactWebpackBeginningProd) — работа над сборкой приложения и её подготовкой к production.
- [monorep-webpack](https://github.com/K0uzer/monorep-webpack) — монорепозиторий с пакетами и сервисами.
- [Auth-toolkit](https://github.com/K0uzer/Auth-toolkit) — проект инструментов авторизации на Next.js и Auth.js; находится в разработке.
- [learning](https://github.com/K0uzer/learning) — вопросы, задачи и ссылки для подготовки по JavaScript и React.

## Другие профили

[GitHub](https://github.com/K0uzer) · [Codewars](https://www.codewars.com/users/K0uzer)
