# ZXCRANDOMCROSSHAIR

Рандомизатор пользовательских прицелов для War Thunder.

Оригинальная идея и основа — [ReDegenerator/WTRandomizer](https://github.com/ReDegenerator/WTRandomizer).

## Что делает

- Рандомит прицелы для всех танков из `tanks.txt` при **каждом заходе в игру**.
- Рандомизация происходит **после закрытия игры** — быстро и без повторов.
- Список танков хранится в файле `tanks.txt`, а не в коде — можно менять без пересборки.

## Установка

1. Скачай `.exe`-файл со страницы [Releases](https://github.com/ReDegenerator/WTRandomizer/releases/tag/Release).
2. Создай папку в любом удобном месте и перенеси туда программу.
3. Запусти программу — она сама найдёт папку с прицелами и создаст файл с путями.

## Использование

1. Запусти `ZXCRANDOMCROSSHAIR.exe`.
2. Нажми **`1`** — программа найдёт папку с прицелами на компьютере и сразу рандомит их.
3. Нажми **`2`** — чтобы прицелы рандомились **каждый раз при заходе в игру** (после перезапуска ПК).

## Важно: где должны лежать прицелы

Прицелы (`*.blk`-файлы) клади сюда:

    Documents\My Games\WarThunder\Saves\<твой_ID>\production\UserSights\

**Прямо в корень `UserSights`**, а не в подпапки `all_tanks` или `tank_sight_presets` — иначе игра их не увидит.

Если прицелы уже лежат в подпапке `all_tanks` — либо перенеси их, либо смотри раздел «Разработка» ниже (там про `FlattenUserSights`).

## Файл `tanks.txt`

- Лежит рядом с `.exe`.
- Один игровой ID танка на строку.
- Без кавычек, без запятых.
- Строки, начинающиеся с `#`, игнорируются (комментарии).

Пример:

    germ_vk_3002m
    ussr_t_80bvm
    us_m1a2_abrams

## Мои каналы

- YouTube: [@milyjmedvedghoulssszxc](https://www.youtube.com/@milyjmedvedghoulssszxc)
- Twitch: [milyjmedvedghoulsss](https://www.twitch.tv/milyjmedvedghoulsss)
