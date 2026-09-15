<div align="center">

# ⚡ Live Turbo — загрузки

**Официальные сборки приложения Live Turbo для всех платформ.**

[🌐 Страница загрузки](https://app.liveturbo.ru/get) · [▶️ Google Play](https://play.google.com/store/apps/details?id=ru.liveturbo.app)

</div>

---

## Скачать

| Платформа | Ссылка | Примечание |
|-----------|--------|------------|
| 💻 **Windows 10/11** (64-бит) | [Скачать установщик](https://github.com/LiveTurboDev/liveturbo-platforms/releases/latest/download/LiveTurbo-Setup-amd64.exe) | Версия 1.0.10 · 24 МБ · обновляется прямо в приложении |
| 🤖 **Android** (Google Play) | [Установить](https://play.google.com/store/apps/details?id=ru.liveturbo.app) | Рекомендуется — автообновление через Маркет |
| 🤖 **Android** (APK) | [Live Turbo 0.7.11](https://github.com/LiveTurboDev/liveturbo-platforms/releases/tag/v0.7.11) | Для устройств без Google Play |
| 🍏 **iOS** | 🛠 в разработке | — |
| 🍎 **macOS** | 🛠 в разработке | — |

> 📍 Быстрее всего скачать с нашей страницы: **https://app.liveturbo.ru/get** — там же инструкция по установке и раздел для iPhone.

## Установка на Windows

1. Скачайте установщик: [постоянная ссылка на последнюю версию](https://github.com/LiveTurboDev/liveturbo-platforms/releases/latest/download/LiveTurbo-Setup-amd64.exe).
   Она всегда ведёт на свежую сборку, её можно давать людям один раз и не менять.
2. Запустите файл. Windows спросит разрешение на запуск от имени администратора — оно нужно, чтобы приложение
   могло создать сетевой адаптер и направить через него трафик.
3. Если появится синее окно «Windows защитила ваш компьютер» — нажмите «Подробнее» → «Выполнить в любом случае».
   Установщик пока без сертификата подписи, поэтому SmartScreen предупреждает о незнакомом издателе.
4. Войдите через Google, Яндекс, почту или Telegram — подписка и серверы подтянутся сами.

Обновления приходят внутри приложения: «Настройки → Проверить обновление». Новая версия скачивается,
проверяется по контрольной сумме и ставится поверх текущей.

## Установка APK (Android)

1. Скачайте `.apk` из [релиза 0.7.11](https://github.com/LiveTurboDev/liveturbo-platforms/releases/tag/v0.7.11).
2. Откройте файл — Android предложит разрешить установку из этого источника, подтвердите.
3. На Xiaomi/MIUI при первом запуске может потребоваться отключить «Оптимизацию MIUI» — подробности в приложении.

APK-версия обновляется сама: приложение проверяет наличие новой сборки и предлагает установить.

## Проверка подлинности

**Android.** Все сборки подписаны нашим релизным ключом:

- **SHA-256:** `6D:34:2C:5E:CA:2E:79:54:FD:81:99:0C:97:B1:0B:24:8F:C2:AA:9D:6E:4D:87:46:99:24:4F:2E:F9:77:5D:DD`

**Windows.** Рядом с установщиком в каждом релизе лежит файл `SHA256.txt` с контрольной суммой.
Проверить скачанный файл можно в PowerShell:

```powershell
Get-FileHash .\LiveTurbo-Setup-amd64.exe -Algorithm SHA256
```

Сумма версии 1.0.10: `de2d7122b39ec8a7f688628a093d66734b21625553177cbf3ed17d8f82e92323`

---

<div align="center">
<sub><a href="https://liveturbo.ru">liveturbo.ru</a></sub>
</div>
