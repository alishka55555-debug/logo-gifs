# Логотипы — GIF процесса и файлы для сайта

Записи процесса создания двух логотипов: **олень** (в стиле Hydro Flask) и
**SHARK** (вордмарк-акула). Водяные знаки убраны.

## GIF процесса

| Файл | Что это | Длительность |
|---|---|---|
| [`gif/deer_logo_process_2x.gif`](gif/deer_logo_process_2x.gif) | олень, ускорено ×2 | 18,9 с |
| [`gif/shark_logo_process_2x.gif`](gif/shark_logo_process_2x.gif) | SHARK, ускорено ×2 | 11,0 с |
| [`gif/deer_logo_process.gif`](gif/deer_logo_process.gif) | олень, реальная скорость | 37,8 с |
| [`gif/shark_logo_process.gif`](gif/shark_logo_process.gif) | SHARK, реальная скорость | 22,0 с |

480×854, 12 кадров/с, бесконечный цикл.

## Для сайта

| Файл | Что это |
|---|---|
| [`web/deer_process_web.mp4`](web/deer_process_web.mp4), [`web/shark_process_web.mp4`](web/shark_process_web.mp4) | видео 9:16, 720×1280, H.264 |
| [`web/deer_process_web.jpg`](web/deer_process_web.jpg), [`web/shark_process_web.jpg`](web/shark_process_web.jpg) | постеры для `poster` |
| [`tiles/deer_tile.mp4`](tiles/deer_tile.mp4), [`tiles/shark_tile.mp4`](tiles/shark_tile.mp4) | видео-плитки 1:1, 720×720 |
| [`tiles/deer_tile.png`](tiles/deer_tile.png), [`tiles/shark_tile.png`](tiles/shark_tile.png) | логотипы-плитки 1000×1000 |
| [`tiles/*_tile_transparent.png`](tiles/) | то же с прозрачным фоном |
| [`web/embed_example.html`](web/embed_example.html) | пример сетки плиток |

## Логотипы

- [`logos/deer_logo.svg`](logos/deer_logo.svg), [`logos/shark_logo.svg`](logos/shark_logo.svg) — векторы
- [`logos/*_poster.png`](logos/) — статичные PNG
- [`logos/*_logo_white.gif`](logos/), [`logos/*_logo_transparent.gif`](logos/) — анимация появления знака

## Встраивание

```html
<video src="web/deer_process_web.mp4"
       poster="web/deer_process_web.jpg"
       autoplay muted loop playsinline preload="metadata"
       style="width:100%;aspect-ratio:9/16;object-fit:cover;border-radius:18px"></video>
```

`autoplay muted loop playsinline` — обязательный минимум, чтобы видео само
запускалось на мобильных.
