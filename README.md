# SimpleWhitelist (Velocity)

Velocity-плагин whitelist для Minecraft **26.1** (и более старых версий через Velocity 3.5.0+).

## Требования

- **Velocity** 3.5.0+
- **Java** 21+ (для сборки)

## Сборка

```powershell
$env:JAVA_HOME = "C:\Program Files\BellSoft\LibericaJDK-21-Full"
.\gradlew.bat :velocity:build
```

Готовый jar: `velocity/build/libs/simplewhitelist-velocity-2.0.1.jar`

## Установка

Положите jar в `plugins/` Velocity и перезапустите прокси.

Конфигурация: `plugins/simplewhitelist/config.yml` и `whitelist.txt`
