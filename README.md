# Liquidity & Volume Nexus — User Manual (GitHub Pages)

Готовая раскладка для публикации мануала v2.4.2 на GitHub Pages.
`index.html` — это manual.html, переименованный так, чтобы Pages открывались
сразу по корневой ссылке (без `/manual.html` в конце).

## Публикация (5 минут)

1. Создайте публичный репозиторий на github.com, например `lvn-manual`.
2. Загрузите в корень репозитория **содержимое этой папки**:
   - `index.html`
   - `images/` (вся папка)
   - `.nojekyll` (не удаляйте — он отключает Jekyll-обработку и гарантирует,
     что все файлы отдаются как есть)
   - этот `README.md` (по желанию)
3. В репозитории: **Settings → Pages → Build and deployment → Source: Deploy
   from a branch → Branch: main, папка / (root) → Save**.
4. Через 1–2 минуты мануал будет доступен по адресу:
   `https://<ваш-логин>.github.io/lvn-manual/`
   Откройте и проверьте: картинки грузятся, боковое меню работает, поиск по
   якорям (например `#s1-watch`) переходит к главам.
5. Вставьте эту ссылку вместо плейсхолдера
   `https://YOUR-USERNAME.github.io/YOUR-REPO/` в двух файлах описания товара
   (`store/description.txt` и `store/description.html`).

## Обновление мануала в будущем

Просто замените `index.html` и/или файлы в `images/` новым коммитом — Pages
пересоберутся автоматически за 1–2 минуты. Версию не забудьте синхронизировать в трёх
местах: `<title>` мануала, блок «What changed since v2.3.0» и шапка
индикатора (PanelHeaderVersion / ProductVersion).

## Проверка перед публикацией товара в cTrader Store

- [ ] Ссылка Pages открывается в приватном окне (без вашего кэша).
- [ ] Все 26 изображений мануала на месте (`images/`), битых ссылок нет.
- [ ] Плейсхолдер ссылки заменён в description.txt и description.html.
- [ ] В Gallery загружены ≥3 скриншотов из `store/gallery/` (ширина ≥800 px).
- [ ] Короткое описание ≤120 символов (в `store/short_description.txt` — 114).
- [ ] Disclaimer присутствует в конце описания (требование модерации).
- [ ] Заголовок товара: `Liquidity and Volume Nexus` (без «&» и спецсимволов).

</content>
