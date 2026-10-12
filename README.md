# pfs-story-ci

Публичный **репо-сборщик** macOS для PFS Story. Сам исходный код приватный — тянется из
приватного репозитория по read-only deploy-ключу во время сборки. Репозиторий публичный,
поэтому macOS-раннеры GitHub Actions бесплатны без лимитов.

Запуск: Actions → «Build PFS Story macOS» → Run workflow. Готовые .dmg — в артефактах прогона,
обновление уходит на Cloudflare.
