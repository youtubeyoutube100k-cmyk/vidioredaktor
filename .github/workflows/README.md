# VidioRedaktor Cloud AI

Автономный видеоредактор коротких вертикальных видео (Shorts, Reels, TikTok) на базе **GitHub Actions**.

## Как запустить:

1. Скопируйте файлы репозитория в ветку `main`:
   - `.github/workflows/render.yml`
   - `index.html`
2. Перейдите в **Settings** -> **Pages** и включите GitHub Pages из ветки `main` (папка `/root`).
3. Получите Personal Access Token в [GitHub Settings -> Tokens](https://github.com/settings/tokens) с правами `workflow`.
4. Откройте опубликованный сайт GitHub Pages, вставьте ссылку на исходное видео и запустите рендеринг.
