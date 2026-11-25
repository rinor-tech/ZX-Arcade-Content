# ZX-Arcade-Content

Публичный каталог и схема ZX-Arcade. В этом репозитории нет образов игр, обложек и архива комплекта.

Скачать игру отсюда нельзя. Поля `downloadable` и `offline` в манифесте равны `false`. У строк нет публичного URL файла: статус `unavailable` / `unpublished`.

Локальный комплект собран отдельно. У его файлов `legal_status` остаётся `unknown`. Это не разрешение на распространение и не то же самое, что `allowed` или `allowedzxart`. Пока права набора не подтверждены, бинарные файлы в репозиторий и в GitHub Releases не входят.

Состав каталога: [`catalog/games.csv`](catalog/games.csv) и [`catalog/manifest.json`](catalog/manifest.json). Схема и вымышленный пример: [`schema/`](schema/).

Маленький файл для проверки публикации: [`catalog/publication-check.txt`](catalog/publication-check.txt). Это текст схемы, не игра.
