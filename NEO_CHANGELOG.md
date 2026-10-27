# Changelog

Все значимые изменения проекта NEO документируются в этом файле.

Формат основан на [Keep a Changelog](https://keepachangelog.com/ru/1.1.0/),
версионирование — [Semantic Versioning](https://semver.org/lang/ru/).

## [1.3.0] — 2026-10-27

### Changed
- Полный ребрендинг: package и namespace `ru.neo.tsd`
- Удалены все упоминания старого имени проекта из кода, ресурсов и документации
- Корневая папка проекта: `NEO`
- README, docs/EXCHANGE.md, docs/1c/* переписаны под NEO
- HTTP-сервис в документации: `neo` / `HTTPService_NEO.md`

### Added
- LICENSE (MIT)
- NOTICE (отказ от связи с коммерческими брендами + third-party)
- CHANGELOG.md

### Technical
- versionName = 1.3.0, versionCode = 130
- applicationId = ru.neo.tsd

## [1.2.x] — 2026-09

- FTP auto-sync
- DataMatrix / Честный ЗНАК (AI 01 + 21)
- Серии во всех типах документов
- Клиентская запись файлов для UNC-шар
- UUID merge при загрузке документов в 1С
- Фильтр периода в обработке 1С
- Документы: Заказ клиента, Приходный/Расходный ордер

## [1.1.x] — 2026-09

- Jetpack Compose UI
- ML Kit barcode (камера)
- Room + Gson
- Базовый JSON-обмен (файл / HTTP)
- Аппаратный сканер (key events / broadcast)

[1.3.0]: https://github.com/YOUR_ORG/NEO/releases/tag/v1.3.0
