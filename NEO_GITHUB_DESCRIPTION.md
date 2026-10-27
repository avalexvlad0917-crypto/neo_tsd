# Текст для GitHub (About + README summary)

## About (короткое описание репозитория, ~150 символов)

```
NEO — открытый Android-ТСД. Сканирование, серии, Честный ЗНАК, обмен JSON/FTP/HTTP с 1С. MIT. package: ru.neo.tsd
```

## Topics (теги)

```
android, tsd, barcode, mlkit, compose, room, 1c, datamatrix, honest-sign, ftp, open-source, kotlin
```

## Website / Homepage

(оставьте пустым или укажите сайт, если появится)

## Releases

Рекомендуемый формат тега: `v1.3.0`  
Прикрепляйте:
- `NEO_sources_1.3.0.zip` (исходники)
- `app-release.apk` или `app-debug.apk` (после сборки)

## Описание для Release v1.3.0

```
## NEO 1.3.0 — полный ребрендинг

### Что изменилось
- Package / applicationId / namespace: **ru.neo.tsd**
- Корневая папка проекта: **NEO**
- Удалены все следы старых имён из кода и документации
- Добавлены LICENSE (MIT) и NOTICE
- Документация обмена и HTTP-сервиса 1С переписана под NEO
- CHANGELOG.md для отслеживания версий

### Сборка
Откройте папку NEO в Android Studio → Sync → Run / assembleDebug.

### Совместимость
Формат JSON обмена 1.1 без изменений. Внешняя обработка 1С — из архива NEO_1C_exchange.
```

## Как вести версии дальше

1. В `app/build.gradle.kts` поднимайте `versionName` (semver) и `versionCode` (целое, например 131, 132…).
2. Добавляйте запись в `CHANGELOG.md`.
3. Коммит + тег `vX.Y.Z` + GitHub Release.
